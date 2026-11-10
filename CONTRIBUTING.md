# Contributing to aapl-expiration-tracker

## Overview

This repository is used to track weekly AAPL (Apple Inc.) options expiration data for risk meetings. All market figures must come from live data sources (e.g., Yahoo Finance) at the time of collection.

## Adding a New Week's Expiration Data

1. Pull the latest expiration dates available for AAPL (e.g., via Yahoo Finance option expiration dates).
2. Take the three soonest upcoming expirations (skipping anything earlier than today).
3. For each of those expirations:
   - Fetch the call and put option chains.
   - Determine the at-the-money strike (closest listed strike to the current share price).
   - Find the call strike with the largest open interest.
   - Find the put strike with the largest open interest.
4. Create a tracking issue titled `Expiry YYYY-MM-DD` with:
   - the expiration date
   - the share price used
   - ATM strike
   - highest-OI call strike
   - highest-OI put strike
5. Create the `expirations.md` file in the repo root on a new branch with all tracking data.
6. Open a pull request into the default branch (`main`).

## Notes

- Report exactly what the source returns; where a number looks odd, do not fabricate a correction.
- Keep the issue numbers and pull request numbers in sync with the week's data.
