## 🍕 Pizza Sales Analytics Dashboard

### 1. Project Title / Headline

A dynamic and interactive Power BI dashboard built to analyze pizza sales performance, customer ordering behavior, revenue trends, product popularity, and sales distribution across categories and sizes. The dashboard enables business stakeholders to monitor KPIs, identify best-selling products, and make data-driven decisions to improve restaurant profitability.

### 2. Short Description / Purpose

The Pizza Sales Analytics Dashboard is a comprehensive Power BI report designed to transform raw transaction data into meaningful business insights. It provides a detailed view of sales performance, customer ordering patterns, product demand, and revenue contribution across pizza categories and sizes, helping restaurant managers optimize inventory, pricing strategies, and menu offerings.

### 3. Tech Stack

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Main data visualization platform used for dashboard creation and reporting.

• 📂 Power Query – Used for data extraction, cleaning, transformation, and preparation before analysis.

• 🧠 DAX (Data Analysis Expressions) – Implemented calculated measures, KPIs, and dynamic business metrics.

• 🗄️ SQL – Used for KPI calculations and sales analysis including revenue trends, best-selling pizzas, category performance, and order metrics.

• 📝 Data Modeling – Built relationships and optimized the data structure for efficient reporting and filtering.

• 📁 File Formats – .csv as the primary dataset, .pbix for dashboard development, and .png for dashboard previews.

### 4. Data Source

Source: Pizza Sales Transaction Dataset

The dataset contains detailed pizza order transactions, including:

Order IDs

Order Date

Pizza Names

Pizza Categories

Pizza Sizes

Quantity Sold

Unit Price

Total Price

Sales Revenue

The dataset captures customer purchasing behavior and product performance across different periods, enabling detailed sales and profitability analysis.

### 5. Features / Highlights
• Business Problem

Restaurant businesses handle thousands of sales transactions every month. Without a centralized analytical solution, it becomes difficult to understand customer preferences, monitor sales performance, identify top-performing products, and optimize inventory planning.

Key business questions include:

What is the total revenue generated?

Which pizzas generate the highest sales?

Which pizza categories contribute the most revenue?

What pizza sizes are preferred by customers?

Which days and months experience the highest order volume?

Which menu items perform poorly and may require improvement?



#### • Goal of the Dashboard

To deliver an interactive analytical solution that:

Monitors restaurant sales performance in real time.

Tracks revenue, orders, and product demand.

Identifies top-performing and underperforming menu items.

Analyzes customer purchasing trends by category and size.

Supports inventory management and pricing decisions.

Enables data-driven business growth strategies.


#### • Walkthrough of Key Visuals
Dashboard 1: Pizza Sales Overview Dashboard
Key KPIs (Top Row)

The dashboard presents five key performance indicators that provide an instant overview of business performance:

Total Revenue: $817.86 :
Total Orders: 21,350 :
Average Order Value: $38.31 :
Total Pizzas Sold: 49,574 :
Average Pizzas per Order: 2.32 :
Pizza Category Filter Panel

An interactive slicer allows users to filter all dashboard visuals by pizza category, enabling focused analysis of specific product segments.

• Date Range Filter : Users can dynamically analyze sales performance across custom time periods by selecting start and end dates.

• Daily Trend for Total Orders (Column Chart) : Displays order volume across weekdays, helping identify peak business days.

##### Key Insight: Friday records the highest number of orders, indicating strong weekend demand.

• Monthly Trend for Total Orders (Line Chart): Tracks monthly ordering patterns throughout the year.

##### Key Insight: July records the highest order volume, while September and October experience comparatively lower demand.

• Revenue by Pizza Category (Donut Chart): Shows revenue contribution across pizza categories:

Classic :
Supreme :
Chicken :
Veggie 

This helps determine which product categories generate the highest business value.

• Revenue by Pizza Size (Donut Chart): Analyzes customer purchasing preferences across pizza sizes:

Large :
Medium :
Regular :
X-Large :
XX-Large

##### Key Insight: Large-sized pizzas contribute nearly 46% of total revenue, making them the most preferred size.

• Revenue by Pizza Category (Bar Chart): Ranks pizza categories by total revenue generated.

##### Key Insight: Classic pizzas generate the highest revenue, followed closely by Supreme pizzas.
