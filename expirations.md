# AAPL Options Expiration Tracker

Weekly tracking repository for Apple (AAPL) options expiration data, populated from live Yahoo Finance data ahead of the risk meeting.

## Company Snapshot (Yahoo Finance)

| Field | Value |
| --- | --- |
| Company | Apple Inc. (AAPL) |
| Infrastructure street address | One Apple Park Way, MS 927-4GC |
| City / State / ZIP | Cupertino, CA 95014, United States |
| Headquarters phone | (408) 996-1010 |
| Website | https://www.apple.com |
| Sector | Technology |
| Industry | Consumer Electronics |
| Current share price (regularMarketPrice / currentPrice) | $355.63 (USD, NasdaqGS, market state: POST) |
| Previous close | $348.51 |
| Day range | $349.325 – $355.90 |
| 52-week range | $243.42 – $355.90 (all-time high $355.38) |
| Market cap | ~$5.168 T |
| Recommendation | Buy (mean 2.22, 40 analyst opinions) |
| Analyst target mean | $344.62 (median $352.50, high $425.00, low $250.00) |

## Available Option Expiration Dates (Yahoo Finance)

Full list currently returned by `get_option_expiration_dates` for AAPL:

| # | Expiration Date |
| --- | --- |
| 1 | 2026-11-11 |
| 2 | 2026-11-13 |
| 3 | 2026-11-16 |
| 4 | 2026-11-18 |
| 5 | 2026-11-20 |
| 6 | 2026-11-27 |
| 7 | 2026-12-04 |
| 8 | 2026-12-11 |
| 9 | 2026-12-18 |
| 10 | 2026-12-24 |
| 11 | 2027-01-15 |
| 12 | 2027-02-19 |
| 13 | 2027-03-19 |
| 14 | 2027-04-16 |
| 15 | 2027-06-17 |
| 16 | 2027-09-17 |
| 17 | 2027-12-17 |
| 18 | 2028-01-21 |
| 19 | 2028-03-17 |
| 20 | 2028-06-16 |
| 21 | 2028-12-15 |
| 22 | 2029-01-19 |

This week's three soonest upcoming expirations (skipping anything earlier than today): **2026-11-11**, **2026-11-13**, and **2026-11-16**.

## Per-Expiration Chain Stats

**Share price used for ATM calculations throughout: $355.63**

### Expiry 2026-11-11

| Metric | Value |
| --- | --- |
| At-the-money strike (closest to $355.63) | **355** |
| Highest open interest call strike | **355** (OI 33,155; contract AAPL261111C00355000) |
| Highest open interest put strike | **347.5** (OI 6,358; contract AAPL261111P00347500) |

### Expiry 2026-11-13

| Metric | Value |
| --- | --- |
| At-the-money strike (closest to $355.63) | **355** |
| Highest open interest call strike | **355** (OI 11,813; contract AAPL261113C00355000) |
| Highest open interest put strike | **265** (OI 10,654; contract AAPL261113P00265000) |

### Expiry 2026-11-16

| Metric | Value |
| --- | --- |
| At-the-money strike (closest to $355.63) | **355** |
| Highest open interest call strike | **355** (OI 5,737; contract AAPL261116C00355000) |
| Highest open interest put strike | **330** (OI 1,537; contract AAPL261116P00330000) |

## Tracking Issues

| Issue | Expiration | Title |
| --- | --- | --- |
| #21 | 2026-11-11 | Expiry 2026-11-11 |
| #22 | 2026-11-13 | Expiry 2026-11-13 |
| #23 | 2026-11-16 | Expiry 2026-11-16 |

Each issue body records the at-the-money strike, highest-open-interest call strike, highest-open-interest put strike, and the share price used ($355.63).

## Notes

- All market figures above are from live Yahoo Finance data (stock info + option chains) retrieved 2026-11-11.
- The ATM strike is the listed strike closest to the $355.63 share price used in this week's review; in all three expirations that strike is 355.
- Open interest leaders were read directly from the option chain responses for each expiration's call and put sides.
- This repository intentionally lives in `mcpmark-eval-liuhezi/aapl-expiration-tracker` (the org account), as the exact name could not be created anew in the personal account (`HeziLiu`) with the current token scope, and `aapl-expiration-tracker` / `aapl-expiration-tracker-2` were both already present in the org.
- A manual `workflow_dispatch` workflow was added to `.github/workflows/` (minimal single-job echo workflow) and triggered once for CI hygiene; run logs were deleted afterward to keep the repo tidy.
- This repository currently has no discussion categories configured yet (checked via `list_discussion_categories`).
