# Branch-Data-Quality-Performance-Dashboard
## Overview

This project is an anonymized portfolio dashboard created to demonstrate branch-level data quality performance monitoring.

The dashboard helps stakeholders compare branch performance based on accuracy, validity, score, rank, and grade. It is designed to make data quality performance easier to review in one page, especially for identifying top-performing branches and branches that may need follow-up.

This portfolio version uses synthetic data only. No real company name, real branch name, internal system screenshot, production data, or confidential business logic is included.

---

## Project Context

In operational reporting environments, branch offices often process large volumes of participant or customer-related data. Management needs a clear way to monitor whether each branch is producing accurate and valid data.

Without a dashboard, performance review can become manual, scattered, and difficult to compare across branches.

This dashboard turns branch-level data quality indicators into a simple monitoring view so stakeholders can quickly understand performance gaps and follow-up priorities.

---

## Problem

The main challenge was to make data quality performance easier to monitor and compare.

The dashboard needed to answer questions such as:

- Which branches have the strongest data quality performance?
- Which branches have lower accuracy or validity scores?
- Which branches are ranked highest or lowest?
- Which branches need closer review?
- Are branches meeting the expected accuracy and validity targets?

---

## Objective

The goal was to build a clear, one-page dashboard for monitoring branch data quality performance.

The dashboard focuses on:

- Accuracy target
- Validity target
- Branch accuracy score
- Branch validity score
- Overall score
- Branch rank
- Branch grade
- Top 10 branch ranking
- Bottom 10 branch ranking
- Branch performance comparison

---

## Dashboard Features

| Feature | Purpose |
| --- | --- |
| Branch filter | Focus on selected branch data |
| Month filter | View performance for a selected month |
| Year filter | View performance for a selected year |
| Accuracy target card | Show the target accuracy benchmark |
| Validity target card | Show the target validity benchmark |
| Rank by branch table | Compare branch grade, rank, accuracy, validity, and score |
| Top 10 rank chart | Highlight the strongest branch performance |
| Bottom 10 rank chart | Highlight branches that may need follow-up |
| Branch performance chart | Compare overall score across branches |

---

## Data Quality Metrics

### Accuracy

Accuracy measures how close the branch data is to the expected correct result.

A high accuracy score means the branch output has fewer errors and is more reliable for reporting.

### Validity

Validity measures whether the data passes required validation rules or business checks.

A high validity score means the data is more complete, consistent, and ready to be used for reporting.

### Score

Score combines the key data quality indicators into one performance value.

It helps stakeholders compare branches more easily.

### Rank

Rank shows branch position based on overall data quality performance.

### Grade

Grade simplifies the performance result into a category that is easy to scan.

Example:

- A = Strong performance
- B = Good performance
- C = Needs review
- D = Needs improvement

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

## My Role

My role in this project was to translate data quality monitoring needs into a simple dashboard structure.

I worked on:

- Defining the dashboard metrics
- Structuring the synthetic dataset
- Creating branch-level performance indicators
- Designing rank and grade logic
- Building a clean one-page dashboard layout
- Making data quality performance easier to compare across branches

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

## Confidentiality Note

This project is based on an anonymized version of a real data quality monitoring use case.

To protect confidentiality, this repository does not include:

- Real company names
- Real branch names
- Real participant or customer data
- Internal system screenshots
- Production database structure
- Confidential business rules
- Original dashboard files

All data, visuals, and examples are recreated using synthetic data for portfolio demonstration purposes only.

---

## Business Impact

This dashboard helps improve visibility into branch-level data quality performance.

The main value is making it easier for stakeholders to:

- Monitor accuracy and validity
- Compare branch performance
- Identify top and bottom performers
- Spot branches that may need follow-up
- Review data quality performance in one page
- Support decisions using clearer performance evidence

---

## Skills Demonstrated

This project demonstrates skills in:

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
