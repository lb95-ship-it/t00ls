# Paycheck Budget

A standalone HTML budgeting tool that syncs to Google Sheets.

## Usage
Download `paycheck-budget.html` and open it locally in any browser.
No server needed — runs entirely from the file.

## Google Sheets sync
The app is hardcoded to sync with a personal Google Sheets backend
via Apps Script. `budget-script.gs` is kept here as a reference copy
of the deployed script.

**Do not share your deployed web app URL publicly** — anyone with it
can read and overwrite your budget state.

## Features
- Spending, Living, and Savings account tracking
- Biweekly paycheck planning with projections
- Per-category budget line items with visibility toggles
- Autosaves to localStorage + Google Sheets on every change
- Snapshot history (one row per period) for analysis
