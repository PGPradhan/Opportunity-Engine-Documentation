# Opportunity Engine — Source-by-source Technical Companion

## Reading and authority

November 13 2026 enterprise requirements establish target functional scope. Configuration files take precedence for rules, followed by prototype source, tests, then written descriptions. The September 22 FDD provides historical/prototype preparation detail; verify differences before implementation.

## Artifact inventory and worksheets

A sheet listed in a generated outputs workbook is a calculated report, not a separately executed formula sheet. XML formula inspection confirms there are no Excel formulas in the generated BU master workbooks. The master reference workbooks contain only tab-title convenience formulas rather than operational scoring equations.

### 20260922 - Opportunity Engine Master - Excel appendix.xlsx

| Sheet | Role in the workflow | Contents / formula status |
|---|---|---|
| 0. Cover | Business-rule or opportunity-type output, from scoring process | 10 XML rows; 0 stored formulas |
| 1.1 Engine tracker | Reference definition / data-source or business rule mapping | 17 XML rows; 1 stored formulas |
| 1.2 Dashboard flags | Reference definition / data-source or business rule mapping | 6 XML rows; 1 stored formulas |
| 2.1 SA sizing normalization | Reference definition / data-source or business rule mapping | 48 XML rows; 1 stored formulas |
| 2.2 Equipment sizing rules | Reference definition / data-source or business rule mapping | 56 XML rows; 1 stored formulas |
| 3.1 Data sources - CMS | Reference definition / data-source or business rule mapping | 10 XML rows; 1 stored formulas |
| 3.2 Data sources - SWT | Reference definition / data-source or business rule mapping | 11 XML rows; 1 stored formulas |
| 3.3 Data sources - AirTemp | Reference definition / data-source or business rule mapping | 10 XML rows; 1 stored formulas |

### Opportunity Engine Master - engine logic sizing and data sourcing.xlsx

| Sheet | Role in the workflow | Contents / formula status |
|---|---|---|
| 0. Cover | Business-rule or opportunity-type output, from scoring process | 10 XML rows; 0 stored formulas |
| 1.1 Engine tracker | Reference definition / data-source or business rule mapping | 21 XML rows; 1 stored formulas |
| 1.2 Dashboard flags | Reference definition / data-source or business rule mapping | 6 XML rows; 1 stored formulas |
| 2.1 PMA sizing normalization | Reference definition / data-source or business rule mapping | 48 XML rows; 1 stored formulas |
| 2.2 Equipment sizing rules | Reference definition / data-source or business rule mapping | 56 XML rows; 1 stored formulas |
| 3.1 Data sources - CMS | Reference definition / data-source or business rule mapping | 10 XML rows; 1 stored formulas |
| 3.2 Data sources - SWT | Reference definition / data-source or business rule mapping | 9 XML rows; 1 stored formulas |
| 3.3 Data sources - AirTemp | Reference definition / data-source or business rule mapping | 10 XML rows; 1 stored formulas |

### OE Requirements Register.xlsx

| Sheet | Role in the workflow | Contents / formula status |
|---|---|---|
| Register | Requirement traceability, acceptance criteria, scope | 249 XML rows; 0 stored formulas |
| About | Register orientation | 6 XML rows; 0 stored formulas |

### CMS_Opportunity_Engine_Lists.xlsx

| Sheet | Role in the workflow | Contents / formula status |
|---|---|---|
| Master Ranked List | Combined scored leads; seller queue and prioritization | 5331 XML rows; 0 stored formulas |
| 1. Soft churn | Business-rule or opportunity-type output, from scoring process | 176 XML rows; 0 stored formulas |
| 2. T&M attach | Business-rule or opportunity-type output, from scoring process | 536 XML rows; 0 stored formulas |
| 3. Project end | Business-rule or opportunity-type output, from scoring process | 9 XML rows; 0 stored formulas |
| 4. Past GC Proj | Business-rule or opportunity-type output, from scoring process | 49 XML rows; 0 stored formulas |
| 5. Past DTO Proj | Business-rule or opportunity-type output, from scoring process | 68 XML rows; 0 stored formulas |
| 6. Exp. warranty | Business-rule or opportunity-type output, from scoring process | 35 XML rows; 0 stored formulas |
| 7. Near EOL | Business-rule or opportunity-type output, from scoring process | 168 XML rows; 0 stored formulas |
| 8. Past EOL | Business-rule or opportunity-type output, from scoring process | 2889 XML rows; 0 stored formulas |
| 9. R-22 | Business-rule or opportunity-type output, from scoring process | 53 XML rows; 0 stored formulas |
| 10. Energy Eff. | Business-rule or opportunity-type output, from scoring process | 8 XML rows; 0 stored formulas |
| 11. Faltering | Business-rule or opportunity-type output, from scoring process | 191 XML rows; 0 stored formulas |
| 12. Electrific. | Business-rule or opportunity-type output, from scoring process | 707 XML rows; 0 stored formulas |
| 13. SA Winback | Business-rule or opportunity-type output, from scoring process | 17 XML rows; 0 stored formulas |
| 14. T&M Winback | Business-rule or opportunity-type output, from scoring process | 438 XML rows; 0 stored formulas |
| Account Flags | Non-dollar alerts and customer indicators | 575 XML rows; 0 stored formulas |
| Run Summary | Engine-run totals, counts and checks | 36 XML rows; 0 stored formulas |

### SWT_Opportunity_Engine_Lists.xlsx

| Sheet | Role in the workflow | Contents / formula status |
|---|---|---|
| Master Ranked List | Combined scored leads; seller queue and prioritization | 4704 XML rows; 0 stored formulas |
| 1. Soft churn | Business-rule or opportunity-type output, from scoring process | 634 XML rows; 0 stored formulas |
| 2. T&M attach | Business-rule or opportunity-type output, from scoring process | 742 XML rows; 0 stored formulas |
| 3. Project end | Business-rule or opportunity-type output, from scoring process | 37 XML rows; 0 stored formulas |
| 4. Past GC Proj | Business-rule or opportunity-type output, from scoring process | 32 XML rows; 0 stored formulas |
| 5. Past DTO Proj | Business-rule or opportunity-type output, from scoring process | 51 XML rows; 0 stored formulas |
| 6. Exp. warranty | Business-rule or opportunity-type output, from scoring process | 61 XML rows; 0 stored formulas |
| 7. Near EOL | Business-rule or opportunity-type output, from scoring process | 186 XML rows; 0 stored formulas |
| 8. Past EOL | Business-rule or opportunity-type output, from scoring process | 1596 XML rows; 0 stored formulas |
| 9. R-22 | Business-rule or opportunity-type output, from scoring process | 16 XML rows; 0 stored formulas |
| 11. Faltering | Business-rule or opportunity-type output, from scoring process | 55 XML rows; 0 stored formulas |
| 12. Electrific. | Business-rule or opportunity-type output, from scoring process | 643 XML rows; 0 stored formulas |
| 13. SA Winback | Business-rule or opportunity-type output, from scoring process | 96 XML rows; 0 stored formulas |
| 14. T&M Winback | Business-rule or opportunity-type output, from scoring process | 567 XML rows; 0 stored formulas |
| Account Flags | Non-dollar alerts and customer indicators | 485 XML rows; 0 stored formulas |
| Run Summary | Engine-run totals, counts and checks | 36 XML rows; 0 stored formulas |

### AirTemp_Opportunity_Engine_Lists.xlsx

| Sheet | Role in the workflow | Contents / formula status |
|---|---|---|
| Master Ranked List | Combined scored leads; seller queue and prioritization | 1860 XML rows; 0 stored formulas |
| 1. Soft churn | Business-rule or opportunity-type output, from scoring process | 502 XML rows; 0 stored formulas |
| 2. T&M attach | Business-rule or opportunity-type output, from scoring process | 453 XML rows; 0 stored formulas |
| 3. Project end | Business-rule or opportunity-type output, from scoring process | 3 XML rows; 0 stored formulas |
| 4. Past GC Proj | Business-rule or opportunity-type output, from scoring process | 4 XML rows; 0 stored formulas |
| 5. Past DTO Proj | Business-rule or opportunity-type output, from scoring process | 46 XML rows; 0 stored formulas |
| 7. Near EOL | Business-rule or opportunity-type output, from scoring process | 25 XML rows; 0 stored formulas |
| 8. Past EOL | Business-rule or opportunity-type output, from scoring process | 119 XML rows; 0 stored formulas |
| 11. Faltering | Business-rule or opportunity-type output, from scoring process | 39 XML rows; 0 stored formulas |
| 12. Electrific. | Business-rule or opportunity-type output, from scoring process | 48 XML rows; 0 stored formulas |
| 13. SA Winback | Business-rule or opportunity-type output, from scoring process | 129 XML rows; 0 stored formulas |
| 14. T&M Winback | Business-rule or opportunity-type output, from scoring process | 502 XML rows; 0 stored formulas |
| Account Flags | Non-dollar alerts and customer indicators | 170 XML rows; 0 stored formulas |
| Run Summary | Engine-run totals, counts and checks | 36 XML rows; 0 stored formulas |

## Exact requirement register (248 rows)

For each row: requirement ID and title; source requirement text; business reason; acceptance criterion; current status; priority; source document and section. Build design ownership is proposed and not an additional source requirement.

### 01 Functional Requirements (110 requirements)

#### HOME-01 — Open on a landing view that puts the user's best opportunities first

- **Requirement:** The system shall open on a landing view that puts the user's best opportunities first.
- **Why:** the tool exists to drive sellers to their best opportunities.
- **Acceptance criterion:** On opening, the first content after the book summary is the user's best opportunities.
- **Source status and priority:** Exists / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-02 — The landing view shall summarize the user's book

- **Requirement:** The landing view shall summarize the user's book: open opportunities (with how many are not yet sized), recurring value per year, one-time value, and how many the user is working.
- **Why:** a one-glance picture of the book.
- **Acceptance criterion:** All four figures appear; recurring and one-time values are never added together.
- **Source status and priority:** Exists / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-03 — The landing view shall offer a short list of the best opportunities the user has not yet...

- **Requirement:** The landing view shall offer a short list of the best opportunities the user has not yet acted on, sized and in the default order.
- **Why:** a short list is actionable; a long one overwhelms.
- **Acceptance criterion:** The list is short enough to read at a glance (the prototype shows six), holds only items with no status, and refills as the user acts.
- **Source status and priority:** Exists / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-04 — The user shall be able to start working an opportunity (which, by default, creates its...

- **Requirement:** The user shall be able to start working an opportunity (which, by default, creates its pipeline record, PIP-01), or open its detail, directly from the landing view.
- **Why:** fast triage.
- **Acceptance criterion:** Both actions are available on each listed opportunity without leaving the landing view.
- **Source status and priority:** Exists / Should
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-05 — The landing view shall show what changed in the user's book since the last refresh

- **Requirement:** The landing view shall show what changed in the user's book since the last refresh: new opportunities, new high-value opportunities, opportunities that no longer trigger, and accounts moved in or out.
- **Why:** change is what users act on.
- **Acceptance criterion:** After a test refresh, each count appears and opens the matching list.
- **Source status and priority:** Partial / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-06 — The landing view shall show service agreements due for renewal in 40, 90 or 120 days,...

- **Requirement:** The landing view shall show service agreements due for renewal in 40, 90 or 120 days, with term end and annual value at risk.
- **Why:** renewals protect revenue already won.
- **Acceptance criterion:** Agreements ending within 120 days appear with these fields.
- **Source status and priority:** Exists / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-07 — The landing view shall show revenue at risk (customers whose spending is falling) apart...

- **Requirement:** The landing view shall show revenue at risk (customers whose spending is falling) apart from opportunities and never add it to opportunity totals.
- **Why:** it is a warning, not a sale.
- **Acceptance criterion:** Revenue-at-risk accounts are listed separately and excluded from every opportunity total.
- **Source status and priority:** Exists / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-08 — The landing view shall show back-burner opportunities whose revisit date has arrived

- **Requirement:** The landing view shall show back-burner opportunities whose revisit date has arrived.
- **Why:** a revisit date is a promise to come back.
- **Acceptance criterion:** An opportunity set to Back burner with today's revisit date appears today.
- **Source status and priority:** Exists / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-09 — The landing view shall show top customers by revenue in the last 12 months and by open...

- **Requirement:** The landing view shall show top customers by revenue in the last 12 months and by open opportunity value, and the book split by opportunity type with count, unsized count and value labeled per year or one-time.
- **Why:** shows where the money is and lets users choose what kind of selling to do this week.
- **Acceptance criterion:** Both customer lists and the type split appear; each item opens the matching account or filtered list.
- **Source status and priority:** Exists / Should
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-10 — A BU manager or executive shall be able to switch the landing view between one person, a...

- **Requirement:** A BU manager or executive shall be able to switch the landing view between one person, a sales team, a manager's group and the whole BU.
- **Why:** managers run the weekly review from the landing view.
- **Acceptance criterion:** Choosing "All" shows BU totals; choosing a name shows that person's view.
- **Source status and priority:** Partial / Must
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### HOME-11 — A seller shall see on the landing view any focus list a manager assigned to them

- **Requirement:** A seller shall see on the landing view any focus list a manager assigned to them.
- **Why:** managers direct effort to specific opportunities.
- **Acceptance criterion:** An assigned focus list appears with progress (items given a status).
- **Source status and priority:** New / Should
- **Source section:** 3.1 Landing View (HOME)
- **Proposed implementation owner:** Application/UI

#### NAV-01 — Offer each role only the functions it may use

- **Requirement:** The system shall offer each role only the functions it may use.
- **Why:** users should not see controls they cannot use.
- **Acceptance criterion:** A seller is never offered sizing assumptions or BU-wide archive, and is offered reassignment only for house accounts when the house book is assigned to them and the BU allows it.
- **Source status and priority:** Exists / Must
- **Source section:** 3.2 Finding Work: Search, Filters and Navigation (NAV)
- **Proposed implementation owner:** Application/UI

#### NAV-02 — Find any account, site, address, equipment model, serial number or opportunity ID from...

- **Requirement:** The system shall find any account, site, address, equipment model, serial number or opportunity ID from part of its text, with results grouped by kind.
- **Why:** users prepare for calls by finding one customer fast.
- **Acceptance criterion:** Typing part of a name or model lists matches within one second, and each result opens directly.
- **Source status and priority:** Partial / Must
- **Source section:** 3.2 Finding Work: Search, Filters and Navigation (NAV)
- **Proposed implementation owner:** Application/UI

#### NAV-03 — Let users narrow every view by BU, account manager (including unassigned), sales team,...

- **Requirement:** The system shall let users narrow every view by BU, account manager (including unassigned), sales team, customer, segment and opportunity type, keep those choices while moving between views, and clear them in one step.
- **Why:** managers review one person or one customer across every page.
- **Acceptance criterion:** Choosing one seller narrows every view to that book until cleared.
- **Source status and priority:** Partial / Must
- **Source section:** 3.2 Finding Work: Search, Filters and Navigation (NAV)
- **Proposed implementation owner:** Application/UI

#### NAV-04 — Any view, with its filters and open item, shall be shareable as a link that reopens the...

- **Requirement:** Any view, with its filters and open item, shall be shareable as a link that reopens the same view for another user who is allowed to see it.
- **Why:** managers share a focus or one opportunity by link, not by file.
- **Acceptance criterion:** A link copied from a filtered view opens the same filters for a second permitted user and shows nothing outside that user's book.
- **Source status and priority:** Partial / Should
- **Source section:** 3.2 Finding Work: Search, Filters and Navigation (NAV)
- **Proposed implementation owner:** Application/UI

#### NAV-05 — Users shall be able to return to where they came from without losing their place

- **Requirement:** Users shall be able to return to where they came from without losing their place.
- **Why:** users move between lists, accounts and detail constantly.
- **Acceptance criterion:** From an opportunity opened from an account, the user returns to the account where they left it.
- **Source status and priority:** Exists / Should
- **Source section:** 3.2 Finding Work: Search, Filters and Navigation (NAV)
- **Proposed implementation owner:** Application/UI

#### NAV-06 — Remember each user's last view, filters and sort order between sessions and devices

- **Requirement:** The system shall remember each user's last view, filters and sort order between sessions and devices.
- **Why:** users pick up where they left off.
- **Acceptance criterion:** A user who signs in on a second device sees the filters they last used.
- **Source status and priority:** New / Could
- **Source section:** 3.2 Finding Work: Search, Filters and Navigation (NAV)
- **Proposed implementation owner:** Application/UI

#### OPP-01 — List every opportunity in the user's book with type, customer and site, value labeled per...

- **Requirement:** The system shall list every opportunity in the user's book with type, customer and site, value labeled per year or one-time, confidence, account manager and status.
- **Why:** the full working list beyond the short list.
- **Acceptance criterion:** Every open opportunity in the book appears with these fields.
- **Source status and priority:** Exists / Must
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-02 — Users shall be able to filter by opportunity type and see each type's count

- **Requirement:** Users shall be able to filter by opportunity type and see each type's count.
- **Why:** sellers sell one kind of work at a time.
- **Acceptance criterion:** Each type shows its count, and choosing it narrows the list.
- **Source status and priority:** Exists / Must
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-03 — Users shall be able to narrow the list by text (customer, site, address or opportunity...

- **Requirement:** Users shall be able to narrow the list by text (customer, site, address or opportunity ID), minimum value, confidence, status, and whether to show opportunities or revenue at risk, in any combination.
- **Why:** these are the filters users are trained on.
- **Acceptance criterion:** Each filter narrows the list and its summary; filters combine.
- **Source status and priority:** Exists / Must
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-04 — Analysts and managers shall be able to open further filters on request

- **Requirement:** Analysts and managers shall be able to open further filters on request: industry, branch, exact opportunity rule, grain (account, site or equipment), sizing status, and display of opportunity IDs and rule names.
- **Why:** finer cuts for the few who need them.
- **Acceptance criterion:** These stay hidden until asked for, and each narrows the list.
- **Source status and priority:** Exists / Could
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-05 — Users shall be able to group the list by customer or by site

- **Requirement:** Users shall be able to group the list by customer or by site.
- **Why:** users plan visits by place.
- **Acceptance criterion:** Grouping shows a header per customer or site with its opportunities.
- **Source status and priority:** Exists / Could
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-06 — Users shall be able to sort by any field in either direction, starting in the configured...

- **Requirement:** Users shall be able to sort by any field in either direction, starting in the configured default order (sized value, largest first).
- **Why:** different questions need different orders.
- **Acceptance criterion:** Every column sorts both ways; the first view uses the default order.
- **Source status and priority:** Exists / Must
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-07 — The list shall show a summary for the current filters

- **Requirement:** The list shall show a summary for the current filters: count, recurring per year, one-time, number not sized, and how many are shown.
- **Why:** users must know what the filters left.
- **Acceptance criterion:** The summary updates with every filter change.
- **Source status and priority:** Exists / Should
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-08 — Mark opportunities that are new since the previous refresh and let users list only new...

- **Requirement:** The system shall mark opportunities that are new since the previous refresh and let users list only new ones or those that no longer trigger.
- **Why:** change is what users act on after a refresh.
- **Acceptance criterion:** New items carry a New tag; the change line opens the list of dropped items. Each no-longer-triggering item states why (condition cleared, customer or equipment changed, data changed, or merged into a current opportunity).
- **Source status and priority:** Exists / Must
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-09 — Users shall be able to select one, several or all filtered opportunities and act on them...

- **Requirement:** Users shall be able to select one, several or all filtered opportunities and act on them together: set a status, export, add to a focus list, or (managers) reassign.
- **Why:** bulk work saves clicks; selection also drives "export selected" (EXP-02).
- **Acceptance criterion:** Selected rows can be acted on in one step; the action reports how many were changed.
- **Source status and priority:** Partial / Must
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-10 — Offer a customer-by-type matrix with per-year and one-time values kept apart, where each...

- **Requirement:** The system shall offer a customer-by-type matrix with per-year and one-time values kept apart, where each customer opens to its sites, a value cutoff hides the long tail (a customer stays when either its per-year or its one-time value reaches the cutoff), and unsized opportunities show as a count, never as dollars.
- **Why:** managers spot concentration at a glance.
- **Acceptance criterion:** Each customer shows value by type; the cutoff updates the totals; unsized items show as counts.
- **Source status and priority:** Exists / Should
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### OPP-11 — The matrix shall show summary figures for the current filters

- **Requirement:** The matrix shall show summary figures for the current filters: open value (per year and one-time), accounts and sites with an opportunity, renewals due, and revenue at risk shown apart. An analyst option shows all 14 opportunity rules as separate columns.
- **Why:** the BU picture, with rule-level detail for analysts.
- **Acceptance criterion:** Figures match the list for the same filters; the option swaps the four type columns for 14 rule columns. No column, total or totals sheet adds per-year and one-time values.
- **Source status and priority:** Exists / Could
- **Source section:** 3.3 Opportunity List and Customer Matrix (OPP)
- **Proposed implementation owner:** Application/UI

#### DET-01 — Show an opportunity's full detail without the user losing their place in the list, and...

- **Requirement:** The system shall show an opportunity's full detail without the user losing their place in the list, and let the user move to the next or previous opportunity in the current list.
- **Why:** working down a list is the common task.
- **Acceptance criterion:** Closing the detail returns to the same place; next and previous follow the current filters and order.
- **Source status and priority:** Exists / Must
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-02 — The detail shall show type, a New tag when new, a plain-language headline, customer and...

- **Requirement:** The detail shall show type, a New tag when new, a plain-language headline, customer and site (or "account level"), value labeled per year or one-time, priority tier with its percentile in the BU, data confidence and likelihood of closing.
- **Why:** users judge an opportunity in seconds.
- **Acceptance criterion:** Every field shows, or a clear "not on file".
- **Source status and priority:** Exists / Must
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-03 — The detail shall explain why the opportunity came up in plain language, with the actual...

- **Requirement:** The detail shall explain why the opportunity came up in plain language, with the actual values that triggered it, and offer a suggested conversation opener for its type.
- **Why:** sellers must be able to explain the lead to a customer.
- **Acceptance criterion:** The explanation names the trigger and its values (for example type, size, age and expected life); each type has an opener.
- **Source status and priority:** Exists / Must
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-04 — The detail shall show equipment facts for equipment opportunities (type, make, model,...

- **Requirement:** The detail shall show equipment facts for equipment opportunities (type, make, model, serial number, age and expected life, capacity, refrigerant, heating type, controls, last service date) and account facts for account-level opportunities.
- **Why:** facts needed on site.
- **Acceptance criterion:** All fields on file appear for an equipment opportunity.
- **Source status and priority:** Exists / Must
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-05 — The detail shall show how its value, confidence, likelihood and priority were reached,...

- **Requirement:** The detail shall show how its value, confidence, likelihood and priority were reached, with the source values behind them, on request.
- **Why:** trust depends on seeing the math, without cluttering the default view.
- **Acceptance criterion:** A user can open the calculation and see inputs and results.
- **Source status and priority:** Exists / Should
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-06 — The detail shall list other opportunities at the same site

- **Requirement:** The detail shall list other opportunities at the same site.
- **Why:** one visit can cover several.
- **Acceptance criterion:** Each listed opportunity opens its own detail.
- **Source status and priority:** Exists / Should
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-07 — The detail shall offer the status controls, a note and, for Back burner, a revisit date...

- **Requirement:** The detail shall offer the status controls, a note and, for Back burner, a revisit date (PUR-01, PUR-02), the pipeline link and stage (PIP-01 to PIP-05), "Correct this information" (COR-01) and, for managers, reassignment of this one opportunity (ASG-03).
- **Why:** decisions are made where the facts are.
- **Acceptance criterion:** Each control appears for the roles allowed to use it.
- **Source status and priority:** Partial / Must
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-08 — The detail shall link to the account briefing and the site summary

- **Requirement:** The detail shall link to the account briefing and the site summary.
- **Why:** users move from lead to account.
- **Acceptance criterion:** Both links open the right record.
- **Source status and priority:** Exists / Should
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### DET-09 — When the opportunity is linked to a pipeline record, the detail shall show the pipeline...

- **Requirement:** When the opportunity is linked to a pipeline record, the detail shall show the pipeline record number, stage and result with a link to open it.
- **Why:** one view of the lead and the deal.
- **Acceptance criterion:** A linked opportunity shows these fields and opens the pipeline record.
- **Source status and priority:** New / Must
- **Source section:** 3.4 Opportunity Detail (DET)
- **Proposed implementation owner:** Application/UI

#### ACT-01 — List accounts with industry, account manager (or "Mixed" when its records have different...

- **Requirement:** The system shall list accounts with industry, account manager (or "Mixed" when its records have different holders), number of sites, revenue in the last 12 months, open opportunities, per-year and one-time value and a flag marker, filterable by name and "only accounts with open opportunities", sortable by any column.
- **Why:** account planning.
- **Acceptance criterion:** Each column shows; Mixed opens the breakdown; filters and sorts combine.
- **Source status and priority:** Exists / Must
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### ACT-02 — Each account shall have a briefing

- **Requirement:** Each account shall have a briefing: customer ID, owner, BU, sites, flags, service agreement coverage, renewals due in 40, 90 or 120 days, revenue at risk, open opportunity (per year and one-time), revenue in the last 12 months, sites with an opportunity, and how many the user is working there.
- **Why:** everything needed before a call.
- **Acceptance criterion:** All items show for any account.
- **Source status and priority:** Exists / Must
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### ACT-03 — The briefing shall show the account's opportunities grouped by site, its sites (address,...

- **Requirement:** The briefing shall show the account's opportunities grouped by site, its sites (address, account manager, agreement on site, repair revenue in the last 12 months, value by type), and its revenue by year and service type with year to date and an annualized run rate.
- **Why:** three views of one account.
- **Acceptance criterion:** All three are available, and revenue history covers every year on file.
- **Source status and priority:** Exists / Should
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### ACT-04 — The briefing shall show the account's installed equipment, filterable by type and age,...

- **Requirement:** The briefing shall show the account's installed equipment, filterable by type and age, with each unit's open opportunities.
- **Why:** sellers plan replacement conversations from the fleet, not one unit at a time.
- **Acceptance criterion:** Every linked unit appears with its key facts and opportunities.
- **Source status and priority:** New / Should
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### ACT-05 — Each site shall have a summary

- **Requirement:** Each site shall have a summary: account, account manager and address; open value, count and agreement coverage; renewals due; opportunities with a quick way to start working each one or archive its equipment; revenue mix for the last 12 months; site details; and flags.
- **Why:** visits are planned by site.
- **Acceptance criterion:** All items show for any site.
- **Source status and priority:** Exists / Should
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### ACT-06 — Account and site flags (alerts that are not sized opportunities) shall show with their...

- **Requirement:** Account and site flags (alerts that are not sized opportunities) shall show with their evidence.
- **Why:** flags explain risk and context.
- **Acceptance criterion:** A flagged account shows a marker in lists and the flag text in its briefing.
- **Source status and priority:** Exists / Should
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### ACT-07 — The briefing shall copy a short call summary of the account and its top opportunities for...

- **Requirement:** The briefing shall copy a short call summary of the account and its top opportunities for the user to paste into notes or email.
- **Why:** call preparation.
- **Acceptance criterion:** The summary lands on the clipboard and contains no other account's data.
- **Source status and priority:** Exists / Could
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### ACT-08 — The briefing shall show the account's assignment history (holder changes with who, when...

- **Requirement:** The briefing shall show the account's assignment history (holder changes with who, when and source).
- **Why:** sellers and managers need to know how an account came to them.
- **Acceptance criterion:** The history lists each change with its source (Opportunity Engine or system of record).
- **Source status and priority:** New / Should
- **Source section:** 3.5 Accounts and Sites (ACT)
- **Proposed implementation owner:** Application/UI

#### PUR-01 — Users shall be able to give any opportunity in their book one status

- **Requirement:** Users shall be able to give any opportunity in their book one status: Working, Back burner or Not a fit. Selecting the current status again clears it. There is no status for the pipeline hand-off: once an opportunity has a pipeline record, the stage and result read back from the pipeline system show beside its status (PIP-05).
- **Why:** users track what they do with each lead; the pipeline system, not a second status, says where the deal stands.
- **Acceptance criterion:** Each status can be set and cleared; only one status at a time; a linked opportunity shows its pipeline stage.
- **Source status and priority:** Partial / Must
- **Source section:** 3.6 Pursuits: Statuses, Notes and Revisit Dates (PUR)
- **Proposed implementation owner:** Application/UI

#### PUR-02 — Users shall be able to add a note to any opportunity with a status, and a revisit date to...

- **Requirement:** Users shall be able to add a note to any opportunity with a status, and a revisit date to a Back burner opportunity.
- **Why:** who they spoke to and when to come back.
- **Acceptance criterion:** Note and date save with the status and appear on every device.
- **Source status and priority:** Partial / Must
- **Source section:** 3.6 Pursuits: Statuses, Notes and Revisit Dates (PUR)
- **Proposed implementation owner:** Application/UI

#### PUR-03 — Protect users from losing work by mistake

- **Requirement:** The system shall protect users from losing work by mistake: confirm before clearing Not a fit, the status of an opportunity linked to a pipeline record, or a status with a note; offer Undo; and keep a cleared note and revisit date for 30 days so setting the status again restores them.
- **Why:** prevents accidental loss.
- **Acceptance criterion:** Undo restores the status; within 30 days, re-setting restores the note and date.
- **Source status and priority:** Exists / Should
- **Source section:** 3.6 Pursuits: Statuses, Notes and Revisit Dates (PUR)
- **Proposed implementation owner:** Application/UI

#### PUR-04 — Revenue-at-risk entries shall not take a status

- **Requirement:** Revenue-at-risk entries shall not take a status.
- **Why:** revenue at risk is awareness, not a lead.
- **Acceptance criterion:** Status controls are absent on revenue-at-risk entries.
- **Source status and priority:** Exists / Should
- **Source section:** 3.6 Pursuits: Statuses, Notes and Revisit Dates (PUR)
- **Proposed implementation owner:** Application/UI

#### PUR-05 — Each user shall have one pursuits list of every opportunity they gave a status, with...

- **Requirement:** Each user shall have one pursuits list of every opportunity they gave a status, with type, customer and site, opportunity ID, value, account manager, status, note, revisit date, and pipeline record and stage (PIP-05), editable in place, filterable by status (all, open, each status, not in the latest data), with totals by status (count, sized count, per year and one-time).
- **Why:** the user's weekly working list and the manager review.
- **Acceptance criterion:** Edits in the list save; totals match the rows for every filter.
- **Source status and priority:** Partial / Must
- **Source section:** 3.6 Pursuits: Statuses, Notes and Revisit Dates (PUR)
- **Proposed implementation owner:** Application/UI

#### PUR-06 — A pursued opportunity that stops appearing in the data shall stay on the pursuits list,...

- **Requirement:** A pursued opportunity that stops appearing in the data shall stay on the pursuits list, labeled "not in the latest data", with its last known details, until the user closes or clears it. One that changed (value, priority, holder or equipment) shall show "changed since you set the status" with old and new values.
- **Why:** a pursuit is the user's commitment, not the data's.
- **Acceptance criterion:** Test refreshes that drop and change pursued items show both labels.
- **Source status and priority:** Partial / Must
- **Source section:** 3.6 Pursuits: Statuses, Notes and Revisit Dates (PUR)
- **Proposed implementation owner:** Application/UI

#### PUR-07 — Show how many opportunities the user is working

- **Requirement:** The system shall show how many opportunities the user is working.
- **Why:** keeps the work visible.
- **Acceptance criterion:** The count updates as statuses change.
- **Source status and priority:** Exists / Could
- **Source section:** 3.6 Pursuits: Statuses, Notes and Revisit Dates (PUR)
- **Proposed implementation owner:** Application/UI

#### PIP-01 — When a user marks an opportunity Working, the system shall automatically create the...

- **Requirement:** When a user marks an opportunity Working, the system shall automatically create the opportunity in the BU's pipeline system (D365 or the Sales Pipeline Tracker), with no extra step, filled in from the Opportunity Engine record: customer, site, type, description of why it came up, estimated value with recurring and one-time values kept apart (mapped by INT-08), owner as set by INT-09 (document 03), source "Opportunity Engine" and the opportunity ID. A BU setting names the status that triggers creation (default Working). Only roles that may create pipeline records (section 2.2) trigger it.
- **Why:** ends double entry, the most common complaint about the prototype.
- **Acceptance criterion:** Marking a test opportunity Working creates one pipeline record with these fields and no further action, and the opportunity shows the link.
- **Source status and priority:** New / Must
- **Source section:** 3.7 Pipeline Hand-off (PIP)
- **Proposed implementation owner:** Integration & workflow

#### PIP-02 — Not create duplicates

- **Requirement:** The system shall not create duplicates. If the opportunity is already linked, no new record is created. If an open pipeline record exists for the same customer and opportunity type, the system links the opportunity to it instead of creating one, and tells the user which record it linked.
- **Why:** duplicates distort the pipeline.
- **Acceptance criterion:** Marking an opportunity Working twice creates one record; with a matching open record in place, the opportunity is linked to it and no record is created.
- **Source status and priority:** New / Must
- **Source section:** 3.7 Pipeline Hand-off (PIP)
- **Proposed implementation owner:** Integration & workflow

#### PIP-03 — The user shall be able to link an opportunity to a pipeline record created outside the...

- **Requirement:** The user shall be able to link an opportunity to a pipeline record created outside the Opportunity Engine, or replace an automatic link with the right record, by searching the pipeline system or entering a record number that the system checks before linking (the search and the check are part of the pipeline integration in document 03).
- **Why:** some deals start in the pipeline system first, and an automatic match can be wrong.
- **Acceptance criterion:** A manual link shows on both records; a number that matches no pipeline record is refused.
- **Source status and priority:** New / Should
- **Source section:** 3.7 Pipeline Hand-off (PIP)
- **Proposed implementation owner:** Integration & workflow

#### PIP-04 — When creating or linking the pipeline record fails, the system shall keep the user's...

- **Requirement:** When creating or linking the pipeline record fails, the system shall keep the user's status, show plainly on the opportunity that the pipeline record was not created and why, retry automatically, and let the user retry at once.
- **Why:** a silent failure loses the lead.
- **Acceptance criterion:** A simulated failure shows the message on the opportunity; when the pipeline system is available again, exactly one record is created and linked.
- **Source status and priority:** New / Must
- **Source section:** 3.7 Pipeline Hand-off (PIP)
- **Proposed implementation owner:** Integration & workflow

#### PIP-05 — The opportunity and the pursuits list shall show each linked opportunity's pipeline...

- **Requirement:** The opportunity and the pursuits list shall show each linked opportunity's pipeline record, stage, value and won or lost result, read back from the pipeline system (INT-04). The read-back stage takes the place of any separate hand-off status.
- **Why:** closes the loop for users and reporting.
- **Acceptance criterion:** A pipeline record moved to a new stage, or marked won, shows the change in the Opportunity Engine by the next day.
- **Source status and priority:** New / Must
- **Source section:** 3.7 Pipeline Hand-off (PIP)
- **Proposed implementation owner:** Integration & workflow

#### PIP-06 — For a BU whose pipeline system is set to "not connected" (INT-06, document 03), marking...

- **Requirement:** For a BU whose pipeline system is set to "not connected" (INT-06, document 03), marking an opportunity Working shall let the user type the pipeline record number, which is saved, shown in place of the read-back stage, and reported until the BU is connected.
- **Why:** every BU can record the hand-off from day one.
- **Acceptance criterion:** In a not-connected BU the typed number is saved, shown and reported; once the BU is connected, the record's stage is read back.
- **Source status and priority:** Partial / Must
- **Source section:** 3.7 Pipeline Hand-off (PIP)
- **Proposed implementation owner:** Integration & workflow

#### ARC-01 — Users shall be able to archive an account, a site or a single asset, with an optional...

- **Requirement:** Users shall be able to archive an account, a site or a single asset, with an optional note, after a confirmation that states the count and value leaving their lists.
- **Why:** removes noise.
- **Acceptance criterion:** The confirmation names the item, its open count and per-year and one-time value.
- **Source status and priority:** Exists / Must
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ARC-02 — An archived item and everything under it shall leave every list, search, filter, export,...

- **Requirement:** An archived item and everything under it shall leave every list, search, filter, export, alert and total for that user, and each affected total shall say what was left out.
- **Why:** archived means gone from view, with no silent change to totals.
- **Acceptance criterion:** An archived account appears in no list; totals show the excluded amount.
- **Source status and priority:** Exists / Must
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ARC-03 — Statuses and notes on archived opportunities shall be kept and restored on unarchive, and...

- **Requirement:** Statuses and notes on archived opportunities shall be kept and restored on unarchive, and an archive can be undone right after it is made.
- **Why:** archiving must not destroy work.
- **Acceptance criterion:** Unarchive restores every status and note; Undo restores the item.
- **Source status and priority:** Exists / Must
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ARC-04 — Users shall have one place to review archived items

- **Requirement:** Users shall have one place to review archived items: who archived each and when, the note, the value then and now, and status, filterable by whose archives and which need review, with unarchive.
- **Why:** archives must stay reviewable.
- **Acceptance criterion:** Every archived item appears with these fields and can be unarchived by a permitted user.
- **Source status and priority:** Exists / Must
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ARC-05 — A BU manager shall be able to archive for the whole BU, hiding the item for every user at...

- **Requirement:** A BU manager shall be able to archive for the whole BU, hiding the item for every user at once. Only a BU manager, or an administrator at the BU's request, can undo it, and sellers see it marked as archived by their manager.
- **Why:** some items are wrong for everyone.
- **Acceptance criterion:** Within one minute, no user in the BU sees the item; a seller cannot unarchive it.
- **Source status and priority:** Partial / Must
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ARC-06 — A BU manager shall be able to see every user's personal archives in the BU.

- **Requirement:** A BU manager shall be able to see every user's personal archives in the BU.
- **Why:** managers check what their people hid.
- **Acceptance criterion:** The team view lists each person's archives with notes.
- **Source status and priority:** Exists / Should
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ARC-07 — After each refresh, an archived asset shall return to view, tagged "New since archived",...

- **Requirement:** After each refresh, an archived asset shall return to view, tagged "New since archived", when a new opportunity type appears on it; an archived site or account shall be flagged for review when a new asset appears under it or its value rises by the configured amount (today 10% and at least $1,000). The user resolves a flag by keeping the archive (new values become the baseline) or unarchiving, and sees how many items need review.
- **Why:** archived items can become real again.
- **Acceptance criterion:** Test refreshes produce each case, its tag or flag, and the review count.
- **Source status and priority:** Exists / Must
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ARC-08 — An archived asset whose identifier changes between refreshes shall stay archived when its...

- **Requirement:** An archived asset whose identifier changes between refreshes shall stay archived when its serial number matches, and an archived item missing from the data shall stay on the archive list by name.
- **Why:** XOi merges change asset IDs; the list must stay readable.
- **Acceptance criterion:** Both test cases behave as stated.
- **Source status and priority:** Exists / Must
- **Source section:** 3.8 Archive (ARC)
- **Proposed implementation owner:** Application/UI

#### ASG-01 — A BU manager shall be able to move an account, with all its opportunities, to another...

- **Requirement:** A BU manager shall be able to move an account, with all its opportunities, to another seller, a sales team or the house book.
- **Why:** ownership changes.
- **Acceptance criterion:** Every opportunity on the account shows the new holder, and the account appears in the new holder's book.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-02 — A BU manager shall be able to move one site, so its present and future opportunities go...

- **Requirement:** A BU manager shall be able to move one site, so its present and future opportunities go to the new holder, without changing the account owner.
- **Why:** large accounts split by site.
- **Acceptance criterion:** The site's opportunities show the new holder; the account shows Mixed; an opportunity found at the site later goes to the new holder.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-03 — A BU manager shall be able to move a single opportunity, leaving the account and its...

- **Requirement:** A BU manager shall be able to move a single opportunity, leaving the account and its other opportunities in place.
- **Why:** exceptions happen.
- **Acceptance criterion:** Only that opportunity changes; the account shows Mixed.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-04 — For account and opportunity moves the system shall ask whether to also update the account...

- **Requirement:** For account and opportunity moves the system shall ask whether to also update the account owner (default yes), and never change the owner on a site move.
- **Why:** the account manager decides whose book it is in; the owner is the owner of record.
- **Acceptance criterion:** The option shows, defaulting on, for account and opportunity moves and is absent on site moves.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-05 — A move can be limited to records held by a named person, so other holders' records stay...

- **Requirement:** A move can be limited to records held by a named person, so other holders' records stay put.
- **Why:** partial moves of shared accounts.
- **Acceptance criterion:** With the limit set, only that person's records move.
- **Source status and priority:** Exists / Should
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-06 — Guide the move of a departing seller's whole book, everything to one person or split...

- **Requirement:** The system shall guide the move of a departing seller's whole book, everything to one person or split account by account, with each person's book before and after.
- **Why:** departures are the most common large move.
- **Acceptance criterion:** The guide lists the departing person's accounts and shows before and after books.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-07 — A BU manager shall be able to move many accounts together in one reviewed change,...

- **Requirement:** A BU manager shall be able to move many accounts together in one reviewed change, choosing them inside the application: by selection (by search, by holder, or all in the view), by a list of account IDs entered or pasted, or by a rule over account fields (for example every account one person holds in one state).
- **Why:** territory changes, departures and new hires move many accounts at once.
- **Acceptance criterion:** A rule or list that matches 50 accounts moves them in one reviewed change; list entries that match no account are listed, not dropped.
- **Source status and priority:** Partial / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-08 — Destinations shall be every current seller, every sales team, house, and a new person...

- **Requirement:** Destinations shall be every current seller, every sales team, house, and a new person chosen from the company directory (choosing from the company directory is new). A typed name that nearly matches an existing one shall be refused or warned.
- **Why:** a misspelled name creates a phantom person.
- **Acceptance criterion:** A name that differs only by capitals, spaces or punctuation is refused; a close name warns.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-09 — People who have left the company shall be tagged in destination lists, listed last, and...

- **Requirement:** People who have left the company shall be tagged in destination lists, listed last, and require a deliberate confirmation.
- **Why:** prevents moving work to a leaver.
- **Acceptance criterion:** A leaver appears last and tagged; choosing them asks for confirmation.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-10 — Every move shall show a review before it applies

- **Requirement:** Every move shall show a review before it applies: from, to, what it is limited to, BUs affected, owner update, and the count of accounts, opportunities and value moving.
- **Why:** moves are consequential.
- **Acceptance criterion:** Nothing changes until confirmed; summary counts match the result.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-11 — A confirmed move shall take effect at once for every user

- **Requirement:** A confirmed move shall take effect at once for every user: the new holder sees the work and the old holder no longer does. The move is recorded (who, when, from, to) and written back to the BU's system of record according to the BU's sync mode (INT-10 to INT-16, document 03). The new holder is notified.
- **Why:** sellers must work from the current assignment, not one that waits for a central step.
- **Acceptance criterion:** Within one minute of confirmation the new holder sees the accounts and the old holder does not; the move appears in the assignment history with its write-back result.
- **Source status and priority:** New / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-12 — Every move shall be kept and re-applied, in order, to every refresh, with the latest move...

- **Requirement:** Every move shall be kept and re-applied, in order, to every refresh, with the latest move winning, until the system of record carries the same assignment.
- **Why:** moves must survive new data.
- **Acceptance criterion:** After a refresh every moved account is still with its new holder.
- **Source status and priority:** Partial / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-13 — Show a history of moves (who, when, what, from, to, source) and let a BU manager reverse...

- **Requirement:** The system shall show a history of moves (who, when, what, from, to, source) and let a BU manager reverse a move.
- **Why:** mistakes must be visible and fixable.
- **Acceptance criterion:** The history lists every move; a reversal restores the prior holder.
- **Source status and priority:** Partial / Should
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-14 — Provide a "Needs an owner" worklist in three groups

- **Requirement:** The system shall provide a "Needs an owner" worklist in three groups: no account manager, held by someone who has left, and accounts placed in two BUs. Each account can be assigned from the list.
- **Why:** one worklist for ownership decisions.
- **Acceptance criterion:** The groups show counts; assignment from the list works.
- **Source status and priority:** Partial / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-15 — A move selection that spans more than one BU shall record each account's move under its...

- **Requirement:** A move selection that spans more than one BU shall record each account's move under its own BU, and archived accounts and sites shall move with their account.
- **Why:** some people hold accounts in two BUs; archived work still has an owner.
- **Acceptance criterion:** A two-BU selection records two moves; a book move includes archived accounts.
- **Source status and priority:** Exists / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-16 — A BU manager shall be able to create a sales team (a name and two or more members),...

- **Requirement:** A BU manager shall be able to create a sales team (a name and two or more members), rename it, change its members and dissolve it, with a review step, effective at once. A person belongs to at most one team per BU. Names the system uses for its own books (the house book) are reserved, and a team name may not match a person's name or differ from another team's name only by capitals, spaces or punctuation.
- **Why:** people who sell together need one shared book.
- **Acceptance criterion:** A new team's members see the shared book within one minute; a renamed team keeps its members and history; a team name that matches a person's name, or another team's name apart from capitals, spaces or punctuation, is refused.
- **Source status and priority:** Partial / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-17 — Accounts assigned to a team shall appear in every member's book, with each record's...

- **Requirement:** Accounts assigned to a team shall appear in every member's book, with each record's holder named, and team members' statuses shall be visible to the whole team.
- **Why:** teams coordinate on the same accounts.
- **Acceptance criterion:** Each member sees the team book and each other's statuses.
- **Source status and priority:** Partial / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### ASG-18 — When the system of record changes an account's manager, the change shall reach the...

- **Requirement:** When the system of record changes an account's manager, the change shall reach the Opportunity Engine at the next sync and appear in the assignment history, unless it conflicts with a newer Opportunity Engine move, in which case the BU manager decides (INT-13).
- **Why:** assignments must agree in both systems.
- **Acceptance criterion:** A test change in the source moves the account in the Opportunity Engine; a conflict appears for decision.
- **Source status and priority:** New / Must
- **Source section:** 3.9 Account Assignment and Sales Teams (ASG)
- **Proposed implementation owner:** Integration & workflow

#### MGR-01 — BU managers and executives shall have a team view

- **Requirement:** BU managers and executives shall have a team view: open value (per year and one-time), accounts with an open opportunity, accounts with no account manager, archived totals left out, and people who left but still hold work.
- **Why:** the weekly team review starts here.
- **Acceptance criterion:** Each figure appears and says what it is filtered to.
- **Source status and priority:** Exists / Must
- **Source section:** 3.10 Team Management and Focus Lists (MGR)
- **Proposed implementation owner:** Application/UI

#### MGR-02 — The team view shall show each person's statuses, notes and revisit dates live, with...

- **Requirement:** The team view shall show each person's statuses, notes and revisit dates live, with counts by status per person and the date of their last activity.
- **Why:** in the prototype a manager sees only their own statuses, so team counts read near zero.
- **Acceptance criterion:** A status set by a seller appears on the manager's view within one minute.
- **Source status and priority:** New / Must
- **Source section:** 3.10 Team Management and Focus Lists (MGR)
- **Proposed implementation owner:** Application/UI

#### MGR-03 — The team view shall let the manager focus on one or more people, hide accounts under a...

- **Requirement:** The team view shall let the manager focus on one or more people, hide accounts under a value cutoff (an account stays when either its per-year or its one-time value reaches the cutoff), search accounts, and sort by type and value.
- **Why:** coaching one person at a time.
- **Acceptance criterion:** Choosing one or more people narrows the view; the cutoff removes smaller accounts.
- **Source status and priority:** Exists / Should
- **Source section:** 3.10 Team Management and Focus Lists (MGR)
- **Proposed implementation owner:** Application/UI

#### MGR-04 — A BU manager shall be able to save a filtered set of opportunities as a named focus list,...

- **Requirement:** A BU manager shall be able to save a filtered set of opportunities as a named focus list, assign it to one or more people with an optional due date, and track progress (statuses set).
- **Why:** a manager's priorities must reach sellers inside the application; the prototype can share a focus list only as an export.
- **Acceptance criterion:** The assignee sees it on the landing view; the manager sees progress.
- **Source status and priority:** New / Should
- **Source section:** 3.10 Team Management and Focus Lists (MGR)
- **Proposed implementation owner:** Application/UI

#### MGR-05 — A BU manager shall be able to propose the BU's equipment rates per size band and...

- **Requirement:** A BU manager shall be able to propose the BU's equipment rates per size band and equipment lives per type, seeing the standard, current and proposed value, with values far from standard flagged (rates under half or over double standard, or a life more than 50% away), and submit for administrator approval. On approval the BU is rescored with them.
- **Why:** managers know local prices; large departures need a second look.
- **Acceptance criterion:** A submitted proposal shows each change and its flag; nothing applies until approved; users can see which values are in use.
- **Source status and priority:** Partial / Should
- **Source section:** 3.10 Team Management and Focus Lists (MGR)
- **Proposed implementation owner:** Application/UI

#### COR-01 — A user shall be able to choose "Correct this information" on an asset, site or account...

- **Requirement:** A user shall be able to choose "Correct this information" on an asset, site or account and change the fields the BU allows (at least: equipment type, make, model, serial number, manufacture year, capacity, refrigerant, heating type, status in service or replaced, and the site the asset belongs to; for sites and accounts: name, address and vertical).
- **Why:** wrong XOi and customer data creates false leads and hides real ones.
- **Acceptance criterion:** Each listed field can be corrected from the record where it appears.
- **Source status and priority:** New / Must
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### COR-02 — Each correction shall record the old value, the new value, a reason chosen from a short...

- **Requirement:** Each correction shall record the old value, the new value, a reason chosen from a short list (for example "Read from nameplate", "Customer confirmed", "Unit replaced", "Wrong site"), an optional note and optional photo, who made it and when.
- **Why:** corrections must be explainable and auditable.
- **Acceptance criterion:** A saved correction shows all items in the record's correction history.
- **Source status and priority:** New / Must
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### COR-03 — A correction shall take effect in the Opportunity Engine for every user from the next...

- **Requirement:** A correction shall take effect in the Opportunity Engine for every user from the next scoring of that BU, and the user shall see when it will take effect. Opportunities created, changed or removed by the correction shall show the correction as the reason.
- **Why:** the user must see the fix work.
- **Acceptance criterion:** After a correction to an asset's capacity, its replacement value changes at the next scoring and cites the correction.
- **Source status and priority:** New / Must
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### COR-04 — Corrections shall persist across every later refresh, and shall win over the source value...

- **Requirement:** Corrections shall persist across every later refresh, and shall win over the source value until the source carries the same value or a person corrects it again (precedence in document 04).
- **Why:** a correction that a refresh undoes is wasted work.
- **Acceptance criterion:** After a refresh with the old source value, the corrected value still applies.
- **Source status and priority:** New / Must
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### COR-05 — Each BU shall choose, by setting, whether a seller's correction applies at once or waits...

- **Requirement:** Each BU shall choose, by setting, whether a seller's correction applies at once or waits for a BU manager's approval. Managers shall have a queue of pending corrections to approve or reject with a reason.
- **Why:** BUs differ in how much review they want.
- **Acceptance criterion:** With approval on, a seller's correction appears as pending until approved.
- **Source status and priority:** New / Should
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### COR-06 — The original source value shall stay visible beside the corrected value, labeled with its...

- **Requirement:** The original source value shall stay visible beside the corrected value, labeled with its source.
- **Why:** the reader can always see what XOi or the ERP itself says.
- **Acceptance criterion:** Detail shows "Corrected: X (source shows Y)".
- **Source status and priority:** New / Must
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### COR-07 — When a user says a unit was replaced, the system shall remove its replacement...

- **Requirement:** When a user says a unit was replaced, the system shall remove its replacement opportunities at the next scoring and invite the user to add the new unit's details.
- **Why:** opportunities on replaced units waste sellers' time.
- **Acceptance criterion:** After marking a unit replaced, its replacement opportunities no longer appear and are listed as no longer triggering.
- **Source status and priority:** New / Must
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### COR-08 — Opportunities that cannot be sized because a value is missing (for example capacity)...

- **Requirement:** Opportunities that cannot be sized because a value is missing (for example capacity) shall offer a quick way to supply the missing value, which is handled as a correction.
- **Why:** thousands of leads are unsized only for lack of one value.
- **Acceptance criterion:** Supplying a capacity on an unsized lead sizes it at the next scoring.
- **Source status and priority:** Partial / Should
- **Source section:** 3.11 Data Corrections (COR)
- **Proposed implementation owner:** Integration & workflow

#### EXP-01 — Users shall be able to export the current opportunity list, matrix, account list, site...

- **Requirement:** Users shall be able to export the current opportunity list, matrix, account list, site list or pursuits list to Excel, including every row that matches the filters, not only those on screen.
- **Why:** users and managers work in Excel.
- **Acceptance criterion:** An export of a 1,000-row filtered list holds 1,000 rows.
- **Source status and priority:** Partial / Must
- **Source section:** 3.12 Exports (EXP)
- **Proposed implementation owner:** Application/UI

#### EXP-02 — Users shall be able to export only the rows they selected (OPP-09), and choose a short...

- **Requirement:** Users shall be able to export only the rows they selected (OPP-09), and choose a short set of columns (the default) or all columns.
- **Why:** users often need a handful of records for a call plan or a customer meeting.
- **Acceptance criterion:** Exporting three selected rows produces a file with those three rows.
- **Source status and priority:** New / Must
- **Source section:** 3.12 Exports (EXP)
- **Proposed implementation owner:** Application/UI

#### EXP-03 — Every export shall carry recurring per-year and one-time values in separate columns, the...

- **Requirement:** Every export shall carry recurring per-year and one-time values in separate columns, the opportunity ID, BU and as-of date, and be named with the view, BU, whose book, whether filtered, and the date.
- **Why:** traceability and no misleading totals.
- **Acceptance criterion:** The file name and columns meet the rule. No column, total or totals sheet adds per-year and one-time values.
- **Source status and priority:** Partial / Must
- **Source section:** 3.12 Exports (EXP)
- **Proposed implementation owner:** Application/UI

#### EXP-04 — Exports shall contain only records the user may see and shall leave out archived items...

- **Requirement:** Exports shall contain only records the user may see and shall leave out archived items unless the user exports the archive list itself.
- **Why:** exports must not leak.
- **Acceptance criterion:** A seller's export contains only their book.
- **Source status and priority:** Exists / Must
- **Source section:** 3.12 Exports (EXP)
- **Proposed implementation owner:** Application/UI

#### EXP-05 — The pursuits export shall include a totals sheet by status

- **Requirement:** The pursuits export shall include a totals sheet by status.
- **Why:** used in the manager review.
- **Acceptance criterion:** The totals sheet matches the screen.
- **Source status and priority:** Exists / Should
- **Source section:** 3.12 Exports (EXP)
- **Proposed implementation owner:** Application/UI

#### EXP-06 — BU managers and administrators shall be able to produce the BU's ranked-list workbook (a...

- **Requirement:** BU managers and administrators shall be able to produce the BU's ranked-list workbook (a master ranked list and one sheet per opportunity rule) and the customer-master opportunity view for any book they may see.
- **Why:** the McKinsey-format outputs some users still expect.
- **Acceptance criterion:** The workbook for a chosen book holds only that book.
- **Source status and priority:** Partial / Could
- **Source section:** 3.12 Exports (EXP)
- **Proposed implementation owner:** Application/UI

#### EXP-07 — Every export shall be recorded as activity (TRK-01 in document 03)

- **Requirement:** Every export shall be recorded as activity (TRK-01 in document 03).
- **Why:** exports carry customer data.
- **Acceptance criterion:** An export produces one activity record with row count.
- **Source status and priority:** New / Must
- **Source section:** 3.12 Exports (EXP)
- **Proposed implementation owner:** Application/UI

#### ALR-01 — Alert a seller when a new opportunity in their book is High priority or above a value...

- **Requirement:** The system shall alert a seller when a new opportunity in their book is High priority or above a value threshold set per BU, and when accounts are moved into their book.
- **Why:** the best new leads must not wait for the user to look.
- **Acceptance criterion:** A new High-priority opportunity and a moved-in account each produce an alert.
- **Source status and priority:** New / Should
- **Source section:** 3.13 Alerts and Summaries (ALR)
- **Proposed implementation owner:** Application/UI

#### ALR-02 — Alert a seller when a High-priority opportunity has had no status for a set number of...

- **Requirement:** The system shall alert a seller when a High-priority opportunity has had no status for a set number of days, and when a Working opportunity has had no update for a set number of days.
- **Why:** aging leads lose value.
- **Acceptance criterion:** With thresholds of 14 and 30 days, test records alert on the right day.
- **Source status and priority:** New / Should
- **Source section:** 3.13 Alerts and Summaries (ALR)
- **Proposed implementation owner:** Application/UI

#### ALR-03 — Keep today's reminders

- **Requirement:** The system shall keep today's reminders: revisits due, renewals due in 40, 90 or 120 days, and archived items to review.
- **Why:** they work today.
- **Acceptance criterion:** Each appears as in the prototype.
- **Source status and priority:** Exists / Must
- **Source section:** 3.13 Alerts and Summaries (ALR)
- **Proposed implementation owner:** Application/UI

#### ALR-04 — Alert BU managers to people who left and still hold work, accounts with no account...

- **Requirement:** The system shall alert BU managers to people who left and still hold work, accounts with no account manager, people with no activity for a set number of days, pending corrections and assignment conflicts with the system of record.
- **Why:** managers act on gaps in coverage.
- **Acceptance criterion:** Each condition produces an alert.
- **Source status and priority:** Partial / Should
- **Source section:** 3.13 Alerts and Summaries (ALR)
- **Proposed implementation owner:** Application/UI

#### ALR-05 — An optional weekly email or Microsoft Teams digest shall carry counts and a link only,...

- **Requirement:** An optional weekly email or Microsoft Teams digest shall carry counts and a link only, never customer names or values. It is off by default and turned on per BU.
- **Why:** pulls users back without putting customer data in email.
- **Acceptance criterion:** A test digest holds counts and one link.
- **Source status and priority:** New / Could
- **Source section:** 3.13 Alerts and Summaries (ALR)
- **Proposed implementation owner:** Application/UI

#### ALR-06 — Users shall be able to choose which alerts they receive and how often

- **Requirement:** Users shall be able to choose which alerts they receive and how often; each digest is capped at a set number of items with a link to the full list.
- **Why:** never overwhelming.
- **Acceptance criterion:** A user who turns an alert off stops receiving it.
- **Source status and priority:** New / Should
- **Source section:** 3.13 Alerts and Summaries (ALR)
- **Proposed implementation owner:** Application/UI

### 02 User Experience and Embedded Help Requirements (30 requirements)

#### UX-01 — A seller who has never seen the tool shall be able to find their top opportunity and set...

- **Requirement:** A seller who has never seen the tool shall be able to find their top opportunity and set its status with no training.
- **Why:** intuitive means no training needed for the core job.
- **Acceptance criterion:** In a test with five sellers new to the tool, each does it in under two minutes.
- **Source status and priority:** Partial / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-02 — A seller shall be able to open and act on any opportunity on the landing view in no more...

- **Requirement:** A seller shall be able to open and act on any opportunity on the landing view in no more than two actions.
- **Why:** speed drives use.
- **Acceptance criterion:** Opening an opportunity and setting its status takes two actions or fewer.
- **Source status and priority:** Exists / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-03 — Default views shall show only what is needed to decide the next step

- **Requirement:** Default views shall show only what is needed to decide the next step; calculations, rule-level detail and extra filters open only on request (the three levels in section 2.1).
- **Why:** never overwhelming.
- **Acceptance criterion:** In the UX-14 test, at least four of five sellers rate the default views 4 or 5 on a five-point scale for "easy to see what to do next", and an inspection finds no Level 3 content shown by default.
- **Source status and priority:** Partial / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-04 — Labels shall use plain business language

- **Requirement:** Labels shall use plain business language; rule numbers, field names and technical terms appear only at Level 3.
- **Why:** sellers are not analysts.
- **Acceptance criterion:** No rule number or field name appears on a Level 1 or Level 2 view.
- **Source status and priority:** Exists / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-05 — Every value shall be labeled per year or one-time, and no figure shown to a user shall...

- **Requirement:** Every value shall be labeled per year or one-time, and no figure shown to a user shall add the two together. The prototype adds them on purpose in three places as a size ranking: the Total column of the 14-rule matrix, the combined Opportunity $ column of the downloads, and the Sized $ column of the pursuit list workbook's totals sheet. The downloads and the totals sheet also carry the two values in separate columns. The enterprise version may keep such a ranking only as a separate column labeled "size ranking only", never as a total.
- **Why:** adding them misleads.
- **Acceptance criterion:** No screen or report total sums the two kinds; any combined column is labeled as a ranking.
- **Source status and priority:** Partial / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-06 — Every total shall say what it leaves out (archived items, leads covered by another lead,...

- **Requirement:** Every total shall say what it leaves out (archived items, leads covered by another lead, unsized counts, revenue at risk).
- **Why:** totals must reconcile in the user's head.
- **Acceptance criterion:** Each total with exclusions shows them on the same view.
- **Source status and priority:** Exists / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-07 — The same thing shall be named the same way everywhere (opportunity types, statuses,...

- **Requirement:** The same thing shall be named the same way everywhere (opportunity types, statuses, roles), using the glossary in HLP-05.
- **Why:** consistency builds trust.
- **Acceptance criterion:** A terminology review finds no conflicting labels.
- **Source status and priority:** Partial / Should
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-08 — Consequential actions (moves, BU-wide archives, clearing a closed status, rejecting a...

- **Requirement:** Consequential actions (moves, BU-wide archives, clearing a closed status, rejecting a correction) shall ask for confirmation with a plain summary of the effect; quick reversible actions shall offer Undo instead.
- **Why:** safety without friction.
- **Acceptance criterion:** Each listed action has its confirmation or Undo.
- **Source status and priority:** Partial / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-09 — Every save shall be confirmed quietly, and a failed save shall be stated plainly with a...

- **Requirement:** Every save shall be confirmed quietly, and a failed save shall be stated plainly with a way to retry. No change is ever lost silently.
- **Why:** users must be able to trust that what they record is kept.
- **Acceptance criterion:** With the connection cut, the user is told the change is not saved; when it returns, it saves or the user retries.
- **Source status and priority:** Partial / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-10 — An empty list shall say why it is empty and what to do (for example "No open...

- **Requirement:** An empty list shall say why it is empty and what to do (for example "No open opportunities for this account").
- **Why:** blank screens read as errors.
- **Acceptance criterion:** Every list that can be empty explains itself.
- **Source status and priority:** Exists / Should
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-11 — Warn before the user leaves a view or closes the application with unsaved edits

- **Requirement:** The system shall warn before the user leaves a view or closes the application with unsaved edits.
- **Why:** prevents lost edits.
- **Acceptance criterion:** Leaving a view or closing the application with unsaved edits asks first.
- **Source status and priority:** Partial / Should
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-12 — The landing view, filter changes, search and opening a detail shall respond without...

- **Requirement:** The landing view, filter changes, search and opening a detail shall respond without noticeable delay for the largest BU book (about 9,600 opportunities in General, counting revenue-at-risk records, measured November 13, 2026; document 05, section 10).
- **Why:** slow tools are not used.
- **Acceptance criterion:** IT proposes measurable targets and states the test conditions: the data volume of the largest BU, 200 concurrent users across all BUs, with the share of them that IT assumes are entering or retrieving data at the same moment (Q21 in document 03), and the devices and network used. The build meets the targets in testing with the largest BU under those conditions. If IT proposes none, the target is 95% of these actions under one second and the landing view under three seconds.
- **Source status and priority:** New / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-13 — The build team shall design the screens, navigation and page structure

- **Requirement:** The build team shall design the screens, navigation and page structure. Where a requirement names a prototype view, the name identifies a function, not a layout to copy.
- **Why:** the prototype proves the functions; a better layout is welcome.
- **Acceptance criterion:** Acceptance testing checks functions, inputs and outputs, not likeness to the prototype.
- **Source status and priority:** New / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-14 — Before release, the build shall pass a usability test of the journeys in section 3.1 with...

- **Requirement:** Before release, the build shall pass a usability test of the journeys in section 3.1 with at least five sellers and three managers from at least two BUs, with no task failure on any journey in section 3.1 and a System Usability Scale score of 75 or higher.
- **Why:** ease of use must be measured, not assumed.
- **Acceptance criterion:** The test report shows the results and the fixes made.
- **Source status and priority:** New / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-15 — Core seller functions (landing view, opportunity detail, account briefing, status and...

- **Requirement:** Core seller functions (landing view, opportunity detail, account briefing, status and note, pipeline link and stage, correction) shall work on a phone with no sideways scrolling.
- **Why:** sellers check the tool between calls and on site.
- **Acceptance criterion:** Each core function is completed on a phone in testing.
- **Source status and priority:** Partial / Should
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-16 — Meet the accessibility standard IT selects (Q13 in document 03), be usable by keyboard...

- **Requirement:** The system shall meet the accessibility standard IT selects (Q13 in document 03), be usable by keyboard and screen reader, and name every control.
- **Why:** accessibility.
- **Acceptance criterion:** An accessibility check finds no failures in core views.
- **Source status and priority:** Partial / Should
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-17 — Follow PremiStar's visual identity (colors, type and logo) and show on every view whose...

- **Requirement:** The system shall follow PremiStar's visual identity (colors, type and logo) and show on every view whose book or which BU is shown and that the content is confidential.
- **Why:** users must know what they are looking at and that it is restricted.
- **Acceptance criterion:** Every view carries the identity, the book or BU in view, and a confidentiality notice.
- **Source status and priority:** Exists / Should
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-18 — Users shall be able to select rows and act on them in bulk (status, export, focus list,...

- **Requirement:** Users shall be able to select rows and act on them in bulk (status, export, focus list, reassign) with a clear count of what is selected.
- **Why:** easy export and bulk work.
- **Acceptance criterion:** Selecting rows shows a count and the allowed actions.
- **Source status and priority:** Partial / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### UX-19 — Correcting information shall be available from wherever the information appears, take no...

- **Requirement:** Correcting information shall be available from wherever the information appears, take no more than three actions for a single field, and show the original value beside the new one.
- **Why:** easy correction is what makes users fix data instead of ignoring it.
- **Acceptance criterion:** A single-field correction takes three actions or fewer in testing.
- **Source status and priority:** New / Must
- **Source section:** 4.1 Simplicity and Ease of Use (UX)
- **Proposed implementation owner:** Application/UI

#### HLP-01 — Help shall be organized by task ("Build this week's list to work", "Prepare for a...

- **Requirement:** Help shall be organized by task ("Build this week's list to work", "Prepare for a customer call or visit", "Move a departing seller's whole book"), grouped by role, and searchable.
- **Why:** users look for help with a job, not a screen.
- **Acceptance criterion:** Every task in the help inventory (section 4.3) has a help entry; a search for a task word finds it.
- **Source status and priority:** Partial / Must
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-02 — Every view shall link to the help tasks done on that view, and help shall open without...

- **Requirement:** Every view shall link to the help tasks done on that view, and help shall open without losing the user's place.
- **Why:** help where the work is.
- **Acceptance criterion:** From any view, the matching tasks are one click away, and closing help returns the user to the same view, record, filters and scroll position.
- **Source status and priority:** Partial / Must
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-03 — Each task shall have short written steps, and each task marked for video in section 4.3...

- **Requirement:** Each task shall have short written steps, and each task marked for video in section 4.3 shall also have a short video (two minutes or less) with captions and a transcript. Videos are recorded once the release's screens are final; Q17 in document 03 must be answered before then.
- **Why:** some people learn by reading, others by watching.
- **Acceptance criterion:** Every task marked for video has both; each video has captions and a transcript.
- **Source status and priority:** Partial / Must
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-04 — Help text and videos shall show only functions the user's role in the BU in view can use

- **Requirement:** Help text and videos shall show only functions the user's role in the BU in view can use; manager tasks are hidden from sellers.
- **Why:** no confusing instructions for controls the user does not have.
- **Acceptance criterion:** A seller sees no manager tasks; a user who is a manager in one BU and a seller in another sees manager tasks only in the first.
- **Source status and priority:** Partial / Should
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-05 — Help shall explain every number in plain language (value per opportunity type, data...

- **Requirement:** Help shall explain every number in plain language (value per opportunity type, data confidence, likelihood of closing, priority, "not sized yet", "covered by a service agreement lead") and include a glossary.
- **Why:** trust in the numbers.
- **Acceptance criterion:** Each figure on the landing view and detail has a help entry reached from the figure.
- **Source status and priority:** Partial / Must
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-06 — Help shall include reference tables generated from the settings in use

- **Requirement:** Help shall include reference tables generated from the settings in use: each opportunity rule's trigger and sizing logic, flag definitions, and the equipment sizing table with rates and lives, including any BU-specific values.
- **Why:** managers and analysts check the rules; tables must never drift from the logic.
- **Acceptance criterion:** After a settings change, the help tables show the new values.
- **Source status and priority:** Partial / Should
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-07 — A first-time user shall be offered a short orientation (under three minutes) covering...

- **Requirement:** A first-time user shall be offered a short orientation (under three minutes) covering their role's main jobs, which they can skip and replay.
- **Why:** a good first session decides adoption.
- **Acceptance criterion:** New users see the offer once; each role's orientation runs under three minutes and covers that role's top jobs in section 3; it can be skipped and replayed from help.
- **Source status and priority:** New / Should
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-08 — Each release shall carry a short "What's new" note in the tool, and the help content...

- **Requirement:** Each release shall carry a short "What's new" note in the tool, and the help content shall be updated in the same release as the function it describes.
- **Why:** stale help misleads.
- **Acceptance criterion:** A release with a changed function ships with updated help; release testing checks it.
- **Source status and priority:** Partial / Must
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-09 — Business administrators shall be able to update help text and replace videos without a...

- **Requirement:** Business administrators shall be able to update help text and replace videos without a software release.
- **Why:** help improves faster than software.
- **Acceptance criterion:** An administrator edits a help entry and users see it the same day.
- **Source status and priority:** New / Should
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### HLP-10 — In addition to help opened (TRK-03 in document 03), the system shall record help searches...

- **Requirement:** In addition to help opened (TRK-03 in document 03), the system shall record help searches that found nothing and helpful or not-helpful ratings.
- **Why:** shows where the product or the help is unclear.
- **Acceptance criterion:** Searches with no result and ratings appear in the adoption report (RPT-02 in document 03).
- **Source status and priority:** New / Could
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

#### FBK-01 — Any user shall be able to report something wrong or suggest a feature from any view, with...

- **Requirement:** Any user shall be able to report something wrong or suggest a feature from any view, with the view and record captured automatically, and see the status of their reports. Administrators triage and close reports.
- **Why:** collects user-requested features (item 13 of the IT feature list, document 01, section 4.2) and gives "Report something wrong" a real channel.
- **Acceptance criterion:** A report made from an opportunity carries its ID; the user sees it marked done.
- **Source status and priority:** Partial / Should
- **Source section:** 4.2 Embedded Help (HLP)
- **Proposed implementation owner:** Application/UI

### 03 Enterprise Platform, Integration and Reporting Requirements (94 requirements)

#### ACC-01 — Be one shared, networked application that users open from a link and sign in to once with...

- **Requirement:** The system shall be one shared, networked application that users open from a link and sign in to once with their PremiStar work account, with single sign-on and the company's multi-factor and conditional-access rules. There is nothing to download, install or keep, and no separate password.
- **Why:** every user works in the same application on the same live data.
- **Acceptance criterion:** A user with a PremiStar account opens the application from a link with no download and no separate password.
- **Source status and priority:** New / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-02 — Enforce each user's role and book (document 01, section 2) on the server for every request

- **Requirement:** The system shall enforce each user's role and book (document 01, section 2) on the server for every request: every page, search, link, export, alert, digest, report and integration call returns only what that user's role may see in that BU.
- **Why:** the book is commercially sensitive. The prototype's rules for which records belong to each book can be reused; enforcing them on the server for every request is new.
- **Acceptance criterion:** A seller cannot reach another book's record by search, shared link, export or direct request; automated tests prove it for every role.
- **Source status and priority:** Partial / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-03 — An administrator shall be able to grant, change and revoke a user's role, BU and book,...

- **Requirement:** An administrator shall be able to grant, change and revoke a user's role, BU and book, effective at the user's next action. A person who leaves the company loses access automatically when their work account is disabled.
- **Why:** access must follow the person's job and end when they leave.
- **Acceptance criterion:** After revocation the user cannot open any data; after a book change the next page load shows the new book.
- **Source status and priority:** Partial / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-04 — A seller's book shall follow the account-manager assignments (document 01, section 3.9)...

- **Requirement:** A seller's book shall follow the account-manager assignments (document 01, section 3.9) with no manual step beyond granting access, and shall include the books of any sales team they belong to.
- **Why:** books follow ownership.
- **Acceptance criterion:** A person newly assigned accounts sees them within one minute of the assignment.
- **Source status and priority:** Partial / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-05 — Roles shall be granted through company directory groups where possible, so joining the...

- **Requirement:** Roles shall be granted through company directory groups where possible, so joining the BU's manager group grants the BU manager role.
- **Why:** access follows the organization without a ticket per person.
- **Acceptance criterion:** Adding a test user to a configured group grants the role at next sign-in.
- **Source status and priority:** New / Should
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-06 — One sign-in shall give a user every role they hold

- **Requirement:** One sign-in shall give a user every role they hold. A person may hold different roles in different BUs (for example a seller in one BU and a BU manager in another) and shall see each BU under the role and permissions they hold there.
- **Why:** some people hold accounts in two BUs, or manage one BU and sell in another.
- **Acceptance criterion:** A user who is a seller in one BU and a manager in another sees the right scope in each, in one session.
- **Source status and priority:** Partial / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-07 — Every change a user makes shall be recorded with who, when, what, before and after values...

- **Requirement:** Every change a user makes shall be recorded with who, when, what, before and after values (TRK-01, fields per TRK-02), and an administrator can list every change to a given account.
- **Why:** accountability for assignments, archives, corrections and statuses.
- **Acceptance criterion:** An administrator lists every change to a test account with user, time, old value and new value.
- **Source status and priority:** Partial / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-08 — An administrator shall correct a wrongly recorded event by voiding it with a reason,...

- **Requirement:** An administrator shall correct a wrongly recorded event by voiding it with a reason, never by deleting it.
- **Why:** corrections must leave an audit trail.
- **Acceptance criterion:** A voided event drops out of reports and current state and stays visible to administrators.
- **Source status and priority:** Exists / Should
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-09 — A BU shall be able to narrow a manager's scope to a named group of sellers, and roles...

- **Requirement:** A BU shall be able to narrow a manager's scope to a named group of sellers, and roles shall be defined as sets of permissions an administrator can adjust, so a BU that needs a variant (for example a read-only manager) gets it by setting.
- **Why:** BUs organize their sales teams differently.
- **Acceptance criterion:** A manager limited to four sellers sees only those four books.
- **Source status and priority:** New / Should
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-10 — An administrator shall be able to view the tool as a given user sees it, read-only, with...

- **Requirement:** An administrator shall be able to view the tool as a given user sees it, read-only, with the viewing recorded.
- **Why:** support needs to see what the user sees.
- **Acceptance criterion:** The administrator sees the user's book read-only, and the view is logged.
- **Source status and priority:** New / Could
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-11 — Customer data shall be classified and handled under PremiStar's data policies, including...

- **Requirement:** Customer data shall be classified and handled under PremiStar's data policies, including data-loss-prevention rules for exports, digests and integrations.
- **Why:** the book is commercially sensitive.
- **Acceptance criterion:** IT confirms the classification and policies before go-live (Q9).
- **Source status and priority:** New / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### ACC-12 — Service accounts used for integrations shall have the least access needed and named...

- **Requirement:** Service accounts used for integrations shall have the least access needed and named owners, and their use shall be logged.
- **Why:** integrations write into systems of record.
- **Acceptance criterion:** Each integration identity is documented with its rights and owner.
- **Source status and priority:** New / Must
- **Source section:** 3 Security, Roles and Access (ACC)
- **Proposed implementation owner:** Security / platform / operations

#### DAT-01 — Take all inputs directly from the data lake and XOi on each BU's refresh schedule

- **Requirement:** The system shall take all inputs directly from the data lake and XOi on each BU's refresh schedule: customers and sites; invoices (time and materials); service agreements; projects; account managers and owners; XOi installed equipment and jobs; and salesperson employment status (document 05, section 2). No user or administrator handles a file. The only exception is BUV-08 (document 06): for a BU whose tables are not yet current in the data lake, an administrator may load a data set that passes the same validation controls, shown with its as-of date and a notice, until the live source is ready. IT manages the data lake tables and identifies which feed each BU (Q24).
- **Why:** every BU works on current data with no file handling.
- **Acceptance criterion:** For a test BU, a change in a source table appears in the Opportunity Engine at the next scheduled refresh without any manual step.
- **Source status and priority:** New / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-02 — Refresh and rescore each BU automatically on a schedule an administrator sets for that BU...

- **Requirement:** The system shall refresh and rescore each BU automatically on a schedule an administrator sets for that BU (at least daily) and whenever its source data refreshes, and users shall always see the latest scored data.
- **Why:** current data without making each sign-in wait on a full rescore.
- **Acceptance criterion:** A source change appears as rescored opportunities within one business day; the next user to open sees the new as-of date; changing a BU's schedule needs no software release.
- **Source status and priority:** New / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-03 — Show the as-of date and age of the data wherever results are shown, per BU.

- **Requirement:** The system shall show the as-of date and age of the data wherever results are shown, per BU.
- **Why:** users must know how fresh the numbers are.
- **Acceptance criterion:** Each BU shows its as-of date; a BU whose refresh failed shows its last good date and a notice.
- **Source status and priority:** Partial / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-04 — Validate every refresh against the data integrity and reconciliation controls (document...

- **Requirement:** The system shall validate every refresh against the data integrity and reconciliation controls (document 05, section 6) before showing it, and keep showing the previous good data when a refresh fails or is partial.
- **Why:** a bad load must never replace good data on screen.
- **Acceptance criterion:** A refresh that breaks an integrity rule is refused, the old data stays, and administrators are alerted.
- **Source status and priority:** Exists / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-05 — Produce, for each refresh, a reconciliation an administrator can read

- **Requirement:** The system shall produce, for each refresh, a reconciliation an administrator can read: rows in, matched and excluded per source with reasons, and counts and dollars per opportunity rule, plus a comparison with the previous refresh.
- **Why:** numbers must be provably tied to the source.
- **Acceptance criterion:** For each BU refresh an administrator opens a reconciliation with source and engine totals side by side.
- **Source status and priority:** Exists / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-06 — XOi equipment shall come from the live XOi data lake tables on each BU's refresh...

- **Requirement:** XOi equipment shall come from the live XOi data lake tables on each BU's refresh schedule, prepared with the XOi rules in document 04, section 12 (one record per physical asset, model-number decoding, end-of-life test, capacity precedence, customer and account manager linking). IT rebuilds the XOi preparation step as part of release 1, applying these rules to the live XOi data lake tables (Q23, answered).
- **Why:** XOi changes daily; equipment opportunities must follow it.
- **Acceptance criterion:** A unit added in XOi appears at the next refresh with its opportunities; duplicate records of one unit appear once.
- **Source status and priority:** Partial / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-07 — When new XOi data or a user correction shows a unit was replaced or its details changed,...

- **Requirement:** When new XOi data or a user correction shows a unit was replaced or its details changed, the system shall update or remove its opportunities at the next scoring and list them as no longer triggering.
- **Why:** leads on replaced equipment waste sellers' time.
- **Acceptance criterion:** After a test replacement, the old unit's replacement opportunity is gone and listed as no longer triggering.
- **Source status and priority:** Partial / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-08 — Keep every scored refresh and compare it with the previous one, marking each opportunity...

- **Requirement:** The system shall keep every scored refresh and compare it with the previous one, marking each opportunity New, still open or no longer triggering, with the date first seen (document 04, section 9).
- **Why:** change detection and history for reporting.
- **Acceptance criterion:** After a refresh, users see new and dropped counts and can list the dropped ones.
- **Source status and priority:** Exists / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-09 — Take salesperson employment status only from the system of record for salespeople (the...

- **Requirement:** The system shall take salesperson employment status only from the system of record for salespeople (the Sales Pipeline Performance model today), read at each BU refresh before scoring, and show who has left and still holds work.
- **Why:** departures must be acted on; one source avoids conflicting answers.
- **Acceptance criterion:** A person marked inactive appears as "Left the company" with their remaining accounts after the next refresh.
- **Source status and priority:** Exists / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-10 — Match people's names across sources using confirmed name decisions recorded once, and...

- **Requirement:** The system shall match people's names across sources using confirmed name decisions recorded once, and propose (never apply) uncertain matches for an administrator to confirm.
- **Why:** spellings differ across systems; a wrong match moves a book.
- **Acceptance criterion:** A proposed match waits for confirmation; once confirmed it applies at every later refresh.
- **Source status and priority:** Exists / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-11 — Flag accounts placed in two BUs for a BU manager's decision (document 01, ASG-14), and...

- **Requirement:** The system shall flag accounts placed in two BUs for a BU manager's decision (document 01, ASG-14), and list for review every account it cannot place in any BU under the BU placement rules (document 04, section 14), never placing such an account by state, address or account manager.
- **Why:** shared or unplaced accounts otherwise appear in two books or none.
- **Acceptance criterion:** Accounts placed in both BUs appear on the Needs an owner list; a test account with no placement value appears on the review list and in no BU.
- **Source status and priority:** Partial / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-12 — Show each refresh's data gaps and BU data-quality notes (for example revenue after the...

- **Requirement:** The system shall show each refresh's data gaps and BU data-quality notes (for example revenue after the as-of date, projects with no end date) to BU managers and administrators, with a short notice to sellers that notes exist.
- **Why:** known gaps must be visible to the people who judge the numbers.
- **Acceptance criterion:** Each refresh's notes appear in the manager's view.
- **Source status and priority:** Exists / Should
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### DAT-13 — Apply one documented rule, set by the business owner, for which invoices count as T&M...

- **Requirement:** The system shall apply one documented rule, set by the business owner, for which invoices count as T&M revenue (for example invoices on open work orders, agreement billing and no-charge lines) on every BU, and shall report the change in a BU's totals when it moves from today's route to the live route.
- **Why:** today's sources differ (Capstone's T&M in the data lake includes invoices on open work orders that the Platform Export dataset leaves out; document 05), and which invoices count as T&M changes rules 1, 2, 4, 5, 11 and 14.
- **Acceptance criterion:** For each BU's first live refresh, a reconciliation shows T&M totals on both routes and the rule applied.
- **Source status and priority:** New / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### SCO-01 — Apply the opportunity rules, sizing, scoring and flags in document 04 and produce the...

- **Requirement:** The system shall apply the opportunity rules, sizing, scoring and flags in document 04 and produce the same results as the prototype's scoring tool on the same inputs, within differences the business owner signs off.
- **Why:** users are trained on these rules; results must not shift silently.
- **Acceptance criterion:** Proposed parity test (to confirm with the business owner): for CS3, Capstone and CMS, each on a frozen set of inputs for one as-of date, both systems produce the same opportunity IDs and, for each opportunity, the same sizing status, value to the cent and priority tier. Every difference is listed and signed off by the business owner.
- **Source status and priority:** Exists / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### SCO-02 — Business-owned settings (thresholds, weights, tiers, sizing table, lives, flags, default...

- **Requirement:** Business-owned settings (thresholds, weights, tiers, sizing table, lives, flags, default order, alert thresholds) shall be changeable by an administrator without a software release, with every change versioned and every scored opportunity carrying the versions that produced it.
- **Why:** rules change; results must say which rules produced them.
- **Acceptance criterion:** After a settings change, new results carry the new version and history keeps the old one.
- **Source status and priority:** Partial / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### SCO-03 — A settings change shall be previewable before it is applied

- **Requirement:** A settings change shall be previewable before it is applied: the counts and values it would change per BU.
- **Why:** a change to a life or a threshold changes which leads exist, not only their value.
- **Acceptance criterion:** An administrator sees the before-and-after counts before applying.
- **Source status and priority:** New / Should
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### SCO-04 — Each opportunity shall keep the inputs and intermediate values behind its value,...

- **Requirement:** Each opportunity shall keep the inputs and intermediate values behind its value, confidence, likelihood and priority, so the calculation can be shown (DET-05 in document 01) and audited.
- **Why:** trust depends on seeing the math.
- **Acceptance criterion:** Any opportunity's calculation can be displayed with its inputs.
- **Source status and priority:** Exists / Must
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### SCO-05 — Use won and lost results returned from the pipeline to measure each opportunity type's...

- **Requirement:** The system shall use won and lost results returned from the pipeline to measure each opportunity type's close rate and let an administrator update the likelihood settings from them on a schedule.
- **Why:** today's likelihoods come from history; real results should refine them.
- **Acceptance criterion:** An administrator sees measured close rates beside the rates in use and can apply an update.
- **Source status and priority:** New / Could
- **Source section:** 4 Live Data, Refresh and Scoring (DAT, SCO)
- **Proposed implementation owner:** Data & scoring

#### INT-01 — When a user marks an opportunity Working (or the status the BU's setting names, INT-06),...

- **Requirement:** When a user marks an opportunity Working (or the status the BU's setting names, INT-06), the system shall automatically create the opportunity in the BU's pipeline system (D365 or the Sales Pipeline Tracker), with no extra step, filled in with the fields in PIP-01 (document 01) and with the Opportunity Engine ID stored on the pipeline record. If a matching record exists, it links instead (INT-02). Each system's record type and required fields are open (Q19).
- **Why:** no re-keying and no separate hand-off step.
- **Acceptance criterion:** Marking a test opportunity Working creates one pipeline record with all fields populated and the Opportunity Engine ID, with no other user action.
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-02 — Before creating, the system shall check for an existing link and for an open pipeline...

- **Requirement:** Before creating, the system shall check for an existing link and for an open pipeline record for the same customer and opportunity type, and link to that record instead of creating a second one; when more than one open record matches, the user chooses which to link. A user shall also be able to link to a record created outside the Opportunity Engine by searching the BU's pipeline system by customer, record number or name, and the system shall validate a typed record number before linking (PIP-02, PIP-03).
- **Why:** no duplicates.
- **Acceptance criterion:** Marking Working twice, or for an opportunity with a matching open record, creates no second record; a search finds a test record; an invalid record number is refused.
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-03 — The link shall be stored on both sides, shown on the opportunity, and survive later...

- **Requirement:** The link shall be stored on both sides, shown on the opportunity, and survive later refreshes in which the opportunity's value, holder or presence changes, including when the opportunity's ID changes through an asset merge (STA-04), a different rule triggering on the same customer, site or asset, or a BU's move to a new system of record (BUV-04, document 06). The link follows the same identity rules as user choices.
- **Why:** later updates must line up.
- **Acceptance criterion:** After a refresh that changes the value, and after a test ID change, the link is intact.
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-04 — Read back each linked record's stage, value, owner, close date and won or lost result at...

- **Requirement:** The system shall read back each linked record's stage, value, owner, close date and won or lost result at least daily and show them on the opportunity (PIP-05). Once linked, the opportunity shows the read-back pipeline stage in place of a status that only records the hand-off.
- **Why:** closes the loop for users, activity tracking (TRK-01) and reporting (RPT-05).
- **Acceptance criterion:** A record marked won shows as won by the next day.
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-05 — When creating or linking fails, the system shall leave no partial record, keep the user's...

- **Requirement:** When creating or linking fails, the system shall leave no partial record, keep the user's status as set, show on the opportunity that the pipeline record is not yet created and why, and retry automatically. A failure that persists after the set number of retries goes to the administrators' list of failed hand-offs, and the user can retry it.
- **Why:** a silent failure loses the lead.
- **Acceptance criterion:** A simulated failure leaves no partial record and shows on the opportunity; a retry creates the record once the pipeline system is back; a persistent failure appears on the failure list.
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-06 — Each BU shall name by setting its pipeline system (D365, the Sales Pipeline Tracker, or...

- **Requirement:** Each BU shall name by setting its pipeline system (D365, the Sales Pipeline Tracker, or not connected) and the status that triggers creation (default Working). Switching a BU (for example from the Sales Pipeline Tracker to D365) routes new records to the new system and carries existing links over. A BU set to not connected offers the typed record number instead (PIP-06).
- **Why:** BUs move to D365 at different times; retiring the Sales Pipeline Tracker needs no change here.
- **Acceptance criterion:** A test switch routes new records to D365 and old links still open; a BU set to not connected offers the typed record number. Each BU's value is confirmed before go-live (BUV-07, document 06).
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-07 — When a user changes a linked opportunity's status to Not a fit, or a pipeline record is...

- **Requirement:** When a user changes a linked opportunity's status to Not a fit, or a pipeline record is closed, each side shall show the other's state, without either side closing the other automatically.
- **Why:** the pipeline system owns the deal; the engine owns the lead.
- **Acceptance criterion:** Both states show on both records in testing.
- **Source status and priority:** New / Should
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-08 — Map Opportunity Engine opportunity types to the pipeline system's opportunity types,...

- **Requirement:** The system shall map Opportunity Engine opportunity types to the pipeline system's opportunity types, products or service lines through a setting per pipeline system, and map the per-year and one-time values to the record's amount fields without adding them together (Q19).
- **Why:** the pipeline systems classify deals differently, and the two kinds of value are never added.
- **Acceptance criterion:** Each opportunity type maps to a valid pipeline value for each system; a test record carries both values with no combined total.
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-09 — A pipeline record created when a seller marks an opportunity Working shall be owned by...

- **Requirement:** A pipeline record created when a seller marks an opportunity Working shall be owned by that seller in the pipeline system; one created by a manager's action is owned by the account's current holder unless the manager chooses another owner.
- **Why:** pipeline credit follows the seller.
- **Acceptance criterion:** The pipeline record's owner matches the rule in testing.
- **Source status and priority:** New / Must
- **Source section:** 5.1 Pipeline Systems (Sales Pipeline Tracker and D365)
- **Proposed implementation owner:** Integration & workflow

#### INT-10 — Each BU shall have a setting naming its system of record for account assignment and how...

- **Requirement:** Each BU shall have a setting naming its system of record for account assignment and how far synchronization goes: two-way, read only (the source can be read but not written), or Opportunity Engine as the system of record (no source holds the field).
- **Why:** BUs differ in what their systems hold and allow.
- **Acceptance criterion:** Each live BU has a configured mode, and the mode controls the behavior below.
- **Source status and priority:** New / Must
- **Source section:** 5.2 Account Assignment Synchronization (D365 and ERPs)
- **Proposed implementation owner:** Integration & workflow

#### INT-11 — For two-way BUs, a reassignment confirmed in the Opportunity Engine shall take effect at...

- **Requirement:** For two-way BUs, a reassignment confirmed in the Opportunity Engine shall take effect at once for every user and be written, with no further step, to the system of record's account-manager (and, when chosen, owner) field, at the level the source holds it (account or worksite); the write-back result is shown in the assignment history.
- **Why:** one assignment in both systems.
- **Acceptance criterion:** After a move, every user sees the new holder at once and the source shows the new manager within the agreed time; the history shows "written to D365".
- **Source status and priority:** New / Must
- **Source section:** 5.2 Account Assignment Synchronization (D365 and ERPs)
- **Proposed implementation owner:** Integration & workflow

#### INT-12 — For two-way and read-only BUs, a change made in the system of record shall be picked up...

- **Requirement:** For two-way and read-only BUs, a change made in the system of record shall be picked up at the next sync (near real time where the source allows, at least daily) and applied in the Opportunity Engine for every user.
- **Why:** changes made in D365 or the ERP must not be lost.
- **Acceptance criterion:** A test change in the source moves the account in the Opportunity Engine.
- **Source status and priority:** Partial / Must
- **Source section:** 5.2 Account Assignment Synchronization (D365 and ERPs)
- **Proposed implementation owner:** Integration & workflow

#### INT-13 — When the same account changed on both sides since the last sync, the system shall not...

- **Requirement:** When the same account changed on both sides since the last sync, the system shall not overwrite either silently: it keeps the newer change, records both, and puts the conflict on the BU manager's list to confirm.
- **Why:** conflicting edits are a normal part of two systems.
- **Acceptance criterion:** A conflict test shows both values and the chosen one on the manager's list.
- **Source status and priority:** New / Must
- **Source section:** 5.2 Account Assignment Synchronization (D365 and ERPs)
- **Proposed implementation owner:** Integration & workflow

#### INT-14 — For BUs where the Opportunity Engine is the system of record, it shall hold the...

- **Requirement:** For BUs where the Opportunity Engine is the system of record, it shall hold the assignments and publish them to a data lake table that other reports can use, updated after each change. IT owns and grants write access to that table (Q24).
- **Why:** some BUs have no system that holds the account manager.
- **Acceptance criterion:** The published table matches the Opportunity Engine's assignments after each change.
- **Source status and priority:** Partial / Must
- **Source section:** 5.2 Account Assignment Synchronization (D365 and ERPs)
- **Proposed implementation owner:** Integration & workflow

#### INT-15 — A bulk reassignment made in the application (ASG-07, document 01

- **Requirement:** A bulk reassignment made in the application (ASG-07, document 01: accounts selected together, an account list, or a rule) shall be reviewed as one change listing matches, misses and changes, then applied as moves for every user at once and written back to the system of record as one batch under the BU's sync mode, with each row's result.
- **Why:** BUs reassign many accounts at a time.
- **Acceptance criterion:** A bulk move of 100 accounts by account list shows each row's outcome before it applies; unmatched rows are listed, not dropped; the history shows each row's write-back result.
- **Source status and priority:** Partial / Should
- **Source section:** 5.2 Account Assignment Synchronization (D365 and ERPs)
- **Proposed implementation owner:** Integration & workflow

#### INT-16 — Write-back shall respect the source system's rules (valid user IDs, required fields,...

- **Requirement:** Write-back shall respect the source system's rules (valid user IDs, required fields, locked records) and report any row the source refused, without blocking the move in the Opportunity Engine.
- **Why:** a refused write must be visible and fixable.
- **Acceptance criterion:** A refused write appears with its reason on the administrator's list.
- **Source status and priority:** New / Must
- **Source section:** 5.2 Account Assignment Synchronization (D365 and ERPs)
- **Proposed implementation owner:** Integration & workflow

#### INT-17 — Every correction (document 01, COR-01 to COR-08) shall be stored centrally as an...

- **Requirement:** Every correction (document 01, COR-01 to COR-08) shall be stored centrally as an append-only record with the record and field, old value, new value, reason, evidence, who, when, approval state and whether a person or a machine supplied it.
- **Why:** corrections are data with a history; the prototype's XOi corrections ledger already keeps corrections as append-only records with their source and trust.
- **Acceptance criterion:** The corrections store holds every field listed; no record is ever edited in place.
- **Source status and priority:** Partial / Must
- **Source section:** 5.3 Data Corrections Write-Back
- **Proposed implementation owner:** Integration & workflow

#### INT-18 — Approved corrections shall be written to corrections tables in the data lake, keyed to...

- **Requirement:** Approved corrections shall be written to corrections tables in the data lake, keyed to the source record (for example the XOi equipment ID), so the data lake's own pipelines and other reports can use them. IT owns and grants write access to these tables (Q24).
- **Why:** a fix made once should benefit every report that uses the data.
- **Acceptance criterion:** After approval, the correction appears in the data lake table at the next sync.
- **Source status and priority:** New / Must
- **Source section:** 5.3 Data Corrections Write-Back
- **Proposed implementation owner:** Integration & workflow

#### INT-19 — The scoring shall apply approved corrections with the precedence in document 04, section...

- **Requirement:** The scoring shall apply approved corrections with the precedence in document 04, section 11: a person's correction beats the source value and any machine-derived value; a machine value only fills a blank; the source value is kept beside it.
- **Why:** users' fixes must win, but never hide what the source says.
- **Acceptance criterion:** A test correction overrides the source; a machine value does not override a person's.
- **Source status and priority:** Partial / Must
- **Source section:** 5.3 Data Corrections Write-Back
- **Proposed implementation owner:** Integration & workflow

#### INT-20 — When the source later carries the same value, the correction shall be marked "now in...

- **Requirement:** When the source later carries the same value, the correction shall be marked "now in source" and stop overriding; when the source changes to a third value, the conflict shall be shown to the BU manager.
- **Why:** corrections should retire once the source is fixed.
- **Acceptance criterion:** Both test cases behave as stated.
- **Source status and priority:** New / Should
- **Source section:** 5.3 Data Corrections Write-Back
- **Proposed implementation owner:** Integration & workflow

#### INT-21 — Whether corrections are also written back into XOi or the ERP itself is an open question...

- **Requirement:** Whether corrections are also written back into XOi or the ERP itself is an open question for IT (Q16). Until decided, the data lake corrections table is the system's write-back target.
- **Why:** writing into vendor systems may not be possible or allowed.
- **Acceptance criterion:** IT records the decision before release 1 scope is fixed.
- **Source status and priority:** New / Must
- **Source section:** 5.3 Data Corrections Write-Back
- **Proposed implementation owner:** Integration & workflow

#### STA-01 — Every user choice shall be stored in the application's central store against the user and...

- **Requirement:** Every user choice shall be stored in the application's central store against the user and the record: statuses, notes, revisit dates, archives, assignments, teams, focus lists, corrections, sizing proposals and alert settings.
- **Why:** every user sees the same current state on any device, with nothing kept on the device.
- **Acceptance criterion:** A choice made on one computer appears at once on another computer or a phone.
- **Source status and priority:** Partial / Must
- **Source section:** 6 Central State and Continuity (STA)
- **Proposed implementation owner:** Security / platform / operations

#### STA-02 — Every saved choice shall apply at every sign-in and after every refresh

- **Requirement:** Every saved choice shall apply at every sign-in and after every refresh.
- **Why:** choices must never lapse silently.
- **Acceptance criterion:** After a refresh, every status, archive, move and correction made before it still applies.
- **Source status and priority:** Partial / Must
- **Source section:** 6 Central State and Continuity (STA)
- **Proposed implementation owner:** Security / platform / operations

#### STA-03 — When a refreshed record no longer exists, the user's choice shall be kept with the...

- **Requirement:** When a refreshed record no longer exists, the user's choice shall be kept with the record's last known details and marked "not in the latest data".
- **Why:** users must see what happened to their work.
- **Acceptance criterion:** A test refresh that removes a pursued, an archived and a moved record shows each with the label.
- **Source status and priority:** Exists / Must
- **Source section:** 6 Central State and Continuity (STA)
- **Proposed implementation owner:** Security / platform / operations

#### STA-04 — Choices on an asset shall follow it when its identifier changes but its serial number...

- **Requirement:** Choices on an asset shall follow it when its identifier changes but its serial number matches (XOi merges).
- **Why:** source merges change IDs.
- **Acceptance criterion:** A choice survives an ID change with the same serial.
- **Source status and priority:** Exists / Must
- **Source section:** 6 Central State and Continuity (STA)
- **Proposed implementation owner:** Security / platform / operations

#### STA-05 — When the same user works in two windows or on two devices, both shall stay in step, with...

- **Requirement:** When the same user works in two windows or on two devices, both shall stay in step, with the latest change winning.
- **Why:** people move between a computer and a phone during the day.
- **Acceptance criterion:** A status set in one window or device shows in the other on its next action.
- **Source status and priority:** Partial / Should
- **Source section:** 6 Central State and Continuity (STA)
- **Proposed implementation owner:** Security / platform / operations

#### STA-06 — When two users change the same record at nearly the same time (for example two managers...

- **Requirement:** When two users change the same record at nearly the same time (for example two managers moving one account), the second shall be told and shown the first change before theirs applies.
- **Why:** no silent overwrite between people.
- **Acceptance criterion:** A concurrency test shows the warning.
- **Source status and priority:** New / Should
- **Source section:** 6 Central State and Continuity (STA)
- **Proposed implementation owner:** Security / platform / operations

#### TRK-01 — Record in the application's store, with no action by the user, every status change, note,...

- **Requirement:** The system shall record in the application's store, with no action by the user, every status change, note, revisit date, archive, unarchive, review, assignment, team change, focus list, correction, approval, sizing proposal, pipeline hand-off and read-back, export, alert and digest sent.
- **Why:** activity is captured as part of the work, with no separate tracking step.
- **Acceptance criterion:** Each listed action produces one record with the fields in TRK-02.
- **Source status and priority:** Partial / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-02 — Each activity record shall hold who (user, role, BU, team), when, the action, before and...

- **Requirement:** Each activity record shall hold who (user, role, BU, team), when, the action, before and after values, and a snapshot of the record (opportunity ID, type, customer and site, holder, value per year and one-time, priority tier, sizing status, as-of date, whether in the latest data).
- **Why:** reports must stand on their own after the data changes.
- **Acceptance criterion:** A status-change record holds all fields.
- **Source status and priority:** Partial / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-03 — Record use

- **Requirement:** The system shall record use: sign-ins, views opened, opportunity details and account briefings opened, searches run (search text only if policy allows), help opened, and alerts and focus lists opened.
- **Why:** adoption is the first question leadership asks.
- **Acceptance criterion:** A test session produces one record per event type.
- **Source status and priority:** New / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-04 — Keep each BU's book at each refresh (every opportunity with its holder, value and status)...

- **Requirement:** The system shall keep each BU's book at each refresh (every opportunity with its holder, value and status) for reporting, so coverage and change can be measured over time.
- **Why:** the denominator for coverage.
- **Acceptance criterion:** A report can show the book on any past refresh date within retention.
- **Source status and priority:** Partial / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-05 — Book totals shall count each opportunity once, so a BU's coverage is never double counted...

- **Requirement:** Book totals shall count each opportunity once, so a BU's coverage is never double counted across overlapping views (teams, house, managers).
- **Why:** a BU's opportunities appear in overlapping views, which must not count them twice.
- **Acceptance criterion:** Coverage equals opportunities with a status divided by the BU's opportunities, each counted once.
- **Source status and priority:** Exists / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-06 — Activity records shall be unchangeable once written

- **Requirement:** Activity records shall be unchangeable once written; corrections are by void only (ACC-08).
- **Why:** trustworthy history.
- **Acceptance criterion:** No user can edit a recorded event.
- **Source status and priority:** Partial / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-07 — Each role shall see only the activity it may see

- **Requirement:** Each role shall see only the activity it may see: sellers their own, managers their BU or group, executives and administrators all.
- **Why:** activity is as sensitive as the book.
- **Acceptance criterion:** A seller cannot open another person's activity.
- **Source status and priority:** Partial / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-08 — At each BU's go-live the system shall record a baseline

- **Requirement:** At each BU's go-live the system shall record a baseline: the BU's book (every opportunity with its holder and value) and its assignments as taken from the system of record, so every later report measures change from that day. It shall also import the prototype's central activity history (status, reassignment, sizing-assumption, team and archive events) with each event's original author and date, so activity reports reach back before go-live.
- **Why:** reports need a clear starting point for each BU.
- **Acceptance criterion:** On a BU's go-live date a report shows its baseline book, and coverage after go-live is measured against it; imported prototype events appear in activity reports under their original dates, and their counts match the prototype's records.
- **Source status and priority:** New / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### TRK-09 — Activity records shall be kept for 24 months and then deleted, with a named business...

- **Requirement:** Activity records shall be kept for 24 months and then deleted, with a named business owner, unless the business owner changes the period by setting.
- **Why:** agreed retention.
- **Acceptance criterion:** Records older than the period are gone; the owner is named in settings.
- **Source status and priority:** Partial / Must
- **Source section:** 7 Activity Tracking (TRK)
- **Proposed implementation owner:** Integration & workflow

#### RPT-01 — Publish a reporting data set for Power BI and Excel, read from the application's store...

- **Requirement:** The system shall publish a reporting data set for Power BI and Excel, read from the application's store and refreshed at least daily, holding activity (TRK-01 to TRK-03), book snapshots (TRK-04), opportunities, pipeline links and results, corrections, assignments, users and roles, with row-level security matching ACC-02.
- **Why:** leadership reports in Power BI; report authors must not need IT for each question.
- **Acceptance criterion:** A report author builds a report of statuses by BU, seller and type without IT help, and a seller sees only their own rows.
- **Source status and priority:** Partial / Must
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-02 — Adoption report

- **Requirement:** Adoption report: users with access, weekly and monthly active users, first sign-in, last activity, and help usage, by BU, role and person, with trend.
- **Why:** answers "is the tool being used?"
- **Acceptance criterion:** The report shows each measure for a test BU and matches the activity records.
- **Source status and priority:** New / Must
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-03 — Usage and coverage report

- **Requirement:** Usage and coverage report: share of each book given a status, by count and by sized value (recurring and one-time apart), by BU, manager, team, seller and opportunity type; share of High-priority opportunities acted on within a set number of days of first appearing.
- **Why:** answers "are sellers working the best opportunities?"
- **Acceptance criterion:** Figures match the team view for the same date.
- **Source status and priority:** Partial / Must
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-04 — Activity report

- **Requirement:** Activity report: opportunities by status and age of status, revisits due and overdue, archives and their reasons, focus-list progress, and people with no activity in a set number of days.
- **Why:** answers "what is being pursued and what is stalled?"
- **Acceptance criterion:** Each measure appears by BU and person.
- **Source status and priority:** Partial / Must
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-05 — Pipeline and closed sales report

- **Requirement:** Pipeline and closed sales report: opportunities sent to the pipeline, pipeline value created, stage mix, won and lost count and value, win rate and days to close, by BU, seller, opportunity type and month of hand-off; and value won from Opportunity Engine opportunities against each BU's total bookings, taken from Planful, the source of truth for bookings, as finalized each month after close (Q18).
- **Why:** answers "what revenue did the engine produce?"
- **Acceptance criterion:** Won value in the report ties to the pipeline system's won records linked to the Opportunity Engine.
- **Source status and priority:** New / Must
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-06 — Ownership report

- **Requirement:** Ownership report: accounts with no account manager, held by people who left, placed in two BUs, and assignment changes by source (Opportunity Engine or system of record), with write-back failures.
- **Why:** coverage depends on ownership.
- **Acceptance criterion:** Counts match the Needs an owner list.
- **Source status and priority:** New / Should
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-07 — Data quality report

- **Requirement:** Data quality report: corrections by type, BU and person; unsized opportunities by reason; refresh results and reconciliation exceptions by BU.
- **Why:** shows where data needs fixing at the source.
- **Acceptance criterion:** Each measure appears by BU.
- **Source status and priority:** New / Should
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-08 — Opportunity book report

- **Requirement:** Opportunity book report: opportunities and value by BU, type, priority tier and segment, with new and no-longer-triggering counts by refresh.
- **Why:** the BU picture over time.
- **Acceptance criterion:** Figures match the application for the same refresh.
- **Source status and priority:** Partial / Should
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-09 — Reports shall be available to each role at the scope it may see

- **Requirement:** Reports shall be available to each role at the scope it may see. Each BU manager shall get a weekly summary of their BU's measures as a report in the application or a scheduled report that links to it, with no file to open or forward.
- **Why:** managers act on these weekly.
- **Acceptance criterion:** A BU manager opens their BU's reports and receives the weekly summary.
- **Source status and priority:** Partial / Should
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### RPT-10 — Every report measure shall be defined once, in writing, with its formula and source, and...

- **Requirement:** Every report measure shall be defined once, in writing, with its formula and source, and shown in the report's help.
- **Why:** one definition per measure avoids conflicting numbers.
- **Acceptance criterion:** Each measure has a definition reachable from the report.
- **Source status and priority:** New / Should
- **Source section:** 8 Reporting in Power BI (RPT)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-01 — Keep an immutable copy of every input set used for a scoring run (every source extract...

- **Requirement:** The system shall keep an immutable copy of every input set used for a scoring run (every source extract and the settings versions), so any run within the input-snapshot retention period (BCK-08) can be reproduced exactly.
- **Why:** numbers must be provable later; the prototype keeps input snapshots for some BUs today.
- **Acceptance criterion:** Re-running a past scoring within the retention period from its stored inputs reproduces its results lead for lead.
- **Source status and priority:** Partial / Must
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-02 — Back up all central state (statuses, notes, assignments, teams, archives, corrections,...

- **Requirement:** The system shall back up all central state (statuses, notes, assignments, teams, archives, corrections, focus lists, settings, activity records) on a schedule that meets the recovery point objective IT sets with the business owner (Q22).
- **Why:** months of user work must survive any failure.
- **Acceptance criterion:** IT documents the schedule and target; a restore test meets it.
- **Source status and priority:** New / Must
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-03 — Backups shall be stored apart from the production system (another location or account),...

- **Requirement:** Backups shall be stored apart from the production system (another location or account), protected from deletion or change for their retention period.
- **Why:** a backup that the same failure can destroy is not a backup.
- **Acceptance criterion:** IT documents the location and protection.
- **Source status and priority:** New / Must
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-04 — Be restorable to a working state within the recovery time objective IT sets with the...

- **Requirement:** The system shall be restorable to a working state within the recovery time objective IT sets with the business owner (Q22), and restoring the application shall not lose any user choice made before the recovery point.
- **Why:** sellers depend on the tool weekly.
- **Acceptance criterion:** A disaster recovery test restores service within the target.
- **Source status and priority:** New / Must
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-05 — Administrators shall be able to restore a single BU's state or a single record's history...

- **Requirement:** Administrators shall be able to restore a single BU's state or a single record's history to a point in time without restoring the whole system.
- **Why:** most incidents are local (a bad bulk move, a wrong settings change).
- **Acceptance criterion:** A test restores one BU's assignments to yesterday while other BUs are untouched.
- **Source status and priority:** New / Should
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-06 — Bulk changes (bulk moves, bulk status changes, settings changes) shall be reversible in...

- **Requirement:** Bulk changes (bulk moves, bulk status changes, settings changes) shall be reversible in one action for a set period.
- **Why:** the fastest recovery is an undo.
- **Acceptance criterion:** A bulk move of 100 accounts is reversed in one action.
- **Source status and priority:** New / Should
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-07 — Backup and restore shall be tested at least twice a year and after major changes, with...

- **Requirement:** Backup and restore shall be tested at least twice a year and after major changes, with results recorded.
- **Why:** an untested backup is not a recovery plan.
- **Acceptance criterion:** Test records exist for each period.
- **Source status and priority:** New / Must
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### BCK-08 — Retention periods shall be settings

- **Requirement:** Retention periods shall be settings: input snapshots (proposed 36 months), scored refreshes (proposed 36 months), activity records (24 months, TRK-09), corrections and assignments (life of the record).
- **Why:** different data has different value over time.
- **Acceptance criterion:** Each period is visible in settings and enforced.
- **Source status and priority:** New / Should
- **Source section:** 9 Backup, Retention and Disaster Recovery (BCK)
- **Proposed implementation owner:** Security / platform / operations

#### ADM-01 — Administrators shall see, per BU, the last refresh of each source, its result, counts...

- **Requirement:** Administrators shall see, per BU, the last refresh of each source, its result, counts against the previous refresh and any failure, and be alerted when a refresh fails or a source is late.
- **Why:** problems must be caught before users notice.
- **Acceptance criterion:** A failed test refresh alerts administrators with the reason.
- **Source status and priority:** Partial / Must
- **Source section:** 10 Administration and Operations (ADM)
- **Proposed implementation owner:** Security / platform / operations

#### ADM-02 — Administrators shall onboard a new BU by configuration alone, completing the 15-step...

- **Requirement:** Administrators shall onboard a new BU by configuration alone, completing the 15-step onboarding checklist in document 06, section 5, which is the list this requirement and BUV-01 share. Among other things it sets source mappings, ID system, house placeholder values, BU placement values where one company holds several BUs (document 04, section 14), refresh schedule, account-manager source and sync mode, link methods and their evidence, engine switches for missing data streams, sizing values, pipeline system and the status that triggers creation, alert thresholds and settings.
- **Why:** McKinsey's version could not extend to other BUs; onboarding must stay configuration.
- **Acceptance criterion:** A test BU is added, refreshed on its schedule and visible to its users without a software release, and each checklist step's check passes.
- **Source status and priority:** Partial / Must
- **Source section:** 10 Administration and Operations (ADM)
- **Proposed implementation owner:** Security / platform / operations

#### ADM-03 — Administrators shall manage BU settings

- **Requirement:** Administrators shall manage BU settings: house placeholder values, the BU's refresh schedule, pipeline system and the status that triggers creation, assignment sync mode, correction approval switch, alert thresholds and digest switch, and the people in BU manager roles.
- **Why:** configuration, not code.
- **Acceptance criterion:** Each setting changes without a release and takes effect as stated.
- **Source status and priority:** Partial / Must
- **Source section:** 10 Administration and Operations (ADM)
- **Proposed implementation owner:** Security / platform / operations

#### ADM-04 — Administrators shall work queues for decisions the data cannot make

- **Requirement:** Administrators shall work queues for decisions the data cannot make: proposed name matches, unlinked XOi equipment awaiting confirmation, placement of accounts in two BUs, accounts that cannot be placed in any BU, assignment conflicts, refused write-backs, failed pipeline hand-offs, sizing proposals and feedback.
- **Why:** human-in-the-loop decisions are part of the logic today.
- **Acceptance criterion:** Each queue lists items with the evidence and records the decision.
- **Source status and priority:** Partial / Must
- **Source section:** 10 Administration and Operations (ADM)
- **Proposed implementation owner:** Security / platform / operations

#### ADM-05 — Every settings change shall be recorded with who, when, before and after, and be...

- **Requirement:** Every settings change shall be recorded with who, when, before and after, and be reversible.
- **Why:** settings change the numbers.
- **Acceptance criterion:** The settings history shows each change.
- **Source status and priority:** Partial / Must
- **Source section:** 10 Administration and Operations (ADM)
- **Proposed implementation owner:** Security / platform / operations

#### ADM-06 — Run in separate development, test and production environments, with test data that...

- **Requirement:** The system shall run in separate development, test and production environments, with test data that contains no real customer data unless IT policy allows it.
- **Why:** safe change.
- **Acceptance criterion:** IT documents the environments and test data rules.
- **Source status and priority:** New / Must
- **Source section:** 10 Administration and Operations (ADM)
- **Proposed implementation owner:** Security / platform / operations

#### MIG-01 — At each BU's go-live the system shall carry over the business-owned settings and...

- **Requirement:** At each BU's go-live the system shall carry over the business-owned settings and decisions (BU settings, confirmed name decisions, GC and DTO decisions, link evidence and verification decisions, approved sizing assumptions, supplied sizing inputs with their held reasons, XOi corrections, sales teams and BU-wide archives) and each user's work in the prototype: statuses with their revisit dates, notes, personal archives and reassignment history. Each item keeps its original author and date, and statuses map as set out in document 05, section 9.1. Current account assignments come from each BU's system of record at go-live (for a BU with no system of record, from the source confirmed under BUV-07); a prototype reassignment that the system of record does not reflect goes on the BU manager's list to apply or drop.
- **Why:** decisions the business has made and work sellers have done must not be lost or redone, and the enterprise version starts from the systems of record.
- **Acceptance criterion:** Sample checks (MIG-04) pass for each item carried over; each user's carried-over statuses and notes match their last sent prototype state; no prototype reassignment is applied without the BU manager's decision.
- **Source status and priority:** New / Must
- **Source section:** 11 Migration and Cutover (MIG)
- **Proposed implementation owner:** Security / platform / operations

#### MIG-02 — Before a BU's prototype files are withdrawn, the system shall run a final send window in...

- **Requirement:** Before a BU's prototype files are withdrawn, the system shall run a final send window in which each user's statuses, notes and personal archives that are held only in their browser are sent to the central record, with a report to the BU manager of who still has unsent changes. What is received is carried over under MIG-01.
- **Why:** in the prototype some work stays in a user's browser until it is sent, and it would be lost at go-live.
- **Acceptance criterion:** Before withdrawal the report shows no user with unsent changes, or the BU manager signs off each user who still has them; a sample of sent items appears in the enterprise version under its original author and date.
- **Source status and priority:** Partial / Must
- **Source section:** 11 Migration and Cutover (MIG)
- **Proposed implementation owner:** Security / platform / operations

#### MIG-03 — BUs shall go live one at a time or in groups, with a parallel period in which the...

- **Requirement:** BUs shall go live one at a time or in groups, with a parallel period in which the prototype and the enterprise version produce matching results (SCO-01), and the prototype retired for a BU at its go-live.
- **Why:** controlled change, and no two sources of truth.
- **Acceptance criterion:** Parity is signed off per BU; the prototype is no longer in use for a live BU.
- **Source status and priority:** New / Must
- **Source section:** 11 Migration and Cutover (MIG)
- **Proposed implementation owner:** Security / platform / operations

#### MIG-04 — A cutover check shall compare, per BU, opportunity counts and values between the...

- **Requirement:** A cutover check shall compare, per BU, opportunity counts and values between the prototype and the enterprise version, each carried-over item (MIG-01, MIG-02) against its source, the imported activity history (TRK-08) against the prototype's event counts, and assignments against the system of record.
- **Why:** proof that nothing was lost.
- **Acceptance criterion:** The check passes or every difference is explained and signed off.
- **Source status and priority:** New / Must
- **Source section:** 11 Migration and Cutover (MIG)
- **Proposed implementation owner:** Security / platform / operations

### 05 Data Sources, Pipeline and Data Cube (6 requirements)

#### DM-01 — Keep a data dictionary for every field shown to users or used by a rule

- **Requirement:** The system shall keep a data dictionary for every field shown to users or used by a rule: meaning, source, type and owner.
- **Why:** a shared vocabulary for IT, analysts and users.
- **Acceptance criterion:** Every field on a Level 1 or 2 view has a dictionary entry.
- **Source status and priority:** Partial / Must
- **Source section:** 11 Data Requirements
- **Proposed implementation owner:** Data & scoring

#### DM-02 — Every value shown shall be traceable to its source records and the settings version that...

- **Requirement:** Every value shown shall be traceable to its source records and the settings version that produced it (lineage).
- **Why:** users and auditors ask "where did this number come from?"
- **Acceptance criterion:** For any opportunity, an administrator lists its source rows and settings versions.
- **Source status and priority:** Partial / Must
- **Source section:** 11 Data Requirements
- **Proposed implementation owner:** Data & scoring

#### DM-03 — Source values shall never be overwritten by corrections, decodes or enrichment

- **Requirement:** Source values shall never be overwritten by corrections, decodes or enrichment; derived and corrected values shall be stored beside them with provenance.
- **Why:** the reader can always see what the source says.
- **Acceptance criterion:** A corrected field shows both values and the source of each.
- **Source status and priority:** Partial / Must
- **Source section:** 11 Data Requirements
- **Proposed implementation owner:** Data & scoring

#### DM-04 — Every exclusion (intercompany, placeholder, own premises, unmatched, duplicate) shall be...

- **Requirement:** Every exclusion (intercompany, placeholder, own premises, unmatched, duplicate) shall be counted with its reason and visible to administrators; nothing is dropped silently.
- **Why:** silent drops hide real customers.
- **Acceptance criterion:** The reconciliation lists each exclusion reason with counts.
- **Source status and priority:** Exists / Must
- **Source section:** 11 Data Requirements
- **Proposed implementation owner:** Data & scoring

#### DM-05 — Data-quality disclosures (for example revenue with no date, zero-value agreements,...

- **Requirement:** Data-quality disclosures (for example revenue with no date, zero-value agreements, invoices dated before 2000) shall be reported per refresh, never corrected automatically.
- **Why:** transparency over silent fixes.
- **Acceptance criterion:** Each refresh lists its disclosures.
- **Source status and priority:** Partial / Should
- **Source section:** 11 Data Requirements
- **Proposed implementation owner:** Data & scoring

#### DM-06 — The matching evidence gates (hand-check sample size and accuracy) shall be enforced...

- **Requirement:** The matching evidence gates (hand-check sample size and accuracy) shall be enforced before a link method is used for a BU, and the evidence kept with the BU's settings.
- **Why:** name matches are unreliable without proof.
- **Acceptance criterion:** A BU without passing evidence uses only ID links.
- **Source status and priority:** Exists / Must
- **Source section:** 11 Data Requirements
- **Proposed implementation owner:** Data & scoring

### 06 Business Unit Variations (8 requirements)

#### BUV-01 — Every difference between BUs shall be a setting, with no BU-specific code

- **Requirement:** Every difference between BUs shall be a setting, with no BU-specific code: sources, BU membership (including the Financial Dimension Value lists of D365 company 1160), refresh schedule, layout, matching, link methods, owners, house values, intercompany, GC or DTO, vertical and segment source, exclusions, notes, sizing assumptions, pipeline system, sync mode and correction approval (the onboarding checklist in section 5).
- **Why:** a new BU or a BU's move to D365 must not need a release.
- **Acceptance criterion:** A test BU is configured end to end with no code change.
- **Source status and priority:** Partial / Must
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

#### BUV-02 — Each BU's settings shall be versioned, and each refresh shall record the settings version...

- **Requirement:** Each BU's settings shall be versioned, and each refresh shall record the settings version it used.
- **Why:** results must be reproducible.
- **Acceptance criterion:** A past refresh shows its BU settings version.
- **Source status and priority:** Partial / Must
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

#### BUV-03 — A BU that lacks a data stream shall run every rule that does not need it, and show the...

- **Requirement:** A BU that lacks a data stream shall run every rule that does not need it, and show the others as "not run" with the reason.
- **Why:** "not run" must never read as "nothing found".
- **Acceptance criterion:** With projects switched off, rules 3 to 5 show "not run", with the reason, wherever rules are listed or totaled.
- **Source status and priority:** Partial / Must
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

#### BUV-04 — A BU's move from one system of record to another (for example Jonas to D365) shall be a...

- **Requirement:** A BU's move from one system of record to another (for example Jonas to D365) shall be a settings change with a parity check between the old and new source, and choices, links and history shall carry over.
- **Why:** CS3 (2027 Q1) and Capstone (2029 Q1) plan to move to D365.
- **Acceptance criterion:** A test switch keeps every status, assignment and link; opportunity IDs carry over through a crosswalk.
- **Source status and priority:** New / Should
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

#### BUV-05 — Each BU's data-quality notes shall be maintained by administrators and shown to the BU's...

- **Requirement:** Each BU's data-quality notes shall be maintained by administrators and shown to the BU's managers (DAT-12).
- **Why:** known gaps, such as Capstone's unpriced agreements, must be visible.
- **Acceptance criterion:** Notes appear in the manager view and the help page for the BU.
- **Source status and priority:** Exists / Should
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

#### BUV-06 — Each BU shall have a named business contact who approves its account manager source,...

- **Requirement:** Each BU shall have a named business contact who approves its account manager source, house values, link evidence and go-live.
- **Why:** BU decisions belong to the BU.
- **Acceptance criterion:** Each live BU's settings name the contact.
- **Source status and priority:** Partial / Should
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

#### BUV-07 — Each BU's pipeline system, account-assignment sync mode and correction approval shall be...

- **Requirement:** Each BU's pipeline system, account-assignment sync mode and correction approval shall be confirmed with Sales Operations and the BU before its go-live.
- **Why:** these differ by BU and are not recorded in the prototype.
- **Acceptance criterion:** Each BU's settings hold confirmed values before go-live.
- **Source status and priority:** New / Must
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

#### BUV-08 — A BU that cannot yet read live data from the data lake (for example CMS until its tables...

- **Requirement:** A BU that cannot yet read live data from the data lake (for example CMS until its tables are current) shall be able to run on a loaded data set with the same controls, clearly labeled with its as-of date, until its live source is ready.
- **Why:** go-live must not wait for the slowest data source.
- **Acceptance criterion:** A BU on a loaded data set shows its as-of date and a notice; switching to live is a setting.
- **Source status and priority:** Partial / Must
- **Source section:** 7 BU Variation Requirements
- **Proposed implementation owner:** Data & scoring

## Supporting specifications — source file listing

- `Reference/Opportunity Engine Master - engine logic sizing and data sourcing.xlsx`
- `Reference/data-contract/README.md`
- `Reference/data-contract/archive-event-v1.schema.json`
- `Reference/data-contract/assumptions-event-v1.schema.json`
- `Reference/data-contract/bu-assumptions-v1.schema.json`
- `Reference/data-contract/opportunity-engine-contract-v1.schema.json`
- `Reference/data-contract/reassignment-event-v1.schema.json`
- `Reference/data-contract/selection-event-v2.schema.json`
- `Reference/data-contract/teams-event-v1.schema.json`
- `Reference/equipment-useful-life.csv`
- `Reference/settings/am_placeholders.yaml`
- `Reference/settings/engines.yaml`
- `Reference/settings/equipment_sizing_rules_v2.json`
- `Reference/settings/flags.yaml`
- `Reference/settings/gc_dto_keywords.yaml`
- `Reference/settings/scoring.yaml`
- `Reference/settings/xoi_source_contract.yaml`
- `Reference/user-guides/manager-guide.docx`
- `Reference/user-guides/salesperson-guide.docx`
- `Reference/xoi-source-workbook-contract-v1.md`

## Implementation design — synthesis (not a direct FDD requirement)

1. A controlled ingestion pipeline imports BU-specific D365 / ERP / XOi source records and captures versioned snapshots.
2. A normalization service builds customer, site, asset and transaction entities and validates source data.
3. A versioned centrally hosted scoring job executes the 14 rules, precedence, sizing, confidence, likelihood, urgency and ranking.
4. A validated output dataset is published atomically, retaining the previous successful version.
5. Dataverse (or an approved operational datastore) holds displayed scored leads and persistent pursuit, archive, correction, reassignment and external pipeline link records.
6. Model-driven app and custom pages expose salesperson and manager workflows with scope-enforced authorization.
7. Idempotent integration writes to D365 or Sales Pipeline Tracker and reconciles outcomes.
8. Analytics endpoints and Power BI consume activity and historical results.

## Individual salesperson output workbook inventory

These are per-book filtered generated outputs, not independent scoring engines. Sheets vary by the opportunities generated for a specific seller.

| Workbook | Included worksheets |
|---|---|
| CMS_Opportunities_Anthony_Pino.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 8. Past EOL, 11. Faltering, 14. T&M Winback, Account Flags |
| CMS_Opportunities_Art_Espinosa.xlsx | Master Ranked List, 2. T&M attach, 7. Near EOL, 8. Past EOL, 14. T&M Winback, Account Flags |
| CMS_Opportunities_Brian_Adamson.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 10. Energy Eff., 11. Faltering, 12. Electrific., 14. T&M Winback, Account Flags |
| CMS_Opportunities_Eric_Anthony.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 8. Past EOL, Account Flags |
| CMS_Opportunities_House_accounts.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 7. Near EOL, 8. Past EOL, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| CMS_Opportunities_Jerry_Kemper.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| CMS_Opportunities_Keith_Linden.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| CMS_Opportunities_Steve_Nortnik.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| CMS_Opportunities_Unassigned.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| CMS_Opportunities_William_Pearsall.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 4. Past GC Proj, 5. Past DTO Proj, 7. Near EOL, 8. Past EOL, 10. Energy Eff., 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Andrew_Harrah.xlsx | Master Ranked List, 2. T&M attach, Account Flags |
| SWT_Opportunities_Anthony_Pauley.xlsx | Master Ranked List, 2. T&M attach, Account Flags |
| SWT_Opportunities_Ariel_Rodriguez.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 5. Past DTO Proj, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Bill_Raub.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Blake_Bihun.xlsx | Master Ranked List, 1. Soft churn, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Brian_Gress.xlsx | Master Ranked List, 2. T&M attach, 8. Past EOL, Account Flags |
| SWT_Opportunities_Brian_Schoff.xlsx | Master Ranked List, 1. Soft churn, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Chris_Davis.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Chris_Schiro.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 8. Past EOL, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Damon_Keilman.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 8. Past EOL, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Eric_Simadis.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Gerry_Grilec.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_House_accounts.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_James_Richmond.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 14. T&M Winback, Account Flags |
| SWT_Opportunities_Jeff_Allgood.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Jennifer_Celis.xlsx | Master Ranked List, 2. T&M attach, 3. Project end, 6. Exp. warranty, 8. Past EOL, 9. R-22, Account Flags |
| SWT_Opportunities_Jennifer_Schiro.xlsx | Master Ranked List, 2. T&M attach, 8. Past EOL, Account Flags |
| SWT_Opportunities_Josh_Munn.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 14. T&M Winback, Account Flags |
| SWT_Opportunities_Joshua_Dykshorn.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 12. Electrific., 14. T&M Winback, Account Flags |
| SWT_Opportunities_Julian_Holst.xlsx | Master Ranked List, Account Flags |
| SWT_Opportunities_Kevin_Varriale.xlsx | Master Ranked List, 1. Soft churn, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Kyle_Stuart.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, Account Flags |
| SWT_Opportunities_Lilyann_Eggert.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, Account Flags |
| SWT_Opportunities_Marquis_Harding.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 5. Past DTO Proj, Account Flags |
| SWT_Opportunities_Michael_Habasinski.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Mike_McCracken.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 4. Past GC Proj, 5. Past DTO Proj, 11. Faltering, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Robert_Williams.xlsx | Master Ranked List, 2. T&M attach, Account Flags |
| SWT_Opportunities_Scott_Ballweg.xlsx | Master Ranked List, 2. T&M attach, Account Flags |
| SWT_Opportunities_Steve_Slasor.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 9. R-22, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Tiffany_Robinson.xlsx | Master Ranked List, 2. T&M attach, Account Flags |
| SWT_Opportunities_Trevor_Fyler.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 5. Past DTO Proj, 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Unassigned.xlsx | Master Ranked List, 1. Soft churn, 2. T&M attach, 3. Project end, 4. Past GC Proj, 5. Past DTO Proj, 6. Exp. warranty, 7. Near EOL, 8. Past EOL, 11. Faltering, 12. Electrific., 13. SA Winback, 14. T&M Winback, Account Flags |
| SWT_Opportunities_Victoria_Wrigley.xlsx | Master Ranked List, Account Flags |