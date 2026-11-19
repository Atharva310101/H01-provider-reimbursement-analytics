from pathlib import Path
content = """# H01 — Project Status

**Project:** Provider Contract Reimbursement & Rate Forecasting Analytics  
**Last updated:** 2026-11-18  
**Current phase:** Module 02 — Business Requirements & KPIs (ready to begin)  
**Overall status:** Planning / domain foundation established  
**Repository:** Created by project owner; repository URL not recorded here

## 1. Project objective

Build a reproducible, locally runnable, free-first, payer-side analytics platform to evaluate provider reimbursement, model negotiated contract rate changes, analyze utilization and allowed spending, and forecast financial impact. The work is a portfolio project, not a real client engagement.

## 2. Progress by module

| Module | Status | Notes |
|---|---|---|
| 01 — Business Domain Masterclass | Foundational checkpoint reached; ongoing reference | Lessons 1.1–1.3 and exercises completed; Lesson 1.4 taught, exercise not submitted |
| 02 — Business Requirements & KPIs | Next | Define business problem, stakeholders, use cases, KPIs, scope, and acceptance criteria |
| 03 — Data Sources & Data Modeling | Not started | Research datasets, data limitations, data dictionary, dimensional model |
| 04 — Advanced SQL Lab | Not started | Reimbursement queries, reconciliation, tests |
| 05 — Python Analytics & Forecasting | Not started | EDA, rate scenarios, forecasting |
| 06 — Advanced Excel Lab | Not started | Financial model, sensitivity analysis |
| 07 — Power BI & DAX | Not started | Semantic model, KPI measures, reporting |
| 08 — Testing & Automation | Not started | Data quality and reproducible pipelines |
| 09 — Business Case & GitHub | Not started | Portfolio documentation and defensible results |

## 3. Domain concepts covered

- Providers, payers, members, employers, and insurance intermediaries
- Insurance premiums, claims expenses, and simplified insurance operating economics
- Billed charges, negotiated allowed amounts, contractual adjustments, and provider costs
- Service volume and expected allowed revenue (rate × volume)
- Deductibles, copays, coinsurance, out-of-pocket maximums, and family deductible examples
- Fully insured versus self-funded employer arrangements
- Allowed spending versus insurer-paid spending
- Static contract rate impact scenarios and their assumptions

### Exercises verified

- **Lesson 1.1:** Expected allowed revenue across three synthetic payers = **$870,000**; correct.
- **Lesson 1.2:** A 5% increase on a $300 MRI rate over 20,000 services gives **$300,000** additional annual allowed spending; correct. Discussed utilization, coding/service mix, and member cost sharing.
- **Lesson 1.3:** For $500 allowed with $300 deductible remaining and 20% coinsurance, member responsibility = **$340**, insurer payment = **$160**; correct. Rate increase to $550 changes insurer payment to **$200**, a **$40** increase; correct.
- **Family cost-sharing check:** With family deductible met and 20% coinsurance, insurer pays **$800** of a $1,000 allowed service under stated assumptions; correct.
- **Lesson 1.4:** Insurance funding models taught; associated contract-impact exercise not completed before transition.

All example values above are **synthetic teaching scenarios**, not measured project outcomes.

## 4. Decisions made

1. **Perspective:** Payer-side provider contracting and reimbursement analytics.
2. **Approach:** Business requirements before data modeling or code.
3. **Learning workflow:** One manageable step at a time, with review before advancing.
4. **Technology preference:** Free, open-source, locally runnable; SQL, Python, Excel, and Power BI as appropriate.
5. **Data policy:** Prefer real public data; label synthetic data and assumptions; never imply access to proprietary claims or contract data.
6. **Project organization:** Separate chats by module; this domain chat remains a reference. Track decisions and progress in repository Markdown files.
7. **GitHub:** Repository creation reported complete; technical scaffolding and implementation not yet confirmed.

## 5. Open questions and risks

- Which concrete payer-side business decisions and stakeholders are in scope?
- Which KPIs will be defined and what are their grains, formulas, exclusions, and reconciliation rules?
- What public claims, utilization, and pricing data are available and legally reusable?
- Which contract terms require explicitly synthetic modeling?
- How will the analysis distinguish allowed spending, insurer-paid amounts, and member responsibility?
- What assumptions are required for service mix, utilization forecasts, and benefit designs?
- Claims lifecycle, CPT/HCPCS, DRG/APC, Medicare/Medicaid methodologies, and advanced contracting concepts still require targeted study.

## 6. Next milestone — Module 02

**Goal:** Produce a reviewed business requirements baseline before selecting datasets or writing analytical code.

**First task:** Define the primary business problem and identify the decisions a Provider Analytics manager or contracting team needs to make.

**Planned outputs (not yet complete):**
- Business problem statement and project objectives
- Stakeholder and decision matrix
- Prioritized use cases and business questions
- KPI dictionary with formulas and assumptions
- Scope, exclusions, acceptance criteria, and data requirements

**Milestone exit criteria:** Business requirements and KPI definitions are coherent, measurable, and sufficiently specific to guide data sourcing and modeling.


## M02 — Business Requirements & KPIs
Date: 2026-11-18
Status: In progress

### Completed
- Module 01 introductory healthcare reimbursement checkpoint
- Introduced payer-side contracting decision context
- Identified preliminary stakeholders and decisions
- Drafted initial H01 business problem and objective

### Proposed decisions (not yet approved)
- Focus: payer-side provider contracting and rate forecasting
- Primary financial measure: modeled allowed spending
- Use public and clearly labeled synthetic data
- Keep contract rate impact distinct from utilization forecasting

### Open issues
- Review and approve business problem statement
- Prioritize stakeholder use cases
- Define business questions and KPI specifications
- Establish scope, exclusions, and acceptance criteria

### Next action
- Complete Exercise 02.1 and review stakeholder framing
