# Sales Data Analysis Project - README

## 📌 Project Overview
This project analyzes sales data to uncover key business insights, transform raw data into actionable intelligence, and create an interactive dashboard for stakeholders. The analysis covers sales performance across regions, channels, and sales teams, with visualizations to highlight trends and opportunities.

---

## 🛠️ Tools Used
- **Microsoft Excel**
- **PivotTables** for dynamic analysis
- **Data Visualization** (Charts, Conditional Formatting)
- **Dashboard Creation**


## 📂 Project Structure

### 1. Data Preparation
- Cleaned and standardized:
  - `sales_date` → Proper date format
  - `sales_value` → Numeric values
  - `sales_quantity` → Verified integers
- Handled missing data (imputed averages or removed invalid entries)

### 2. Key Metrics Calculated
| Metric | Formula | Result |
|--------|---------|--------|
| Total Sales | `=SUM(B2:B1001)` | $5038148.02 |
| Avg. Transaction | `=AVERAGE(B2:B1001)` | $5038.14802 |
| Total Units Sold | `=SUM(F2:F1001)` | 483300 |

### 3. Core Analysis
- **Top Performing Region**: [North America] (22% of total sales)
- **Most Effective Channel**: [Instores and Distribution] (both with 26% of total sales)
- **Best Salesperson**: [Salesperson ID 21] (995 sold Items)

### 4. Dashboard Features
- **Interactive Filters**: Region, Time Period, Product Category
- **Visualizations**:
  - Monthly Trend Line Chart
  - Regional Performance Heatmap
  - Channel Contribution Pie Chart
  - Top Performers Leaderboard

---

## 🔍 Key Findings
1. **Revenue Drivers**:
   - [North America] accounts for 29% of total sales
   - [August] shows positive seasonal uplift

2. **Improvement Opportunities**:
   - [Africa] is 19% below average
   - [Distributor Channel] conversion rate is 19% lower than others

3. **Recommendations**:
   - Reallocate resources to [North America Region]
   - Implement training for [Distributor Channel]
   - Expand [Instores and Direct Sales Channels] initiatives

---
