# Global E-commerce Sales Dashboard | Power BI Portfolio Project

## 1. Project Overview

This project analyzes a global e-commerce sales dataset using **Power BI** to understand revenue performance, profitability, product/category contribution, regional performance, customer segments, and promotion-related margin risks.

The main goal is to build a business-facing dashboard that helps answer:

- Which categories and products drive the highest revenue and profit?
- Which regions and customer segments contribute most to sales?
- How do discounts and shipping costs affect profitability?
- Which products should be scaled, monitored, or optimized?

> Status: Dashboard completed in Power BI. Current README includes preliminary analysis based on the dataset and dashboard structure.

---

## 2. Dataset Summary

| Item | Description |
|---|---|
| Dataset | Global E-commerce Sales |
| Rows | 2,000 orders |
| Columns | 15 fields |
| Period | 2023-01-02 to 2025-12-31 |
| Countries | 20 |
| Regions | 5 |
| Product categories | 4 |
| Products | 40 |

### Main Fields

- `Order_ID`
- `Order_Date`
- `Customer_Name`
- `Customer_Segment`
- `Country`
- `Region`
- `Product_Category`
- `Product_Name`
- `Quantity`
- `Unit_Price`
- `Discount_Percent`
- `Total_Sales`
- `Shipping_Cost`
- `Profit`
- `Payment_Method`

---

## 3. Tools Used

- **Power BI**: data modeling, DAX measures, dashboard design, interactive slicers
- **Power Query**: data type checking and transformation
- **CSV dataset**: raw sales data source
- **GitHub**: project documentation and portfolio presentation

---

## 4. Dashboard Pages

The Power BI report contains 4 pages:

### Page 1: Overview

Purpose: Give a quick business snapshot of overall sales performance.

Main visuals:

- KPI cards: Total Sales, Total Orders, Total Profit, Profit Margin, AOV, Total Quantity
- Monthly Sales & Profit Trend
- Category Revenue Overview
- Top 5 Products by Sales
- Sales by Region
- Customer Segment Revenue Mix

### Page 2: Product & Category

Purpose: Evaluate product and category performance.

Main visuals:

- Product ranking by sales and profit
- Product portfolio scatter plot
- Recommended Product Actions table
- Category Profitability matrix
- Product and category KPI cards

### Page 3: Region & Segment

Purpose: Compare business performance across regions, countries, and customer groups.

Main visuals:

- Regional Revenue and Margin Performance
- Country-level revenue/profit comparison
- Customer Segment Value Overview
- Customer Segment Strength by Region

### Page 4: Discount & Profitability

Purpose: Analyze how promotions and cost pressure affect margin.

Main visuals:

- Revenue and Margin by Promotion Level
- Category Margin Pressure Summary
- Promotion Risk by Product
- Loss-making Order Risk by Promotion Level
- KPI cards for Negative Margin Orders, Average Discount, Shipping Cost %

---

## 5. Key Metrics

| Metric | Value |
|---|---:|
| Total Sales | $484,559.34 |
| Total Profit | $158,872.32 |
| Profit Margin | 32.79% |
| Total Orders | 2,000 |
| Total Quantity | 7,115 |
| Shipping Cost % of Sales | 5.33% |
| Average Discount | 8.57% |
| Negative Margin Orders | 272 |

---

## 6. Preliminary Insights

### Insight 1: Furniture is the largest revenue driver, but not the most profitable category by margin.

Furniture generated the highest revenue at **$256.3K**, accounting for more than half of total sales. However, its profit margin was **31.7%**, lower than Technology and Clothing & Accessories.

This suggests that Furniture is important for revenue scale, but margin improvement should be monitored through discount control, shipping cost management, or product mix optimization.

### Insight 2: Clothing & Accessories has the strongest margin performance.

Clothing & Accessories generated **$69.4K** in sales with the highest category margin of **37.6%**. Although its revenue is smaller than Furniture and Technology, it is a strong profitability category.

This category could be used for margin-focused campaigns, cross-selling, or product expansion.

### Insight 3: Office Supplies has weak profitability.

Office Supplies contributed only **$19.4K** in sales and had the lowest profit margin at **17.1%**.

This indicates that Office Supplies may need a deeper review of pricing, discounting, shipping cost, or product assortment before further scaling.

### Insight 4: Europe and North America are the strongest regions.

Europe generated the highest revenue at **$137.0K**, followed closely by North America at **$133.9K**. North America had a slightly higher margin at **33.8%**.

These two regions should be prioritized for sales growth because they combine high revenue contribution with healthy profitability.

### Insight 5: Discounts create visible margin risk.

The dataset contains **272 negative-margin orders**. Since the dashboard includes promotion-level analysis, discount bands should be reviewed carefully to identify where promotions reduce profitability instead of creating valuable sales growth.

---

## 7. Business Recommendations

### 1. Protect and optimize Furniture revenue

Furniture is the main revenue driver, so the business should not simply reduce focus on this category. Instead, it should improve profitability by:

- Reviewing high-shipping-cost products
- Reducing unnecessary discounts
- Prioritizing best-performing furniture products
- Creating bundles or premium positioning for high-value products

### 2. Scale high-margin categories

Clothing & Accessories has the strongest margin performance. The business can use this category to improve overall profitability by:

- Promoting high-margin products
- Testing cross-sell campaigns with Furniture or Technology
- Highlighting best-selling products in seasonal campaigns

### 3. Review Office Supplies before scaling

Office Supplies currently has low revenue and low margin. Before investing more in this category, the business should:

- Identify products with low or negative margin
- Review discount strategy
- Compare shipping cost impact
- Consider removing or deprioritizing weak SKUs

### 4. Prioritize Europe and North America

Europe and North America should be treated as key markets because they generate the highest revenue. Recommended actions:

- Maintain strong product availability
- Run region-specific campaigns
- Compare customer segment behavior across these two regions
- Use these regions as benchmarks for lower-performing markets

### 5. Monitor promotion risk

Promotions should not be evaluated only by revenue. They should also be reviewed by:

- Profit margin
- Negative-margin order count
- Shipping cost %
- Average discount level

---

## 8. Dashboard Preview

> Add dashboard screenshots here after exporting them from Power BI.

### Overview Page

![Overview Dashboard](images/overview.png)

### Product & Category Page

![Product and Category Dashboard](images/product-category.png)

### Region & Segment Page

![Region and Segment Dashboard](images/region-segment.png)

### Discount & Profitability Page

![Discount and Profitability Dashboard](images/discount-profitability.png)

---

## 9. Suggested Repository Structure

```text
global-ecommerce-sales-dashboard/
│
├── README.md
├── global_ecommerce_sales.csv
├── global_ecommerce_sales_dashboard.pbix
│
└── images/
    ├── overview.png
    ├── product-category.png
    ├── region-segment.png
    └── discount-profitability.png
```

---

## 10. What I Learned

Through this project, I practiced:

- Building an end-to-end Power BI dashboard from raw CSV data
- Designing KPI cards and interactive dashboard pages
- Creating DAX measures for sales, profit, margin, AOV, discount, and negative-margin risk
- Translating dashboard findings into business insights and recommendations
- Presenting a data project in a GitHub portfolio format

---

## 11. Next Improvements

To improve this project further, I plan to:

- Add deeper customer segment analysis
- Compare year-over-year sales and profit trends
- Add product-level action logic with clearer business rules
- Improve dashboard storytelling and visual hierarchy
- Add more detailed documentation of DAX measures and data cleaning steps
