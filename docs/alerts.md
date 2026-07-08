# Proactive Alerts — What Finley Watches For

This is the checklist Finley runs through at each check-in (see
`docs/reports/` for the cadence) and whenever new data is added to
`finance/`. It's the "proactive alerts" part of the job — flagging things
before they become a problem, not just answering when asked.

**Assumption:** thresholds below are conservative starting defaults since no
real data or preferences exist yet. Adjust any of them — just say so and
this file gets updated.

## Cash flow

- Flag if projected outgoings in the next 30 days exceed available cash on
  hand (once real transaction data exists).
- Flag any single expense over **£500** that isn't already categorised —
  ask before assuming the category.

## Invoicing & receivables

- Flag any invoice in `finance/invoices.csv` that is **past its due date**
  and still marked unpaid.
- Flag any invoice unpaid **14+ days** past due as needing a chase-up.
- Flag draft invoices sitting unsent for more than **7 days**.

## Budget

- Flag any category in `finance/budget.csv` where actual spend exceeds
  budgeted amount by more than **15%** in a given month.
- Flag categories with no budget set once actual spend appears against
  them.

## Tax readiness

- Flag as Self Assessment deadlines approach (31 Jan online filing,
  31 Jul second payment on account) — see `finance/tax_notes.md` for
  general dates, confirm exact figures with HMRC each year.
- Flag if income appears from a new/unrecognised source, since that may
  change filing obligations.
- Flag anything that looks like it could be miscategorised as a personal
  vs. allowable expense — default to treating it as personal/non-allowable
  until confirmed, per the conservative-interpretation rule in `CLAUDE.md`.

## Data integrity / potential errors

- Flag duplicate-looking transactions (same date, amount, and near-identical
  description).
- Flag any transaction or invoice missing a required field.
- Flag anything that looks like it could indicate an error or
  non-compliance — surfaced directly, not smoothed over, per `CLAUDE.md`.

## Status

No real data has been loaded yet, so none of these checks have run for
real. This file defines the logic; it will start producing actual alerts
once `finance/` contains real transactions, invoices, and budget figures.
