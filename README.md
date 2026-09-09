# blinkit-sales-analytics-powerbi
Interactive Power BI dashboard analyzing $1.20M in Blinkit sales data across outlet types and locations.
# 🛒 Blinkit Sales & Inventory Performance Analysis

An end-to-end Power BI Business Intelligence project analyzing **$1.20M** in revenue across 8,500+ items to identify operational bottlenecks, evaluate outlet-level performance, and uncover margin optimization strategies.

---

## 📊 Executive Dashboard Overview

![Blinkit Dashboard](Screenshot%202026-09-09%20000823.png)

---

## 💼 Business Problem & Context
Quick-commerce platforms operate on thin margins where inventory placement and outlet efficiency dictate profitability. This project evaluates Blinkit's operational data across different store tiers and product categories to answer critical business questions:
- Which outlet format yields the highest revenue density?
- Why do smaller grocery setups struggle with low ticket sizes?
- Where should dark-store capacity be expanded to maximize ROI?

---

## 🔑 Key Metrics (KPIs)
- **Total Revenue:** $1.20M
- **Average Ticket Size (AOV):** $141
- **Items Transacted:** 8,523 items
- **Average Customer Rating:** 3.9 / 5.0

---

## 📈 Strategic Insights & Analysis

### 1. The Dominance of Supermarket Formats
- **Supermarket Type 1** is the primary revenue driver, generating **$787.55K** (over 65% of total sales).
- In contrast, smaller **Grocery Stores** generate only **$151.94K** with low item visibility (0.10), indicating underutilized inventory turnover.

### 2. Geographic Disparity: Tier 3 Outperforming Tier 1
- **Tier 3 cities** generated the highest sales (**$472K**), significantly outpacing Tier 2 ($393K) and Tier 1 ($336K).
- Tier 3 customers show a strong appetite for bulk and recurring orders, creating an expansion opportunity for localized inventory fulfillment.

### 3. Category Contribution
- **Fruits & Vegetables** and **Snack Foods** lead transaction volumes (~1.2K items each).
- Fat content distribution shows strong regular-fat adoption ($507.90K) compared to low-fat variations.

---

## 💡 Actionable Business Recommendations
1. **Drive Average Order Value (AOV):** Implement automated bundle recommendations pairing high-frequency essentials (Fresh Produce) with high-margin impulse items (Chocolates/Health Foods) to raise AOV from $141 to $170+.
2. **Reallocate Shelf Space in Grocery Formats:** Downsize slow-moving SKUs in small formats and allocate 70%+ capacity to high-velocity staples.
3. **Double Down on Tier 3 Dark Stores:** Prioritize logistics investments and dark store footprint in Tier 3 micro-markets where demand velocity is fastest.

---

## 🛠️ Technical Stack & Implementation
- **BI Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Star Schema architecture linking fact sales with outlet and item dimensions.
- **DAX Functions:** Custom measures for dynamic filtering, total sales calculation, and weighted ratings.
- **Data Cleansing:** Power Query (type casting, missing value imputation, text standardization).

---

## 📂 Repository Contents
- `Screenshot 2026-09-09 000823.png`: High-resolution dashboard view.
- `Dashboard.png.pbix`: Complete Power BI report with interactive data model and DAX measures.
-
