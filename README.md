# Deloitte_DataAnalytics_Simuation-Forage
# Daikibo Gender Pay Equity Analysis

## Overview

Daikibo Industrials initiated an internal investigation following employee complaints regarding gender pay inequality.

The Forensic Tech team developed an algorithm that generated an **Equality Score** (ranging from -100 to +100) to quantify pay balance across job roles and factories.

The objective of this project was to:

- Classify equality scores into meaningful categories
- Identify potentially discriminatory pay patterns
- Visualize results using Excel and Tableau dashboards

This project was completed as part of a Forage Virtual Job Simulation

---

## Business Problem

Pay inequality can negatively impact employee morale, company reputation, and legal compliance.

Daikibo required:

- A structured classification system for equality scores
- Clear identification of high-risk roles and factories
- A visual dashboard to support leadership decision-making

---

## Dataset

The dataset contains:

- Factory
- Job Role
- Equality Score (-100 to +100)

Each Equality Score represents the degree of gender pay imbalance for a specific role at a specific factory.

---

## Methodology

### 1. Equality Classification Logic

A new column, **Equality Class**, was created based on score thresholds:

- Fair: -10 to +10  
- Unfair: -20 to -11 and 11 to 20  
- Highly Discriminative: less than -20 or greater than 20  

This classification enables structured severity analysis of pay inequality.

### 2. Data Transformation (Excel)

- Applied conditional logic using nested IF statements
- Categorized equality levels
- Prepared dataset for visualization

### 3. Dashboard Development (Tableau)

An interactive dashboard was built to:

- Visualize distribution of equality classes
- Identify factories with multiple discriminatory roles
- Compare severity across job roles
- Highlight high-risk areas for HR intervention

---

## Key Insights

- Certain job roles exhibit highly discriminative equality scores.
- Some factories show clusters of unfair classifications.
- Visualization reveals structural patterns not immediately visible in raw data.

These insights can help Daikibo prioritize audits and corrective actions.

---

## Tools Used

- Microsoft Excel (data transformation and classification logic)
- Tableau (interactive dashboard visualization)

---

## Skills Demonstrated

- Business rule implementation
- Data classification logic
- HR analytics
- Dashboard design and visualization
- Insight communication
- Data-driven decision support

---

## Disclaimer

This project was completed as part of a Forage Virtual Job Simulation. The dataset provided through the simulation is not redistributed beyond the processed version included here.

---

## Author

Harneet  Kaur
