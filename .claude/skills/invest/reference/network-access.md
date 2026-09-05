# Network access required by this skill

The research method in `SKILL.md` asks for primary sources — filings, regulator
orders, company IR pages. In an Anthropic-hosted cloud environment those are
reachable only if the environment's network policy allows them.

## Symptom

Findings degrade to search-result summaries and the phase output carries a line like:

> No primary filing was retrievable — every external domain is blocked by this
> environment's network egress proxy.

`WebFetch` returns `EGRESS_BLOCKED`, and `curl` reports
`CONNECT tunnel failed, response 403`. `WebSearch` still works, because it runs on
Anthropic's side rather than through the session's network — which is why a run can
look partially successful while never touching a filing.

## Diagnosis

```sh
curl -sS -o /dev/null -w '%{http_code}\n' https://data.sec.gov/    # 403 => blocked
curl -sS "$HTTPS_PROXY/__agentproxy/status"                        # proxy state
sed -n '/403 . 407/,/###/p' /root/.ccr/README.md                   # the official reading
```

A 403 or 407 at CONNECT is an egress-policy denial. Per `/root/.ccr/README.md`, do
not retry it or route around it — report the blocked host and fix the policy.

## Fix

The default **Trusted** access level allows package registries, GitHub and cloud
SDKs, and nothing else. Equity research needs more.

At claude.ai/code, open the environment selector (the cloud icon showing the
environment name, in the row above the message box — there is no settings URL),
edit the environment, and set:

- **Network access** → **Custom**
- **Allowed domains** → paste `network-allowlist.txt` from this directory
- Tick **"Also include default list of common package managers"** so GitHub,
  npm and PyPI keep working

A leading `*.` matches every subdomain. **Full** also works but grants any domain;
a named list keeps the egress surface deliberate.

The policy is bound when the session's VM is created, so **an existing session keeps
its old policy** — start a new session after saving.

## What it buys

| Domain | Closes |
|---|---|
| `data.sec.gov` | XBRL `companyfacts` — reported figures become `[FACT]` instead of `[ANALYST ESTIMATE]` |
| `fred.stlouisfed.org` | A sourced risk-free rate. Highest leverage on the list: a 100bp WACC error moves a DCF fair value by roughly 15% |
| `stockanalysis.com`, `finance.yahoo.com` | A real peer table with EV/EBITDA, and an observed price rather than one derived from market cap over share count |

## If you would rather not widen egress

Download the filings and commit them to the repo, or paste the figures into the
session. The analysis is identical; the finding labels just have to record where
each number came from, which is the point of the taxonomy.
