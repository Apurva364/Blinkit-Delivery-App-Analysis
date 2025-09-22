# Blinkit-Delivery-App-Analysis

1. Project Title
Blinkit Delivery App Analysis
A dynamic, interactive Power BI dashboard built to explore Blinkit’s quick-commerce operations—focusing on delivery performance, order trends, customer behavior, and operational efficiency of Blinkit’s grocery delivery app.

2. Short Description / Purpose

The Blinkit Delivery App Analysis dashboard is a visual Power BI report designed to help stakeholders monitor and understand Blinkit’s delivery app metrics, such as speed, order volume, regional performance, and revenue streams. It exists to enable data-driven decisions for improving delivery times, customer satisfaction, and profitability.

3. Tech Stack

List of technologies used to build the Blinkit dashboard:

📊 Power BI Desktop – primary platform for building the report.

📂 Power Query – for cleaning, shaping, and transforming data (orders, delivery logs, customer feedback, etc.).

🧠 DAX (Data Analysis Expressions) – for calculated measures like average delivery time, late delivery rate, revenue per order, etc.

📝 Data Modeling – establishing relationships among tables such as Orders, Deliveries, Dark Stores, Customers, Delivery Partners, Products.

📁 File Format – .pbix for development; exported visuals (.png, .jpeg) or Power BI service dashboards for sharing.

4. Data Source

More info on where the data comes from and how it’s structured:

Source: Blinkit’s internal operational databases (orders, deliveries), partner/vendor systems, app usage logs, and customer feedback data.

Data Structure: Multiple tables such as:
• Orders (order_id, customer_id, order_time, delivery_time, order_value, city/area)
• Delivery Partners (partner_id, region, performance metrics)
• Dark Stores Inventory / Location (store_id, stock levels, city/zone)
• Customer Feedback / Ratings (order_id, rating, comments)
• Costs & Fees (delivery fees, commissions, markup)

Granularity: Ideally minute‐level timestamps for orders & deliveries; location granularity (city → zone → pincode); daily/weekly/monthly aggregations for trends.

5. Features / Highlights

Business Problem
Blinkit promises ultra-fast deliveries (10-25 mins) but faces challenges in maintaining consistent delivery times, managing costs, ensuring high customer satisfaction, and optimizing dark store and delivery partner efficiency. Decision-makers need insights across multiple dimensions to identify bottlenecks and improvement areas.

Goal of the Dashboard
To deliver an interactive visual tool that:
• Enables monitoring of delivery performance across geographies and time.
• Helps compare order volume, value, and customer satisfaction by region, time of day, product category.
• Identifies inefficiencies in operations (delivery delays, late deliveries, partner underperformance).
• Assesses revenue and cost drivers (commissions, delivery fees, product markups) to support profitability.

Walkthrough of Key Visuals

• Top KPIs (Top Left) – e.g. Total Orders Delivered, Average Delivery Time, % Late Deliveries, Average Customer Rating.
• Orders & Revenue Trend Line – shows orders and revenue over time (daily, weekly, monthly).
• Delivery Time Distribution – histogram showing how many deliveries fall into different time bands (e.g. <10 min, 10-20 min, >20 min).
• Regional / Zone Map / Heat Map – order density, average delivery time or late delivery rate by city or zone.
• Delivery Partner Performance – bar charts showing on-time rate, cancellations, deliveries per partner.
• Category & Order Value Analysis – breakdown of orders by product categories; average order values across categories.
• Cost & Fee Breakdown – visualization of revenue vs cost (delivery fees, commissions, markups), margin by product / location.
• Customer Satisfaction / Ratings – trend of ratings over time; ratings by region or delivery time buckets; feedback counts.

Business Impact & Insights
• Operational Efficiency: Identify zones or times of day where delivery delays are high to re-allocate resources or adjust staffing/dark store locations.
• Profitability Optimization: Understand which product categories or zones are generating margins vs loss, to adjust pricing, delivery charges or fee structure.
• Customer Satisfaction Improvement: Correlate delivery speed and customer feedback to improve service quality, reduce complaints.
• Strategic Expansion: Use volume and demand insights to plan new dark store locations or expand in certain cities or zones.

6. Screenshots / Demos
   Show what the dashboard looks like.
   Example:
• Profitability Optimization: Understand which product categories or zones are generating margins vs loss, to adjust pricing, delivery charges or fee structure.
• Customer Satisfaction Improvement: Correlate delivery speed and customer feedback to improve service quality, reduce complaints.
• Strategic Expansion: Use volume and demand insights to plan new dark store locations or expand in certain cities or zones.
