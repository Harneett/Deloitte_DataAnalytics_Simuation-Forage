# Gender Pay Equity Classification

## Overview

Daikibo Industrials requested an analysis of gender pay equality across job roles and factories.

An internal algorithm generated an Equality Score (-100 to +100) to quantify pay balance.

The objective was to classify equality severity levels using structured thresholds.

---

## Dataset

- Factory
- Job Role
- Equality Score (-100 to +100)

---

## Classification Logic

A new column, **Equality Class**, was created using:

- Fair: -10 to +10
- Unfair: -20 to -11 and 11 to 20
- Highly Discriminative: less than -20 or greater than 20

This categorization supports severity-based HR investigation.

---

## Methodology

- Implemented nested IF logic in Excel.
- Applied classification consistently across all records.
- Validated threshold boundaries.

---

## Business Impact

This structured classification enables leadership to:

- Identify high-risk roles
- Detect systemic inequality patterns
- Prioritize corrective compensation review
