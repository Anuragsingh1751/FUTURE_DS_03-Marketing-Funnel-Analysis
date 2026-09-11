# FUTURE_DS_03 – Marketing Funnel & Conversion Performance Analysis

## Objective
Analyze direct-marketing campaign performance, identify conversion patterns, and provide actionable recommendations.

## Dataset
UCI Bank Marketing (`bank-full.csv`) – 45,211 records and 17 variables.

## KPIs
- Campaign contacts: 45,211
- Subscriptions: 5,289
- Non-conversions: 39,922
- Conversion rate: 11.70%
- Drop-off rate: 88.30%

## Funnel
Because the dataset has no explicit web Visitor or Lead field, the defensible observable funnel is:

**Campaign Contacts → Subscriptions**

No artificial lead count is created.

## Analyses
- Contact channel
- Job
- Marital status
- Education
- Housing/personal loan
- Campaign month
- Previous campaign outcome
- Business recommendations

## Important Notes
- `duration` is post-call information and should not be used for realistic pre-call targeting.
- `unknown` is retained as a category.
- Observed relationships are associations, not causal effects.

## Deliverables
- `Dashboard/FUTURE_DS_03_Marketing_Funnel_Analysis.xlsx`
- `Report/FUTURE_DS_03_Marketing_Funnel_Analysis_Report.pdf`

## Source
UCI Machine Learning Repository – Bank Marketing
DOI: 10.24432/C5K306
