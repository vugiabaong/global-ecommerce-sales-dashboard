# Global E-commerce Sales Dashboard

## 1. Project Overview

This project presents a Power BI dashboard designed to analyze global e-commerce sales performance across categories, regions, customer segments, discounts, shipping costs, and profitability.

The dashboard uses a transaction-level dataset of 2,000 orders from 2023 to 2025 across 20 countries, 5 regions, and 4 product categories. The main focus is to evaluate not only revenue performance, but also margin quality and potential profitability risks.

## 2. Business Objective

The objective of this dashboard is to support e-commerce performance monitoring by answering the following questions:

* Which product categories are the main revenue and profit drivers?
* Which regions and customer segments contribute most to business performance?
* How do discounts and shipping costs affect profitability?
* Which categories or order groups may require pricing, promotion, or cost optimization?

## 3. Tool Used

This project was built entirely in Power BI Desktop, including data import, data modeling, measure creation, and dashboard visualization.

## 4. Dashboard Preview

### Overview

The overview page summarizes total sales, total profit, quantity sold, profit margin, and overall business performance.

![Overview Dashboard](images/overview.png)

### Product & Category

This page compares category-level sales, profit, margin, and product performance to identify both revenue drivers and margin opportunities.

![Product and Category Dashboard](images/product-category.png)

### Region & Segment

This page analyzes sales and profitability across regions and customer segments to understand where the business performs strongest.

![Region and Segment Dashboard](images/region-segment.png)

### Discount & Profitability

This page reviews the relationship between discount levels, profit margin, and negative-margin orders.

![Discount and Profitability Dashboard](images/discount-profitability.png)

## 5. Key Business Insights

### Furniture is the main revenue engine, but margin control is still important

Furniture contributes approximately 52.9% of total sales and 51.1% of total profit, making it the most important category in terms of business scale. However, its profit margin is around 31.7%, slightly below the overall margin of 32.8% and lower than Technology and Clothing & Accessories.

This suggests that Furniture should remain a core category for revenue growth, but discounting, shipping cost, and product-level profitability need to be monitored carefully.

### Clothing & Accessories is a margin opportunity

Clothing & Accessories contributes only around 14.3% of total sales but delivers around 16.4% of total profit, with the highest category margin at approximately 37.6%.

From an e-commerce perspective, this category can be treated as a margin-enhancing category. It may be suitable for cross-selling, bundled offers, and targeted campaigns because it contributes stronger profitability despite a smaller revenue base.

### Office Supplies shows weak unit economics

Office Supplies contributes only around 4.0% of total sales and 2.1% of total profit, with the lowest category margin at approximately 17.1%.

This category also has a high shipping-cost burden relative to sales, with shipping cost equal to roughly one-third of category sales. Most negative-margin orders also come from Office Supplies, indicating that low item value, shipping cost, and discounting may be eroding profitability.

### Europe and North America are the strongest regional markets

Europe and North America together account for more than half of total sales and profit. They also show healthier margins compared with smaller regions such as Middle East & Africa and South America.

This indicates that these two regions are the most commercially attractive markets for scaling campaigns, while smaller regions may require more careful review of logistics cost, pricing, and promotion efficiency.

### Discounting has a clear impact on margin performance

Profit margin declines as discount levels increase. Orders with no discount show the strongest margin, while orders with discounts between 21% and 30% have the weakest margin.

This suggests that discounts should not be used only to increase sales volume. Promotion decisions should be tied to margin thresholds, average order value, and category-level profitability.

### Corporate customers generate lower margin despite higher discount exposure

The Corporate segment contributes meaningful sales volume, but it has the lowest margin among the three customer segments. It also receives a higher average discount compared with Consumer and Home Office segments.

This suggests that Corporate promotion strategy should be reviewed to ensure that higher discounts are justified by order value, repeat purchase potential, or strategic customer value.

## 6. Business Recommendations

### Protect Furniture as the core revenue category

Furniture should remain a priority category because of its strong contribution to both sales and profit. However, the business should monitor margin by product, especially for items with high shipping cost or frequent discounting.

### Use Clothing & Accessories to improve profitability

Clothing & Accessories can be used as a margin-supporting category. The business can promote this category through cross-selling, product bundles, or personalized recommendations to improve overall profit mix.

### Redesign the Office Supplies strategy

Office Supplies should not be scaled aggressively without improving its unit economics. Recommended actions include setting minimum order values, bundling low-ticket items, reviewing shipping thresholds, and reducing discounts on products with weak margins.

### Set discount guardrails by category

Discounts should be managed based on category margin rather than applied broadly. Higher discount levels should require a clear business reason, such as increasing basket size, clearing inventory, or acquiring high-value customers.

### Prioritize high-performing regions while reviewing cost-heavy markets

Europe and North America should be prioritized for growth campaigns due to their stronger revenue and margin performance. For Asia Pacific, South America, and Middle East & Africa, further analysis should focus on logistics cost, pricing, and market-level promotion efficiency.

## 7. Dashboard File

The full interactive Power BI report is available in this repository:

`global_ecommerce_sales_dashboard.pbix`
