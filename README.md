# 🛒 eBay Customer RFM Analysis & Marketing Strategy

![Python](https://img.shields.io/badge/Python-3.13-blue)  
![Status](https://img.shields.io/badge/Status-Completed-green)  
![Pandas](https://img.shields.io/badge/Pandas-2.x-lightgrey)  
![License](https://img.shields.io/badge/License-MIT-green)

**Creator:** Rivaldi

---

## Project Overview

This project is a **customer segmentation and marketing strategy analysis** using **RFM** and **CV-RFM** on the Online Retail II dataset.

The analysis segments **5,942 customers into 11 behavioral groups**, identifies high-value segments, uncovers revenue opportunities, and translates insights into a **3-month retention and growth strategy**.

Designed from a **CRM and growth analytics perspective**, the project simulates how data can support segmentation strategy, budget prioritization, and lifecycle marketing decisions.

---

## Context, Problem, and Users

### 1. Context  
Not all customers contribute equal value. While some drive recurring revenue, others show churn signals or untapped growth potential. Without structured segmentation, marketing investment is often inefficient.

### 2. Problem  
How can customer behavior data be used to prioritize retention efforts, identify hidden value, and improve marketing ROI?

### 3. Users  
CRM, Growth Marketing, Lifecycle Marketing, and Customer Analytics teams looking to optimize retention and revenue.

---

## Business Questions

- Which customer segments drive the highest value?
- Which segments are at churn risk?
- Where should retention budget be prioritized?
- Which segments hold growth opportunity?
- What actions should each segment receive?

---

## Goals

- Identify high-value customer segments  
- Quantify revenue concentration by segment  
- Surface untapped mid-tier growth opportunities  
- Build actionable segment-level strategies  
- Support data-driven retention prioritization

---

## Deliverables

- RFM customer segmentation model  
- Revenue contribution analysis  
- CV-RFM customer value scoring  
- Tier opportunity analysis  
- Segment action strategy map  
- 3-month implementation roadmap

---

## Dataset

| Metric | Value |
|---|---|
| Source | Online Retail II (UCI) |
| Customers | 5,942 |
| Period | 2009–2011 |
| Method | RFM + CV-RFM |

**Key Features:**  
`Recency`, `Frequency`, `Monetary`, customer value tiers, segment labels

---

## Key Findings

### Revenue Concentration
Top customer segments generate the majority of revenue while representing a minority of customers.

### Growth Opportunity
Mid-tier segments show strong upsell and retention potential.

### Churn Risk
At-risk and inactive segments benefit from lower-cost recovery strategies.

### Hidden High-Value Users
CV-RFM reveals strong-value customers hidden within mid-level segments.

---

## Strategic Recommendations

| Focus | Strategy |
|---|---|
| High-Value Customers | Protect and deepen loyalty |
| Growth Segments | Nurture and upsell |
| At-Risk Customers | Reactivation campaigns |
| Low-Value Segments | Low-cost automated recovery |

---

## Focus Areas

- Retention prioritization by segment  
- Segment-based lifecycle campaigns  
- Budget allocation by revenue opportunity  
- Customer value scoring for CRM strategy

---

## 🔗 Links

- 🎨 **Canva Presentation:** *Under revision — coming soon*

---

## Libraries

- **pandas** — data manipulation and analysis  
- **numpy** — numerical computing  
- **matplotlib / seaborn** — visualization  
- **squarify** — treemap visualization  

---

## Repository Structure

```text
├── README.md
├── online_retail_II.xlsx
├── ebay_rfm_analysis.ipynb
```

---

## Environment & Tools

- Programming Language: Python  
- Environment: Jupyter Notebook  
- Visualization: Seaborn, Matplotlib  
- Reporting: Canva (coming soon)
