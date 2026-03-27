# Week 8: Grouping, Aggregation & Summary Analysis

In this Week 8 project, I focused on extracting business intelligence from the supply chain dataset using **Pandas GroupBy**, aggregation functions, and pivot tables. This week was about moving beyond individual records to summarize data across suppliers, products, and time periods, revealing actionable insights for decision-making.

Grouping and aggregation allowed me to see patterns at scale—identifying top-performing suppliers, profitable product categories, and trends across months.

![Week 8 Intro](https://github.com/R887645/TDI-Python-Learning-Week-8-Project/blob/main/Intro.png?raw=true)

---

## Key Skills Practiced

- Grouping data with `.groupby()` on single and multiple columns
- Applying aggregation functions (`sum`, `mean`, `count`, `min`, `max`, `std`)
- Using named aggregations for clarity in results
- Creating pivot tables for cross-dimensional analysis
- Performing multi-level grouping to answer complex business questions

---

## What I Implemented

### 1. Basic GroupBy Analysis
Grouped data by `supplier_name` to calculate:

- Total orders
- Total cost
- Average, minimum, and maximum cost

Sorted results by total cost (descending).

### 2. Multi-Column Grouping
Grouped by `supplier_name` and `product_category` simultaneously to:

- Count orders
- Calculate average cost
- Summarize total quantity
- Identify the most profitable supplier-category combinations

### 3. Multiple Metrics with Named Aggregations
Used `.agg()` with named aggregations to calculate:

- `total_orders` (count)
- `avg_cost` (mean)
- `std_cost` (standard deviation)
- `min_cost` and `max_cost`

Displayed the top 3 suppliers by volume.

### 4. Pivot Tables
Created pivot tables to reveal cross-dimensional insights:

- Suppliers vs product categories (`average cost` as values)
- Product categories vs months (`total quantity` as values)

Identified cheapest suppliers per category and highest-volume product-month combinations.

### 5. Multi-Level Analysis
Performed advanced grouping to answer complex questions:

- On-time delivery rate by supplier
- Average order value by product category and delivery status
- Delivery time trends by month

Built a supplier performance scorecard with multiple metrics.

---

## Reflection

This project showed me how grouping and aggregation transform engineered data into business intelligence. By summarizing across dimensions, I uncovered insights that raw records could not reveal.

Key findings included:

- The top suppliers driving the highest order volumes and costs
- The most profitable product categories
- Seasonal and delivery performance trends highlighting operational strengths and weaknesses

Overall, Week 8 helped me move from data transformation into actionable analysis, setting the stage for visual storytelling with Matplotlib in Week 9.

---

## View the Full Project

🔗 [View my Week 8 full project on GitHub](https://github.com/R887645/TDI-Python-Learning-Week-8-Project)
