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
2. **Business structure — changing soon.** May/June 2026 statements show
   PAYE employment (nanny work via NANNYTAX payroll). Christy has now said
   she'll be **self-employed from around September 2026**, earning roughly
   **£5,000–£6,000/month** — a material change. Still needed:
   - What is the self-employed work? (Determines allowable expense
     categories, whether the Trading Allowance is relevant, and whether it's
     continuing nanny/childcare work under self-employed status or something
     different.)
   - Exact start date, and whether the NANNYTAX/PAYE income stops entirely
     or continues alongside the new self-employment for a transition period.
   - Once self-employed, **you will need to register for Self Assessment
     with HMRC** (by 5 October following the tax year you start, per
     `finance/tax_notes.md`) since self-employment income isn't taxed at
     source the way PAYE is. Please confirm you're aware of this — it's not
     automatic.
3. **Are you VAT registered?** Not currently, and £5,000–£6,000/month
   (£60,000–£72,000/year) is under the current VAT registration threshold on
   its own — but confirm once the nature of the self-employed work is known,
   since thresholds and rules can vary.
4. **Bank/account connections.** Two months of HSBC statements (5 May – 4
   Jul 2026) have now been manually uploaded and loaded into
   `finance/income_and_expenses.csv`. Do you want to keep sending statements
   manually each month, or set up open banking for this going forward?
5. **Historical data — partially resolved.** May and June 2026 are now
   loaded from real statements (147 transactions). Still missing: anything
   before May 2026, and July 2026 is only 3 days' worth (statement cuts off
   4 Jul) — the rest of July needs the next statement.
6. **Income sources — currently PAYE, changing to self-employed ~Sept
   2026.** Current data shows one stream: ~£4,202/month via NANNYTAX (PAYE).
   From September, expect £5,000–£6,000/month self-employed instead — a
   wider, less predictable range than the current fixed salary. For budget
   planning I've used the conservative end (£5,000) as the baseline — see
   item 2 above and `finance/budget.csv`.
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
10. **Mortgage starting ~September 2026, £1,295/month.** Added as a fixed
    cost in the September projected budget. Please confirm: exact start
    date, and whether £1,295 is the full monthly payment (capital +
    interest) or interest-only, since that affects how it's tracked.
11. **Self-employed tax set-aside — needs your input, not just mine.** I've
    put a placeholder of 25% of income (~£1,250/month at the £5,000
    baseline) into the September budget to cover Income Tax and Class 2/4
    National Insurance, since self-employment income isn't taxed at source.
    This is a general rule-of-thumb, not a calculation — your actual rate
    depends on total income, any expenses, and existing PAYE income earned
    earlier in the tax year. **Important:** in your first year of Self
    Assessment, HMRC often also asks for a "payment on account" toward the
    following year, meaning your first tax bill can be noticeably bigger
    than 25% of one year's profit. Please get this confirmed by an
    accountant before September if at all possible — this is the single
    biggest financial-planning risk in this transition.

## Resolved

1. **What does the payday cash withdrawal cover?** Christy confirmed most
   cash spending is hair, nails, and beauty appointments at vendors that are
   cash-only. Reflected in `finance/budget.csv` (category renamed from
   generic "Cash Withdrawal" to "Beauty & Hair (cash-only vendors)") and a
   new `finance/cash_spending_log.csv` was created to track each
   withdrawal against the actual vendor/visit going forward, since a bank
   statement alone can't show that detail.
