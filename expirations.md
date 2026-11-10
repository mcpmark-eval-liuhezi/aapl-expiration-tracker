# AAPL Options Expiration Tracker

Weekly tracking repo for Apple (AAPL) options expiration data, built for risk meetings.
All market figures sourced from live data (Yahoo Finance) at the time this pull request was created.

## Company Snapshot

| Field | Value |
|---|---|
| Company | Apple Inc. |
| Street Address | One Apple Park Way |
| City | Cupertino |
| State | CA |
| Zip | 95014 |
| Country | United States |
| Sector | Technology |
| Industry | Consumer Electronics |
| Current Share Price | $348.51 |

## Available Expiration Dates

All option expiration dates currently available for AAPL:

| # | Expiration Date |
|---|---|
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

## Per-Expiration Statistics

Share price used for ATM determination: **$348.51** (AAPL current price, Yahoo Finance, latest session).

| Expiration Date | ATM Strike | Highest-OI Call Strike | Highest-OI Put Strike |
|---|---|---|---|
| 2026-11-11 | 347.5 | 355 (OI 32,028) | 340 (OI 3,922) |
| 2026-11-13 | 347.5 | 355 (OI 10,645) | 265 (OI 10,657) |
| 2026-11-16 | 347.5 | 355 (OI 5,171) | 330 (OI 770) |

## Notes

- ATM strike is the strike closest to the share price of $348.51 for the given expiry.
- Highest-open-interest (OI) strikes are the call/put strike with the largest OI as returned by the data source.
- Source: Yahoo Finance (live option chain data via the market data provider).
