# Inventory Management Analysis for Surya Automobile Parts

## 📌 Project Overview

This project focuses on diagnosing and resolving inventory management inefficiencies for **Surya**, a company dealing in automobile parts and repair services. Through in-depth data analysis, the objective is to identify inventory issues—especially **overstocking** and **slow-moving items**—and develop actionable strategies to improve inventory turnover, reduce holding costs, and optimize procurement and forecasting practices.


## 📊 Problem Statement

Surya has been facing issues related to **stock accumulation**, resulting in **blocked working capital** and **inefficient space utilization**. This project aims to:

* Analyze stock movement patterns
* Identify overstocked and slow-moving items
* Diagnose root causes (e.g., high opening balances, procurement inefficiencies)
* Prioritize clearance and deadstock risk
* Recommend targeted, data-driven interventions


## 🔍 Key Analyses Performed

### 1. **Rate Distribution Analysis**

* Identified variability in procurement rates
* Outliers and inconsistent rate patterns suggest procurement inefficiencies

### 2. **ABC Analysis**

* Categorized items into A (high-value), B (medium), and C (low-value) groups based on closing value
* Found that a small number of items contribute to most of the inventory value

### 3. **Overstocked vs. Regular Items Comparison**

* Items with outflow < 30% of inflow marked as overstocked
* Overstocked items had \~4x higher closing quantity and \~2x higher closing value than regular items

### 4. **Clearance Priority & Deadstock Risk**

* Developed scores to prioritize overstock clearance and assess deadstock risk
* Visualized critical items using a dual-axis scatter plot

### 5. **Root Cause Analysis of Overstocking**

* Segregated items based on high opening balance and/or excessive inwards
* Found 67.1% of overstock caused by high opening balances


## 📈 Visualizations

* **Bar Charts**: Overstocked vs. Regular Items (Quantity & Value)
* **Scatter Plots**:

  * Clearance Priority Score vs Deadstock Risk Score
  * Opening Balance Contribution vs Inwards-Outwards Ratio
* **Pie Chart**: Root Cause Contribution to Overstocking


## ✅ Recommendations

1. **Optimize Pricing Strategies**
   Adjust pricing of slow-moving and high-cost items dynamically based on demand trends to improve turnover and release working capital.

2. **Manage High-Value Items Efficiently**
   Prioritize the movement and management of high-value items using techniques like ABC categorization to reduce holding costs and improve liquidity.

3. **Implement Targeted Clearance Strategies**
   Use Clearance Priority and Deadstock Risk Scores to expedite clearance of financially burdensome and movement-prone items.

4. **Refine Procurement Practices**
   Avoid bulk ordering low-demand items and revise procurement schedules to better match demand patterns.

5. **Enhance Forecasting Accuracy**
   Use historical trends and advanced forecasting models to improve demand prediction and avoid unnecessary stock accumulation.


## 🛠️ Tools & Technologies

* **Python**: Pandas, NumPy, Matplotlib, Seaborn, Sklearn
* **Google Sheets**: Score tracking and item-wise comparisons
* **Excel**: Preliminary data checks and visualization drafts


## 📂 Project Structure

```
├── notebooks/
│   └── inventory_analysis.ipynb
├── reports/
│   ├── Final Term Report.pdf
│   ├── Mid Term Report.pdf
│   ├── Project Presentation.pdf
│   └── Proposal Report.pdf
└── README.md
```


## 📌 Outcomes

* Identified key contributors to inventory inefficiencies
* Created actionable scoring systems for prioritizing stock clearance
* Provided practical and data-supported recommendations
* Empowered Surya’s decision-making with visual diagnostics and procurement strategies

