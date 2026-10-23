# AAPL Option Expiration Tracker

Weekly snapshot of Apple (AAPL) option expirations — company profile, available expiration dates, and per-expiration chain statistics for the three soonest upcoming expirations.

**Data source:** Yahoo Finance (live data, pulled 2026-10-22, latest completed session)
**Share price used:** $348.22 (AAPL current price as returned by the source)

## Company Snapshot

| Field | Value |
|---|---|
| Ticker | AAPL |
| Headquarters street address | One Apple Park Way |
| City | Cupertino |
| State / ZIP / Country | CA 95014, United States |
| Sector | Technology |
| Industry | Consumer Electronics |
| Current share price | $348.22 |

## Available Option Expiration Dates

As returned by the source (21 dates, all on or after the 2026-10-22 data date):

1. 2026-10-23
2. 2026-10-26
3. 2026-10-28
4. 2026-10-30
5. 2026-11-06
6. 2026-11-13
7. 2026-11-20
8. 2026-11-27
9. 2026-12-18
10. 2027-01-15
11. 2027-02-19
12. 2027-03-19
13. 2027-04-16
14. 2027-06-17
15. 2027-09-17
16. 2027-12-17
17. 2028-01-21
18. 2028-03-17
19. 2028-06-16
20. 2028-12-15
21. 2029-01-19

## Per-Expiration Chain Statistics

The three soonest upcoming expirations (share price used: $348.22):

| Expiration | ATM strike (closest to $348.22) | Call strike w/ largest open interest | Put strike w/ largest open interest |
|---|---|---|---|
| 2026-10-23 | 310.0 (see note) | none — all strikes tied at 0 OI | none — all strikes tied at 0 OI |
| 2026-10-26 | 347.5 | none — all strikes tied at 0 OI | none — all strikes tied at 0 OI |
| 2026-10-28 | 347.5 | none — all strikes tied at 0 OI | none — all strikes tied at 0 OI |

### Data notes (reported exactly as the source returned)

1. **Open interest is 0 on every contract returned, on both the call and put side, for all three expirations.** Because all strikes report identical open interest of 0, there is no single "largest open interest" strike; every strike ties. No leader is listed above for that reason.
2. **The 2026-10-23 expiration chain response was truncated by the source before reaching the near-money strikes.** The call chain returned strikes only up to 310.0 and the put chain only up to 265.0; no strike in the ~345–350 range was present in the returned data. The ATM strike of 310.0 shown above is simply the closest strike to $348.22 among the strikes the source actually returned for that expiry, and should be treated with caution — it is not a true at-the-money strike.
3. The 2026-10-26 and 2026-10-28 chains included the strikes 345.0, 347.5, and 350.0, making 347.5 the closest strike to the $348.22 share price on both those expirations.

## Tracking Issues

- #1 — Expiry 2026-10-23
- #2 — Expiry 2026-10-26
- #3 — Expiry 2026-10-28
