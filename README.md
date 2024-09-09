# Adventure Works Dashboard

## Project Overview

In the current business environment, where data plays a crucial role, the skill to harness data for informed decision-making sets professionals apart. To highlight my expertise in Power BI and data analytics, I utilized the Adventure Works dataset — a sample dataset centered around a bicycle company — to create dashboards that deliver comprehensive insights into sales trends, customer patterns, and product information. This project underscores my abilities in data storytelling, applying DAX formulas, and creating dynamic reports.

I dedicated over 16 hours to mastering the content and creating this interactive dashboard. The project was developed as part of a comprehensive Udemy course. You can find the link to the original course project [here](https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop/)

## Technologies Used

- Power BI
- DAX (Data Analysis Expressions) language
- Excel


## Power BI Skills Acquired

- Identifying key questions before initiating a project
- Creating calculated columns
- Crafting measures using DAX
- Data modeling techniques
- Utilizing Bookmarks for toggling between visuals
- Implementing page navigation with buttons
- Avoiding division by zero errors using the DIVIDE function
- Creating date tables with M language
- Integrating KPI indicators
- Applying conditional formatting with icons or colors
- Data validation strategies
- Power BI services
- Publishing reports on Power BI services
- And much more 😅

## Key Business Concepts

- Revenue
- Profit
- Returns
- Customer
- etc

## Data Model and Table Relationships

This project is built on a robust data model that integrates multiple related tables: Sales Data, Customer Lookup, Product Lookup, Product Categories Lookup, and Calendar Lookup.

- The Sales Data table serves as the core, capturing detailed transaction records. 

- The Customer Lookup table offers demographic and behavioral insights for each customer. 

- The Product Lookup and Product Categories Lookup tables support analysis at both the product and category levels, linking product details to sales data. 

- The Calendar Lookup table facilitates time-based analysis, essential for identifying trends and patterns. 

- These interconnected tables allow for smooth integration and multi-dimensional analysis, leading to precise insights and impactful visualizations

### Data Model:

Data modeling is the foundation of any report, directly impacting its performance. In this project, we used the below snowflake schema for data modeling.

## Importing Data into Power BI

All the required data for this dashboard are located in the Course Provide CSV files.


## Project Walkthrough:

### 1. Executive Dashboard

<img src="https://github.com/SandeepanBhattacharyya/Croma-India-Product-Wise-Sales-Report/blob/main/fiscal_date.png" class="center">

- The Executive Dashboard provides a high-level summary of Adventure Works' financial status and operational efficiency, focusing on the most important KPIs aligned with the company’s strategic goals.

**Key Features:**

- **Revenue:** Displays total revenue for the selected period and compares it to the previous month to assess growth.

- **Profit:** Reflects total profit, giving insight into the effectiveness of cost management.

- **Orders:** Shows the total number of orders, offering a perspective on market demand.

- **ROI %:** Calculates return on investment by comparing profit to costs, highlighting spending efficiency.

- **Monthly Trends:** A line chart illustrating trends in revenue and orders over time, revealing seasonal patterns and growth trajectories.

- **Top 10 Products:** A table listing the top 10 products by orders, revenue, profit, and return rate, helping to identify top performers and those with high return rates that may need attention.

- **Orders by Category:** A pie chart showing the distribution of orders across different product categories (Accessories, Bikes, Clothing), providing insight into category popularity.

- **Profit by Country and Category:** A bar chart breaking down profit by country and product category, offering a view of geographic performance and key revenue sources.

This dashboard facilitates swift decision-making by offering a clear, concise view of critical business metrics. For instance, a high ROI percentage suggests resource efficiency, while high return rates highlight potential areas for product quality improvement. Understanding the geographic distribution of profits helps tailor marketing efforts and expansion plans.

### 2. Product Detail

<img src="https://github.com/SandeepanBhattacharyya/Croma-India-Product-Wise-Sales-Report/blob/main/fiscal_date.png" class="center">

The Product Detail Dashboard offers an in-depth analysis of product performance, with a focus on returns and profitability. This dashboard helps pinpoint the products that are driving sales and those that may require improvements.

**Key Features:**

- **Orders Return:** Tracks the total number of returned orders, shedding light on customer satisfaction and potential product quality issues.

- **Average Cost per Return:** Measures the financial impact of returns, which can influence overall profitability.

- **Revenue and Return by Category:** Displays pie charts that compare revenue and return distribution by category, enabling an analysis of sales versus returns.

- **Top 10 Returned Products:** A bar chart that highlights products with the highest return rates, indicating areas that may need quality improvements.

- **Orders by Month and Category:** A line chart that shows monthly order trends by category, assisting in inventory management and seasonal planning.

- **Subcategory Products:** A table presenting subcategory orders, revenue, profit, and return rate, offering a more granular view of product performance.

- **% Lost to Returns:** This KPI highlights the percentage of revenue lost due to returns, helping the company assess the financial impact of returns on overall sales.

- **Return Rate**: Displays the return rate percentage, indicating the proportion of total sales that were returned and providing insight into potential product issues or misalignment with customer expectations.

This dashboard is crucial for identifying trends in product returns and offers actionable insights for reducing return rates and enhancing product quality. For example, a high return rate for a particular item might suggest a need for improved quality control or clearer product descriptions. Understanding the percentage of revenue lost to returns is essential for assessing the impact on overall sales, while focusing on high-return products can guide strategies to boost customer satisfaction and minimize losses.

### 3. Customer Detail

<img src="https://github.com/SandeepanBhattacharyya/Croma-India-Product-Wise-Sales-Report/blob/main/fiscal_date.png" class="center">

The Customer Detail Dashboard offers a thorough analysis of customer demographics, purchasing habits, and retention rates, helping the company better understand its customer base and refine marketing strategies. Meanwhile, the Geographic Dashboard visually maps out sales distribution across various regions, highlighting strong markets and uncovering growth opportunities in areas that are underperforming.

**Key Features:**

- **Unique Customers:** Displays the total number of unique customers, indicating the size of the customer base.

- **Avg per Customer:** Shows the average spending per customer, emphasizing customer value.

- **Purchase Frequency:** Tracks the average number of purchases per customer, providing insight into customer engagement levels.

- **Customer Segmentation:** Visualizes customer distribution by country, income level, and gender, helping to identify key segments for targeted marketing efforts.

- **Monthly New Customers:** A line chart tracking the number of new customers acquired each month, reflecting the impact of marketing campaigns.

- **Monthly Churned vs. Retained Customers:** A stacked area chart showing trends in customer retention and churn, offering insights into customer loyalty and the effectiveness of retention strategies.

By analyzing customer demographics and behaviors, this dashboard helps the company pinpoint opportunities for targeted marketing and customer retention initiatives. For instance, identifying customer segments with the highest churn rates can guide the development of more effective retention strategies.


