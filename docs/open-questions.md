# Open Questions Log

Running list of things Finley needs from Christy before proceeding
confidently. Newest first. Move items to "Resolved" once answered, with the
answer noted.

## Outstanding

1. **Fiscal year vs. UK tax year mismatch.** Your profile says fiscal year =
   calendar year (Jan–Dec), but the UK Self Assessment tax year runs 6 April
   to 5 April. If you're filing UK Self Assessment, your tax-year reporting
   will need to follow the April–April window regardless of how you track
   things internally. Please confirm: do you want bookkeeping tracked by
   calendar year, tax year, or both? (Assumption for now: tracking by
   calendar year for personal budgeting, but tax-relevant totals will need
   to be re-cut to the Apr–Apr window at tax time.)
2. **Business structure — tentative answer, please confirm.** The May/June
   2026 HSBC statements show no business-type activity — just one recurring
   credit labelled "NANNYTAX" (a nanny payroll bureau) plus ordinary personal
   spending. This reads as **PAYE employment (nanny)**, not self-employment,
   but please confirm your employer/role and whether NANNYTAX is your actual
   payroll provider — this affects which expense rules apply and whether the
   "allowable business expense" and "Trading Allowance" reliefs are even
   relevant (likely not, if you're purely PAYE).
3. **Are you VAT registered?** Given the above, likely not applicable if
   you're a PAYE employee with no separate business — please confirm.
4. **Bank/account connections.** Two months of HSBC statements (5 May – 4
   Jul 2026) have now been manually uploaded and loaded into
   `finance/income_and_expenses.csv`. Do you want to keep sending statements
   manually each month, or set up open banking for this going forward?
5. **Historical data — partially resolved.** May and June 2026 are now
   loaded from real statements (147 transactions). Still missing: anything
   before May 2026, and July 2026 is only 3 days' worth (statement cuts off
   4 Jul) — the rest of July needs the next statement.
6. **Income sources — tentative answer, please confirm.** Only one income
   stream appears in the data: a salary-like credit from "NANNYTAX" of
   ~£4,202/month, consistent almost to the penny both months. No other
   income (freelance, rental, dividends, interest) appears. Please confirm
   this is your only income source and that it's taxed at source via PAYE
   (Nannytax handles PAYE for household employers) — if so, you're likely
   **not** required to file a Self Assessment return unless something else
   applies (e.g. income over £100k, other untaxed income, claiming certain
   reliefs). Worth a quick check with HMRC or an accountant to confirm you
   don't need to file.
7. **Six transactions with unclear merchant names** — I categorised these as
   "Uncertain - Please Confirm" in `finance/income_and_expenses.csv` rather
   than guess: CNBC Civil Applica (£19.00, 20 May — the name suggests a
   court/civil application fee, worth checking this isn't something that
   needs following up), SP Wander Doll (£48.99, 1 Jun), SumUp - Amilcare R
   (£26.38, 15 Jun), LDN East Ltd (£35.00, 15 Jun), SumUp - Ahmed ME4Z
   (£11.00, 23 Jun), Lily's Place Ltd (£26.80, 23 Jun).
8. **EE mobile direct debit appears twice a month** (~£47 and ~£42, both
   labelled EE Limited/EE Ltd) in every month of data — worth confirming
   with EE whether this is two separate lines/contracts or a duplicate
   billing error, since it's ~£90/month on mobile either way.
9. **DVLA payment of £200.00 on 1 July** — likely vehicle tax (VED) renewal,
   but worth confirming it isn't a fine or penalty charge.

## Resolved

_(none yet — items above are evidence-based inferences pending your
confirmation, not closed out)_
