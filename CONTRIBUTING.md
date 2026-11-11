# Contributing to aapl-expiration-tracker

Thanks for helping keep the weekly AAPL options expiration review accurate and up to date. This repo tracks company snapshot data, option expiration dates, and per-expiration chain stats (ATM strikes, highest open-interest calls/puts) for Apple (AAPL).

## How to contribute

1. **Market data must come from live sources.** All price, strike, volume, and open-interest figures in PRs and issues should be pulled fresh from Yahoo Finance (stock info + option chain for the relevant expiration). Record the share price used in each issue/commit body.
2. **Create one tracking issue per expiration** (titled `Expiry YYYY-MM-DD`) with: the ATM strike, the highest-open-interest call strike, the highest-open-interest put strike, and the share price used.
3. **Add `expirations.md` on a feature branch**, then open a pull request into `main`. The file should bring together: company snapshot, the full list of expiration dates, and a per-expiration stats table.
4. **Keep PRs small and focused** — one stat set per expiration per PR is fine.
5. **Workflows:** a manual `workflow_dispatch` workflow lives in `.github/workflows/`. Trigger it manually with `workflow_dispatch` and note run duration; delete run logs afterward to keep the repo tidy.

## Repository notes

- This repo lives at `mcpmark-eval-liuhezi/aapl-expiration-tracker` (the org account). The exact name could not be created anew in the personal account (`HeziLiu`) with the current token scope, and both `aapl-expiration-tracker` and `aapl-expiration-tracker-2` were already present in the org, so work continues here.
- Data as of 2026-11-11: AAPL share price $355.63, sector Technology, industry Consumer Electronics, HQ One Apple Park Way, Cupertino, CA.
--expiration dates currently available run from 2026-11-11 out to 2029-01-19.

## Discussion

The repo currently has no discussion categories configured. If the team wants to use GitHub Discussions for weekly standup notes, add a `discussions` category via repository settings.
