# Sam Altman Investment Portfolio Analysis

## Overview

This project analyzes a subset of companies associated with Sam Altman’s investment portfolio using structured data exported from [Dealroom.co](https://dealroom.co/).

**Data Filtering Criteria**

For this analysis, only companies with a valuation of at least $200 million were included.

After applying this threshold, the dataset was reduced to 46 portfolio companies.

The objective is to explore portfolio characteristics through quantitative visualizations, focusing on:

- Company valuation
- Total funding raised
- Employee scale
- Industry distribution
- Valuation-weighted industry exposure

The analysis was conducted using Python (Pandas + Plotly) in Google Colab.

---

## Data Source

Data was exported from Dealroom using the Companies section and filtered for portfolio companies meeting specific valuation criteria.

Key fields used:

- Name
- Industries
- Total funding (USD M)
- Valuation (USD)
- Employees latest number

**Note:** “Total funding” represents cumulative capital raised by each company and does not reflect the personal investment amount by Sam Altman.

---

## Visualizations Included

### 1. Portfolio Companies by Employees

Shows operational scale across companies.

**Insight:**

- Stripe and OpenAI dominate in workforce size.
- Long tail of smaller, capital-efficient startups.
- Mix of mature and frontier-stage companies.

---

### 2. Portfolio Companies by Total Funding

Displays cumulative capital raised per company.

**Insight:**

- OpenAI is a capital outlier.
- Clear concentration in high capital-intensity sectors.
- Majority of companies operate with significantly smaller funding bases.

---

### 3. Portfolio Companies by Valuation

Ranks companies by estimated valuation.

**Insight:**

- Portfolio heavily skewed by OpenAI’s valuation.
- Stripe forms a second-tier anchor.
- Significant valuation dispersion across the portfolio.

---

### 4. Portfolio Distribution by Industry

Counts number of companies per industry.

**Insight:**

- Concentration in fintech, enterprise software, and robotics.
- Diversified exposure across health, energy, transportation.
- Broad technological thesis rather than single-sector focus.

---

### 5. Portfolio Exposure by Industry (Valuation-weighted)

Aggregates valuation by industry.

**Insight:**

- Enterprise software dominates total valuation exposure.
- Fintech forms the second largest block.
- Smaller industries contribute marginal valuation weight.
- This visualization highlights capital concentration rather than company count.
