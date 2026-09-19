# Supplier Performance & Procurement Risk Analysis
## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Supplier Spend Analysis](#2-supplier-spend-analysis)
3. [Supplier Risk Analysis](#3-supplier-risk-analysis)
4. [Supplier Performance](#4-supplier-performance)
5. [Category Supplier Dependency](#5-category-supplier-dependency)
6. [Geographic Supplier Exposure](#6-geographic-supplier-exposure)
7. [Key Supplier Findings](#7-key-supplier-findings)
8. [Procurement Action Framework](#8-procurement-action-framework)
9. [Business Takeaways](#9-business-takeaways)
10. [Methodology](#10-methodology)
11. [Limitations](#11-limitations)
12. [Tools Used](#12-tools-used)
13. [Dashboard](#13-dashboard)

## 1. Executive Summary

This project analyzes supplier spend, operational performance, supplier concentration, and procurement risk across a dataset of 25 suppliers and 200 products.

The analysis combines procurement spend with supplier lead time and reliability ratings to identify where procurement teams may need greater monitoring or further investigation.

![Dashboard showing Supplier Performance & Procurement Risk](Supplier%20Performance%20&%20Procurement%20Risk.png)

### Key findings

- Total procurement spend: **£18.30M**
- Suppliers analyzed: **25**
- Products supplied: **200**
- Orders analyzed: **5,894**
- Units ordered: **136,404**
- Average supplier lead time: **21.72 days**
- Average supplier reliability: **3.85 / 5**
- The five largest suppliers account for **31.19%** of total procurement spend.
- **21 of 25 suppliers (84%)** have at least one defined risk flag.
- **12 of 25 suppliers (48%)** have two or more risk flags.
- **3 suppliers (12%)** have all three risk flags.
- No individual supplier accounts for more than 20% of spend within any product category.

The analysis indicates that supplier exposure is distributed across a relatively broad supplier base, but several high-spend suppliers also exhibit combinations of long lead times and/or below-average reliability.

---

# 2. Supplier Spend Analysis

Supplier procurement spend was calculated using:

`Quantity × Supplier Unit Cost`

The five largest suppliers by procurement spend are:

| Supplier | Procurement Spend | Share of Total |
|---|---:|---:|
| Rhodes PLC | £1,175,015 | 6.42% |
| Sanchez, Ford and Nelson | £1,164,433 | 6.36% |
| Davis Inc | £1,154,324 | 6.31% |
| Montgomery, Hensley and Ray | £1,114,281 | 6.09% |
| Ellis, Baker and Wright | £1,099,100 | 6.01% |
| **Top 5** | **£5,707,152** | **31.19%** |

### Insight

The top five suppliers collectively represent **31.19% of total procurement spend**.

However, the largest individual supplier represents only **6.42%** of total spend. This means procurement exposure is distributed rather than dominated by a single supplier.

The top five suppliers should nevertheless receive closer monitoring because changes in their pricing, lead times, reliability, or supply continuity could affect a significant portion of total procurement expenditure.

---

# 3. Supplier Risk Analysis

A supplier risk indicator was developed using three measurable conditions:

### Risk flags

**1. High Spend**

Supplier procurement spend is above the average supplier spend of:

**£731,898.94**

**2. Long Lead Time**

Supplier average lead time is above the supplier average of:

**21.72 days**

**3. Low Reliability**

Supplier reliability rating is below the supplier average of:

**3.85 / 5**

Each supplier receives between 0 and 3 risk flags.

This is an analytical screening method rather than a definitive assessment of supplier business risk.

### Risk flag distribution

| Risk Flags | Suppliers | Share |
|---:|---:|---:|
| 0 | 4 | 16% |
| 1 | 9 | 36% |
| 2 | 9 | 36% |
| 3 | 3 | 12% |
| **Total** | **25** | **100%** |

### Insight

**21 of 25 suppliers (84%) have at least one defined risk flag**, while **12 suppliers (48%) have two or more**.

Only three suppliers meet all three screening criteria:

- Clark PLC
- Martinez, Nielsen and Miller
- Ramirez-Lewis

Together, these suppliers represent approximately **£2.52M**, or **13.78% of total procurement spend**.

These suppliers represent a useful starting point for procurement teams conducting deeper supplier reviews.

---

# 4. Supplier Performance

The supplier base has:

- Average lead time: **21.72 days**
- Lead-time range: **6–43 days**
- Average reliability: **3.85 / 5**
- Reliability range: **2.9–5.0**

### Longest lead times

| Supplier | Lead Time | Reliability | Spend |
|---|---:|---:|---:|
| Burgess-Patterson | 43 days | 4.2 | £1.05M |
| Blake and Sons | 40 days | 3.2 | £0.46M |
| Johnson-Davis | 39 days | 3.0 | £0.48M |
| Flowers, Martin and Kelly | 39 days | 3.1 | £0.47M |
| Ramirez-Lewis | 31 days | 3.3 | £0.74M |
| Clark PLC | 29 days | 3.4 | £1.00M |
| Sanchez, Ford and Nelson | 28 days | 4.1 | £1.16M |

### Insight

Long lead time does not always coincide with low reliability.

For example, **Burgess-Patterson has the longest average lead time at 43 days but a reliability rating of 4.2/5**.

This suggests that different supplier issues require different procurement responses. A supplier with long but consistent lead times may require inventory and planning adjustments, while a supplier combining long lead times with lower reliability may warrant a broader performance review.

---

# 5. Category Supplier Dependency

The analysis also examined the largest supplier within each product category.

| Category | Largest Supplier | Supplier Share |
|---|---|---:|
| Electronics | Rhodes PLC | 18.52% |
| Health & Beauty | Sanchez, Ford and Nelson | 17.38% |
| Home & Kitchen | Zuniga, Wong and Lynch | 16.12% |
| Office Supplies | Davis Inc | 10.47% |
| Outdoor & Sports | Ellis, Baker and Wright | 8.41% |

### Insight

No supplier accounts for more than 20% of spend within an individual category.

The highest observed category concentration is **18.52% in Electronics**, where Rhodes PLC is the largest supplier.

This indicates that category spend is distributed across multiple suppliers rather than being dominated by a single supplier.

However, the largest supplier in each category can still be monitored for changes in pricing, lead time, reliability, or supply continuity.

---

# 6. Geographic Supplier Exposure

Supplier spend was also analyzed by supplier country.

| Country | Suppliers | Procurement Spend | Share |
|---|---:|---:|---:|
| Germany | 6 | £4.16M | 22.71% |
| Netherlands | 3 | £2.68M | 14.67% |
| Vietnam | 3 | £2.65M | 14.47% |
| Finland | 3 | £2.46M | 13.43% |
| Sweden | 3 | £2.08M | 11.34% |
| South Korea | 3 | £1.59M | 8.68% |
| China | 2 | £1.28M | 6.97% |
| Turkey | 1 | £0.94M | 5.15% |
| Italy | 1 | £0.47M | 2.58% |

### Insight

Germany represents the largest country-level supplier exposure at **22.71% of procurement spend**.

Geographic concentration alone does not establish supply risk. Additional factors such as transportation routes, geopolitical conditions, tariffs, supplier substitutability, and category criticality would be required for a more complete geographic risk assessment.

---

# 7. Key Supplier Findings

### Clark PLC

Clark PLC has:

- £997K procurement spend
- 29-day average lead time
- 3.4/5 reliability
- 3 risk flags

This combination means the supplier exceeds the spend threshold while also having both a longer-than-average lead time and below-average reliability.

**Potential procurement focus:** supplier performance review, lead-time improvement, and continuity planning.

---

### Rhodes PLC

Rhodes PLC has:

- £1.18M procurement spend
- 19-day average lead time
- 3.1/5 reliability
- 2 risk flags
- 18.52% of Electronics category spend

This supplier is the largest supplier by procurement spend and also has the largest observed supplier share within a category.

**Potential procurement focus:** performance monitoring and Electronics category dependency assessment.

---

### Sanchez, Ford and Nelson

The supplier has:

- £1.16M procurement spend
- 28-day average lead time
- 4.1/5 reliability
- 2 risk flags
- 17.38% of Health & Beauty category spend

The main identified issue is lead time rather than reliability.

**Potential procurement focus:** lead-time management and inventory planning.

---

### Burgess-Patterson

Burgess-Patterson has the longest average lead time:

**43 days**

However, its reliability rating is **4.2/5**, above the overall supplier average.

**Potential procurement focus:** inventory and replenishment planning rather than treating the supplier as a general performance problem.

---

# 8. Procurement Action Framework

The analysis suggests several areas for procurement teams to investigate.

| Finding | Potential Procurement Action |
|---|---|
| High spend + below-average reliability | Supplier performance review |
| High spend + long lead time | Lead-time and inventory review |
| Multiple risk flags + material spend | Prioritized supplier risk assessment |
| High category supplier concentration | Supplier dependency review |
| Long lead time + high reliability | Inventory and replenishment planning |
| Low spend + few/no flags | Routine monitoring |

These actions are proposed based on the analytical indicators in this dataset. They should not be treated as automatic decisions without considering supplier criticality, contractual terms, switching costs, service levels, and business context.

---

# 9. Business Takeaways

The analysis highlights five main procurement themes:

### 1. Spend is distributed across the supplier base

The largest supplier represents only **6.42%** of total procurement spend, while the top five account for **31.19%**.

### 2. Several suppliers combine multiple risk indicators

Three suppliers meet all three screening criteria, representing approximately **13.78% of total procurement spend**.

### 3. Reliability and lead time are different dimensions

A long lead time does not necessarily mean poor reliability. Procurement decisions should therefore distinguish between delivery speed and delivery consistency.

### 4. Category dependency is present but distributed

The highest supplier share within a category is **18.52%**, suggesting that no category is dominated by a single supplier in this dataset.

### 5. High-spend suppliers deserve differentiated monitoring

The combination of procurement spend, lead time, reliability, and category exposure provides a more useful screening framework than looking at spend alone.

---

# 10. Methodology

## Procurement Spend

Supplier procurement spend was calculated as:

`Quantity × Product Unit Cost`

The analysis uses `products.unit_cost` rather than the customer-facing selling price stored in `order_items.unit_price`.

## Supplier Metrics

Supplier-level metrics include:

- Procurement spend
- Spend percentage
- Product count
- Order count
- Units ordered
- Average lead time
- Reliability rating

## Risk Screening

Risk flags were based on supplier-level averages:

- High spend: `Spend > £731,898.94`
- Long lead time: `Lead Time > 21.72 days`
- Low reliability: `Reliability < 3.85`

The resulting 0–3 risk flag count is intended as a **screening indicator**, not a statistically validated risk score.

---

# 11. Limitations

Several limitations should be considered when interpreting the analysis.

### Supplier reliability

Reliability ratings are provided as supplier-level values. The dataset does not contain transaction-level delivery performance such as:

- Promised delivery date
- Actual delivery date
- On-time delivery percentage
- Late delivery frequency

Therefore, the reliability rating cannot be independently calculated from the order data.

### Lead time

Lead time is represented by an average supplier-level value rather than individual purchase-order lead times.

### Risk thresholds

The risk thresholds are based on averages within this dataset. They are analytical benchmarks rather than industry standards.

### Geographic risk

Country-level spend concentration does not automatically indicate geopolitical or logistics risk.

### Category dependency

Supplier concentration was assessed using spend share, but the analysis does not include supplier switching costs, alternative suppliers, contractual restrictions, or product criticality.

### Currency

The underlying procurement analysis is presented in **£**. The Tableau dashboard may display currency using the dashboard's configured currency format.

---

# 12. Tools Used

- **MySQL** — Data analysis and supplier risk calculations
- **Tableau Public** — Interactive dashboard and visualization
- **Excel/CSV** — Data preparation and export
- **GitHub** — Project documentation and portfolio presentation

---

# 13. Dashboard
![Dashboard showing Supplier Performance & Procurement Risk](Supplier%20Performance%20&%20Procurement%20Risk.png)
The Tableau dashboard provides an interactive view of:

- Total procurement spend
- Supplier count
- Order volume
- Units ordered
- Average lead time
- Average supplier reliability
- Supplier risk matrix
- Supplier risk distribution
- Top 10 suppliers by procurement spend

The dashboard is designed to help procurement stakeholders move from **spend visibility → supplier performance → risk identification → procurement action**.
