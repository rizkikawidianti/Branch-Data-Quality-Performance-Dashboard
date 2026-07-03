# Branch Data Quality Performance Dashboard

## Executive Summary

This project is an anonymized portfolio dashboard that demonstrates branch-level data quality performance monitoring.

The dashboard helps stakeholders review whether branch data meets expected accuracy and validity standards. It turns scattered performance indicators into one management-ready view with branch scores, ranks, grades, top performers, bottom performers, and follow-up priorities.

This project supports a Data Quality Analyst or Fraud Data Analyst positioning because it focuses on the control layer behind reliable reporting: validation logic, performance thresholds, exception visibility, and branch-level monitoring.

> **Confidentiality Note**
>
> This portfolio version uses synthetic data only. It does not include real company names, real branch names, real participant or customer data, internal system screenshots, production database structures, or confidential business rules. All visuals and examples are recreated for portfolio demonstration.

---

## Business Context

In large operational environments, branch offices often process high volumes of participant, customer, or account-related records. Management needs to know whether each branch submits data that is accurate, valid, and reliable enough for reporting.

Without a structured monitoring dashboard, data quality review can become manual and inconsistent. Low-performing branches may be missed. Accuracy issues may only appear after reports have already been used for decisions.

This dashboard solves that problem by giving stakeholders a clear view of branch-level data quality performance.

---

## Business Problem

Management needed a simple way to monitor data quality performance across branches.

The dashboard was designed to answer these questions:

- Which branches have the strongest data quality performance?
- Which branches fall below accuracy or validity expectations?
- Which branches need follow-up from the central team?
- Are performance issues isolated to a few branches or spread across the network?
- Which branches should be reviewed first based on score, rank, and grade?

The main risk was not just poor reporting. The deeper risk was decision-making based on inaccurate or invalid branch data.

---

## Project Objective

The objective was to build a one-page dashboard that helps stakeholders monitor branch data quality in a consistent and repeatable way.

The dashboard focuses on:

- Accuracy target
- Validity target
- Branch accuracy score
- Branch validity score
- Overall data quality score
- Branch rank
- Branch grade
- Top 10 branch ranking
- Bottom 10 branch ranking
- Branch performance comparison
- Follow-up priority based on score and grade

---

## Dashboard Features

| Feature | Purpose |
| --- | --- |
| Branch filter | Review performance for a selected branch |
| Month filter | Compare performance by reporting month |
| Year filter | Review performance across reporting periods |
| Accuracy target card | Show the expected accuracy benchmark |
| Validity target card | Show the expected validity benchmark |
| Branch ranking table | Compare branch grade, rank, accuracy, validity, and score |
| Top 10 branch chart | Highlight branches with the strongest performance |
| Bottom 10 branch chart | Surface branches that need closer review |
| Branch performance chart | Compare overall data quality scores across branches |
| Grade logic | Translate numeric performance into an easier review category |

---

## Data Quality Metrics

### Accuracy

Accuracy measures how close branch data is to the expected correct result.

A high accuracy score means the branch output has fewer errors and can be trusted for reporting.

### Validity

Validity measures whether the data passes required validation rules or business checks.

A high validity score means the data is more complete, consistent, and ready for stakeholder use.

### Score

Score combines the key data quality indicators into one performance value.

This makes it easier to compare branches using a single summary metric.

### Rank

Rank shows branch position based on overall data quality performance.

This helps stakeholders identify the strongest and weakest branches quickly.

### Grade

Grade translates performance into a simple review category.

Example:

- A = Strong performance
- B = Good performance
- C = Needs review
- D = Needs improvement

---

## How This Project Follows the V.E.R.I.F.Y. Framework

| VERIFY Step | How It Appears in This Project |
| --- | --- |
| Validate | Accuracy and validity metrics define what acceptable data quality looks like. |
| Examine | Branch-level scores, ranks, and grades make performance gaps visible. |
| Reconcile | Branch data is compared against expected targets, central ratios, and reporting benchmarks. |
| Identify Signals | Low scores, low grades, and negative deviations act as signals for data quality risk. |
| Flag and Escalate | Bottom 10 rankings and branch grades help stakeholders decide which branches need follow-up. |
| Yield Standards | The dashboard creates a repeatable standard for monthly branch data quality review. |

This dashboard represents the reporting layer of the VERIFY process. It turns validation results into a structured monitoring view that stakeholders can use for follow-up decisions.

---

## Sample Synthetic Data Structure

The dashboard uses synthetic data with the following fields:

| Field | Description |
| --- | --- |
| date | Reporting date |
| branch_code | Synthetic branch code |
| branch_name | Synthetic branch name |
| active_total | Synthetic active participant total |
| pens_total | Synthetic pension participant total |
| total | Combined total records |
| act_report | Active data reporting percentage |
| pens_report | Pension data reporting percentage |
| ratio_central | Central-level ratio indicator |
| ratio_country | Country-level ratio indicator |
| validity | Data validity score |
| accuracy | Data accuracy score |
| deviation | Difference from expected performance |
| score | Overall data quality score |
| rank | Branch ranking |
| branch_grade | Branch performance grade |

---

## My Role

My role was to translate branch data quality monitoring needs into a clear dashboard structure.

I worked on:

- Defining dashboard metrics
- Structuring the synthetic dataset
- Creating branch-level performance indicators
- Designing rank and grade logic
- Building a clean one-page dashboard layout
- Turning data quality performance into a stakeholder-ready review format

---

## Tools Used

- Tableau
- SQL
- Microsoft Excel
- Synthetic data preparation
- Data validation logic
- Dashboard design
- Data quality monitoring

---

## Business Impact

This dashboard helps improve visibility into branch-level data quality performance.

The main value is that stakeholders can:

- Monitor accuracy and validity in one page
- Compare branch performance consistently
- Identify top and bottom performers
- Spot branches that need follow-up
- Review data quality performance by month and year
- Support decisions with clearer performance evidence
- Reduce the risk of relying on inaccurate branch data

---

## Skills Demonstrated

- Data quality monitoring
- Data validation
- KPI reporting
- Dashboard development
- Synthetic data preparation
- Ranking and grading logic
- Data visualization
- Branch performance analysis
- Reporting quality control
- Management-ready insight delivery
- VERIFY Framework application

## Mockup UI
<img width="1672" height="941" alt="ChatGPT Image Jul 2, 2026, 07_40_33 PM" src="https://github.com/user-attachments/assets/94749285-2928-4894-9182-3559cbaba147" />

