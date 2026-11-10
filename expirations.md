# AAPL Option Expiration Tracker

Weekly snapshot of Apple (AAPL) option expirations — company profile, available expiration dates, and per-expiration chain statistics for the three soonest upcoming expirations.

**Data source:** Yahoo Finance (live data, pulled for week of 2026-11-10)
**Share price used:** $348.51 (AAPL current price as returned by the source)

## Company Snapshot

| Field | Value |
|---|---|
| Ticker | AAPL |
| Headquarters street address | One Apple Park Way (MS 927-4GC) |
| City | Cupertino |
| State / ZIP / Country | CA 95014, United States |
| Sector | Technology |
| Industry | Consumer Electronics |
| Current share price | $348.51 |

## Available Option Expiration Dates

As returned by the source (22 dates):

1. 2026-11-11
2. 2026-11-13
3. 2026-11-16
4. 2026-11-18
5. 2026-11-20
6. 2026-11-27
7. 2026-12-04
8. 2026-12-11
9. 2026-12-18
10. 2026-12-24
11. 2027-01-15
12. 2027-02-19
13. 2027-03-19
14. 2027-04-16
15. 2027-06-17
16. 2027-09-17
17. 2027-12-17
18. 2028-01-21
19. 2028-03-17
20. 2028-06-16
21. 2028-12-15
22. 2029-01-19

## Per-Expiration Chain Statistics

The three soonest upcoming expirations (share price used: $348.51):

| Expiration | ATM strike (closest to $348.51) | Call strike w/ largest open interest | Put strike w/ largest open interest |
|---|---|---|---|
| 2026-11-11 | 347.5 | 355 (OI 32,028) | 345 (OI 4,004) |
| 2026-11-13 | 347.5 | 365 (OI 10,656) | 265 (OI 10,657) |
| 2026-11-16 | 347.5 | 355 (OI 5,171) | 340 (OI 1,025) |

### Data notes (reported exactly as the source returned)

1. **ATM strike = 347.5** on all three expirations: it is the nearest listed strike to the $348.51 share price (neighbors 345.0 and 350.0).
2. **2026-11-13 put side oddity:** the highest open interest put strike returned by the source is 265, which is deep out-of-the-money (the chain's put strikes run from 110 up to 415). The source returned open interest of 10,657 for AAPL261113P00265000 — this is reported exactly as returned rather than re-interpreted.
3. **Other figures:** all values above are exactly what the source returned for each expiry's call and put chain, with open interest quoted alongside each strike.

## Tracking Issues

- #6 — Expiry 2026-11-11
- #7 — Expiry 2026-11-13
- #8 — Expiry 2026-11-16
