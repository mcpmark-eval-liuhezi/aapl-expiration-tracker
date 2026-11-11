# Contributing to aapl-expiration-tracker

This repo tracks Apple (AAPL) options expirations weekly for risk meetings.

## Weekly workflow

1. Pull live market data (Yahoo Finance).
2. Create one tracking issue per upcoming expiration, titled `Expiry YYYY-MM-DD`.
3. Add `expirations.md` at the repo root on a new branch and open a PR into `main`.
4. Keep `CONTRIBUTING.md` up to date with the weekly workflow.
5. Bring the PR branch up to date with `main`; then add a minimal `workflow.yml`
   triggerable manually, run it once, note its billable duration, and **delete
   the run's logs** to keep the repo tidy.

## Data source

All market figures come from live data (Yahoo Finance) and are reported exactly as returned.
