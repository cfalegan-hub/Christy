# Christy — Personal Finance Records

Working repository for Christy's bookkeeping, tax readiness, invoicing, and
budget tracking, maintained together with Finley (personal accountant AI
agent). See `CLAUDE.md` for how Finley operates in this repo.

## Contents

- `finance/income_and_expenses.csv` — cash-basis income & expense log
- `finance/invoices.csv` — invoice / receivables tracker
- `finance/budget.csv` — monthly budget vs. actual
- `finance/tax_notes.md` — UK tax-year reference notes (not advice)
- `docs/open-questions.md` — running log of open questions for Christy
- `docs/alerts.md` — proactive-alerts checklist Finley runs against `finance/`
- `docs/reports/` — monthly check-in reports
- `docs/dashboard/index.html` — visual status dashboard (open directly in a
  browser, or double-click the file locally); see below

## Status

All templates are currently placeholders with no real financial data. See
`docs/open-questions.md` for what's needed to populate them with Christy's
actual figures.

## Dashboard

`docs/dashboard/index.html` is a self-contained, static HTML dashboard —
open it in any browser, no server or build step required. It shows income,
expenditure, budget variance, invoice aging, calendar-year and UK-tax-year
report views, general UK tax-relief reference material, and the current
open questions / alerts / template status.

It's a **manually-generated snapshot**, not a live view — every figure
currently reads £0.00 because `finance/` only holds placeholder rows. Ask
Finley to regenerate it after loading real data or answering open
questions, and it'll reflect the real numbers.
