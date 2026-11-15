
# E-Commerce Supply Chain & Logistics Analytics

An end-to-end business analytics project developed using **Microsoft Excel and Power BI** to analyze e-commerce order fulfillment, delivery performance, logistics costs, warehouse efficiency, and courier partner performance.


## 1. Project Overview

This project focuses on analyzing an e-commerce supply chain dataset covering the complete year 2025.

The objective is to evaluate operational performance across the order fulfillment and logistics process, identify delivery delays, monitor cancellations and returns, analyze logistics expenses, and compare warehouse and courier partner performance.

The project combines:

- **Microsoft Excel:** Data preparation, formula-based analysis, PivotTables, KPI calculations, dashboards, and validation.
- **Power BI:** Interactive dashboards, business performance reporting, and visual analysis.

The analysis helps understand supply chain operations and identify areas that require operational improvement.

## 2. Business Objectives

- Analyze total order volume and unique orders.
- Monitor order fulfillment, cancellation, and return rates.
- Evaluate on-time and delayed delivery performance.
- Analyze monthly delivery trends and logistics efficiency.
- Compare shipping modes and delivery zones.
- Evaluate warehouse and courier partner performance.
- Monitor shipping, handling, and reverse logistics costs.
- Analyze net revenue and gross profit.

## 3. Tools & Technologies

| Tool | Application |
|---|---|
| Microsoft Excel | Data cleaning, formulas, KPI calculations, PivotTables, charts, dashboards |
| Power BI Desktop | Interactive dashboards, KPI cards, visualizations, slicers |
| Excel Analysis | Order, logistics, warehouse, and courier performance |
| Business Analytics | Operational performance monitoring and business insights |

## 4. Dataset Information

| Dataset Details | Information |
|---|---|
| Dataset Period | January – December 2025 |
| Raw Data Records | 20,450 |
| Cleaned Data Records | 20,000 |
| Original Columns | 39 |
| Cleaned Columns | 44 |
| Unique Orders | 13,740 |

The dataset contains information related to:

- Order IDs and Order Item IDs
- Order dates and order status
- Product details and categories
- Customer city, state, and PIN code
- Warehouse information
- Courier partners and shipping modes
- Dispatch and delivery dates
- Delivery status and delay information
- Return details and reasons
- Shipping, handling, and product costs
- Revenue, gross profit, and payment information

## 5. Data Cleaning & Preparation

The Excel workbook follows a Raw Data to Clean Data workflow.

**Data Preparation Process:**

1. Imported the original dataset into Excel.
2. Maintained the original records in the Raw_Data sheet.
3. Prepared the Clean_Data sheet containing 20,000 records.
4. Added additional helper fields for operational analysis.
5. Used the cleaned dataset for all analysis sheets.
6. Created a Validation_Report to check record counts and financial calculations.

**Data Validation:**

- Total cleaned order items: 20,000
- Unique orders: 13,740
- Items that reached customers: 18,387
- Dispatched items: 18,986
- Net revenue reconciliation: Passed
- Total logistics cost reconciliation: Passed
- Gross profit reconciliation: Passed

## 6. Excel Workbook Structure

The Excel workbook contains 8 worksheets.

| Sheet Name | Description |
|---|---|
| Raw_Data | Original source dataset |
| Clean_Data | Cleaned dataset used for analysis |
| Order_Analysis | Order volume, fulfillment, cancellation, returns, and revenue analysis |
| Logistics_Analysis | Delivery performance, shipping modes, delivery zones, and logistics costs |
| Warehouse_Courier_Analysis | Warehouse efficiency and courier partner performance |
| Pivot_Analysis | Pivot-based business analysis and summaries |
| Dashboard | Main supply chain KPI dashboard |
| Validation_Report | Data count and financial validation checks |

## 7. Power BI Dashboard

The Power BI report contains four interactive pages.

### Page 1: Executive Overview
- Overall supply chain performance
- Total order items and unique orders
- Net revenue and gross profit
- Delivery success rate
- On-time delivery rate
- Delayed deliveries
- Total logistics cost

### Page 2: Delivery & Logistics Analysis
- Monthly delivery performance
- On-time and delayed delivery analysis
- Shipping mode comparison
- Delivery zone performance
- Logistics cost analysis

### Page 3: Product & Order Analysis
- Product category performance
- Order volume analysis
- Order status distribution
- Revenue and return analysis

### Page 4: Business Insights & Recommendations
- Key operational findings
- Delivery and logistics improvement areas
- Warehouse and courier performance observations
- Business recommendations

## 8. Key Performance Indicators (KPIs)

The following KPIs are taken from the Excel Dashboard and supporting analysis sheets.

| KPI | Result |
| Total Order Items | 20,000 |
| Total Unique Orders | 13,740 |
| Fulfillment Rate | 91.94% |
| Cancellation Rate | 7.22% |
| Order Return Rate | 5.68% |
| Dispatched Items | 18,986 |
| On-Time Delivery Rate | 77.78% |
| Late Delivery Rate | 22.22% |
| Delayed Deliveries | 4,085 |
| Average Shipping Days | 2.56 Days |
| Net Revenue | ₹3,90,09,156 |
| Gross Profit | ₹1,43,89,328 |
| Total Logistics Cost | ₹21,66,159 |

## 9. Key Business Insights

### Order & Fulfillment Analysis

- The business processed 20,000 order items across 13,740 unique orders.
- Overall fulfillment rate was 91.94%.
- Cancellation rate was 7.22%.
- Return rate was 5.68%.

### Delivery & Logistics Analysis

- Overall on-time delivery rate was 77.78%.
- A total of 4,085 deliveries were delayed.
- October recorded an on-time delivery rate of 69.30%.
- November recorded an on-time delivery rate of 70.19%.
- Average shipping time was 2.56 days.

### Shipping Mode Analysis

- Express handled 7,799 shipments.
- Standard handled 8,285 shipments.
- Same Day handled 2,316 shipments.
- Surface handled 1,600 shipments.
- Same Day had the lowest average shipping time at approximately 0.78 days.

### Warehouse & Courier Analysis

- The network includes 5 fulfillment hubs and 5 courier partners.
- Blue Dart recorded the highest on-time delivery rate at 82.18%.
- Xpressbees recorded the lowest on-time delivery rate at 70.15%.
- Warehouse and courier performance was compared using shipment volume, delivery performance, shipping time, and logistics spending.

### Financial Analysis

- Full order value: ₹4,48,72,335
- Net revenue: ₹3,90,09,156
- Product cost: ₹2,24,53,669
- Total logistics cost: ₹21,66,159
- Gross profit: ₹1,43,89,328

## 10. Business Recommendations

Based on the analysis:

1. Focus on improving on-time delivery performance.
2. Investigate the reasons behind higher delays during October and November.
3. Monitor delivery performance in low-performing delivery zones.
4. Review courier partner performance and shipping lane efficiency.
5. Monitor logistics expenses across warehouses and shipping modes.
6. Improve return and cancellation monitoring to protect realized revenue.

## 11. Project Files

This repository includes:

- Excel workbook with Raw Data, Clean Data, analysis sheets, PivotTables, Dashboard, and Validation Report.
- Power BI report with four interactive dashboard pages.
- README documentation explaining the project and its business findings.

## 12. How to Use This Project

1. Download or clone this repository.
2. Open the Excel workbook using Microsoft Excel.
3. Open the PBIX file using Power BI Desktop.
4. Explore the Excel analysis sheets and dashboard.
5. Navigate through the four Power BI report pages.
6. Use available slicers to explore the interactive report.

## 13. Author

**Vikram Dhakad**

Aspiring Data Analyst|MIS Executive

**Technical Skills:** Microsoft Excel, Power BI, Data Cleaning, Data Analysis, KPI Reporting, Dashboard Development, and Business Analytics.

---
