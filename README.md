# Infosys_Springboard_Virtual_Internship-7.0_Batch-1_Team-B

📊 Supply Chain Visibility & Optimization Dashboard

🚀 Project Overview

This project was completed as part of the Infosys Springboard Virtual Internship 7.0 by Team B (Group 1).

Supply Chain Visibility & Optimization Dashboard is an interactive business intelligence solution developed using Microsoft Power BI to analyze retail supply chain performance and provide actionable business insights. The project transforms raw retail supply chain data into an easy-to-understand, interactive seven-page dashboard covering sales, profitability, customer segments, regional performance, shipping operations, returns, discounting, and unit economics.

The dashboard is designed to improve supply chain visibility by helping business stakeholders monitor key performance indicators, identify operational bottlenecks, understand profitability patterns, evaluate shipping performance, and make faster data-driven decisions.

The project uses a structured analytics workflow covering data collection, data cleaning, transformation, data modeling, DAX-based calculations, dashboard development, testing, and business interpretation.

🗂️ Project Files

The repository contains the following project resources:

Team_Members_PPT/
├── Individual presentation slides for team members

Supply_Chain_Visibility_Optimization.pbix
├── Main Power BI dashboard file

Group_Presentation.pptx
├── Group presentation used for project demonstration

Completion_Report.pdf
├── Internship completion and project documentation report

LICENSE
├── Repository license

README.md
└── Project documentation

Note: If the actual filenames in the repository differ, the corresponding files can be renamed while keeping the same project structure.

🚀 Key Features

📊 1. Executive Dashboard

Provides a high-level view of overall business performance using key KPIs such as:

Total Sales

Total Profit

Total Orders

Profit Margin

Sales by Category

Profit by Region

Monthly Sales Trends

The Executive Dashboard helps management quickly understand overall sales and profitability performance.

🔍 2. Supply Chain Visibility

Provides operational visibility into:

Return Rate

Returned Orders

Sales by Customer Segment

Quantity by Region

Top Products by Sales

Orders by Shipping Mode

Profit by Customer Segment

This page helps identify demand patterns, customer contribution, product performance, and shipping distribution.

🌎 3. Regional & Category Analysis

Analyzes performance across regions, states, categories, and sub-categories to identify:

High-performing regions

Category-level performance

Regional demand patterns

Profit contribution

Product and sub-category differences

🚚 4. Shipping & Logistics Analysis

Evaluates logistics performance using shipping-related metrics and visualizations, helping identify differences in shipping duration and operational performance across shipping modes and order priorities.

💰 5. Product & Pricing Analysis

Examines the relationship between product performance, pricing, discounting, sales, and profitability to identify areas where discount strategies may affect margins.

📉 6. Discount & Profitability Diagnostics

Provides deeper profitability analysis, including loss-making orders and the relationship between discount levels and profit.

A key finding from the completed dashboard was that 20.40% of orders were loss-making, with discounting being an important area for further investigation.

📦 7. Order & Unit Economics

Analyzes profitability at the order and unit level to compare product categories and sub-categories.

The dashboard identified Technology as the strongest category in profit per unit, while Copiers stood out as a particularly strong sub-category.

🔄 Interactive Analysis

The dashboard uses Power BI interactivity, including:

Slicers

Cross-filtering

Drill-through

Dynamic KPI cards

Interactive charts

Consistent visual design across all seven pages

🛠️ Tools & Technologies

Technology

Purpose

Microsoft Power BI

Dashboard development, visualization, data modeling, and interactive reporting

Power Query

Data cleaning, transformation, formatting, and preprocessing

DAX (Data Analysis Expressions)

Creation of reusable calculated measures and KPIs

Microsoft Excel / CSV

Data preparation and source-data handling

GitHub

Version control and project repository management

GitLab

Backup repository and additional version-control support

Microsoft Teams

Team communication and mentor coordination

📊 Dataset

The project uses the Retail Supply Chain Sales Dataset, sourced from Kaggle.

The dataset contains information related to:

Order details

Customer information

Product information

Sales

Profit

Quantity

Discount

Shipping mode

Delivery information

Regional information

Customer segments

The dataset was studied field-by-field before dashboard development so that each visualization could answer a meaningful business question.

📐 Data Model & DAX Measures

The project uses a simple star-style data model with the retail order dataset as the central fact table and a supporting Calendar Table for time-based analysis.

A reusable DAX measure library was created and used throughout the dashboard:

Total Sales – Sum of Sales

Total Profit – Sum of Profit

Total Orders – Distinct count of Order ID

Total Quantity – Sum of Quantity

Profit Margin – Total Profit ÷ Total Sales

Return Rate – Returned Orders ÷ Total Orders

Returned Orders – Count of returned orders

Average Profit – Average Profit

Average Discount – Average Discount

Using reusable measures ensured that KPI values remained consistent and automatically responded to slicers and cross-filters.

📊 Project Workflow

Problem Understanding
        ↓
Data Collection
        ↓
Data Understanding
        ↓
Data Connection
        ↓
Data Cleaning & Preprocessing
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Measure Development
        ↓
Dashboard Development
        ↓
Testing & Validation
        ↓
Business Insights
        ↓
Decision Support

1. Problem Understanding

Identified common supply chain challenges such as delayed deliveries, limited visibility, inefficient shipping, profitability issues, and difficulty tracking operational performance.

2. Data Collection & Understanding

Selected and studied the Retail Supply Chain Sales Dataset from Kaggle, including order, customer, product, sales, profit, and logistics fields.

3. Data Connection

Imported the CSV dataset into Power BI using the Get Data option.

4. Data Cleaning & Preprocessing

The data preparation process included:

Removing duplicate records

Handling missing/null values

Correcting data types

Formatting date fields

Standardizing categorical values

Renaming fields for clarity

Removing unnecessary columns

Preparing calculated fields and measures

5. Data Modeling

Created a structured data model and supporting Calendar Table to enable reliable reporting and time-based analysis.

6. DAX Measure Development

Created reusable measures for sales, profit, orders, quantity, profitability, returns, and discount analysis.

7. Dashboard Development

Developed and expanded the report across four internship milestones, resulting in a complete seven-page interactive Power BI dashboard.

8. Testing & Validation

Tested slicers, filters, drill-through paths, KPI calculations, and cross-filtering behavior across the dashboard.

9. Insights & Interpretation

Converted dashboard findings into business insights and recommendations related to regional performance, discounting, shipping, profitability, and product economics.

🎯 Objectives

To improve supply chain visibility using an interactive Power BI dashboard.

To monitor sales, profit, orders, quantity, returns, and other important KPIs.

To identify delivery and shipping performance patterns.

To analyze regional, category, product, and customer-segment performance.

To understand how discounting affects profitability.

To identify loss-making orders and profitable product areas.

To support faster and more evidence-based business decisions.

To demonstrate the practical application of business intelligence and data analytics in a real-world supply chain context.

📌 Key Business Insights

The completed dashboard produced several important insights:

The West region recorded the highest regional profit at approximately 108K and also led in order quantity.

Technology was the leading category in sales and showed the strongest profit-per-unit performance.

Standard Class was the dominant shipping mode, accounting for approximately 59.77% of orders.

The overall Return Rate was approximately 5.91%, representing 296 returned orders.

20.40% of orders were loss-making, highlighting a significant profitability improvement opportunity.

Heavy discounting was associated with weaker profitability, particularly in areas involving Furniture and Office Supplies.

Copiers showed particularly strong unit economics, with approximately 237.68 profit per unit in the analyzed dashboard.

These findings demonstrate how interactive BI reporting can move beyond displaying data and support practical business decisions.

🎯 Dashboard KPIs

Some headline values from the completed dashboard include:

KPI

Value

Total Sales

2.30M

Total Profit

286.41K

Total Orders

5,009

Profit Margin

12.47%

Return Rate

5.91%

Returned Orders

296

Standard Class Order Share

59.77%

Loss-Making Orders

20.40%

👥 Team Learnings & Outcomes

Through this project, the team strengthened both technical and professional skills.

🔧 Technical Skills

Microsoft Power BI

Power Query data transformation

DAX measure development

Data cleaning and preprocessing

Data modeling

Interactive dashboard design

Supply chain analytics

KPI development

Business intelligence and data interpretation

Version control using GitHub/GitLab

💡 Soft Skills

Problem-solving and analytical thinking

Team collaboration

Technical communication

Presentation skills

Mentor interaction

Documentation

Time management

Data-driven decision making

The project provided practical exposure to the complete analytics lifecycle, from understanding raw data to delivering a business-ready dashboard.

🧩 Team Collaboration

The project was completed by a six-member team over the internship period.

The team divided responsibilities according to project phases rather than simply assigning individual dashboard pages. This helped maintain clear handoffs between data preparation, dashboard development, testing, and documentation.

GitHub was used as the primary version-control repository, with GitLab maintained as a backup. Regular communication and mentor interactions through Microsoft Teams supported progress reviews and refinement of dashboard design.

📈 Future Enhancements

Possible future improvements include:

Integrating live or regularly refreshed supply chain data.

Adding automated refresh and scheduled reporting.

Connecting additional inventory and procurement data sources.

Adding predictive analytics for demand and delivery-delay forecasting.

Developing early-warning indicators for high-risk orders.

Adding advanced profitability and customer-level analytics.

Deploying the dashboard through a governed cloud-based BI environment.

Integrating alerts for critical delivery, return, and profitability thresholds.

Extending the model with advanced time-intelligence and forecasting capabilities.

🏁 Conclusion

The Supply Chain Visibility & Optimization Dashboard demonstrates how business intelligence can be applied to a real-world retail supply chain problem.

By combining Power BI, Power Query, DAX, data modeling, and interactive visualization, the project transforms raw supply chain data into a centralized analytical solution for monitoring performance and supporting business decisions.

The final outcome is a seven-page interactive Power BI report covering executive performance, supply chain visibility, regional and category analysis, logistics, product and pricing, profitability diagnostics, and unit economics.

The project provided hands-on experience with an end-to-end data analytics workflow and helped bridge academic learning with practical, industry-oriented business intelligence experience.

💬 Contributors

Team B – Group 1

Manoj Pamuru

Narayana Murari

P. Shreesha

Pendyala Venkata Bharath

Prajwal Sahu

Priyanshi Singh

Internship: Infosys Springboard Virtual Internship 7.0
Start Date: 29 June 2026
Duration: 8 Weeks
Year: 2026

📌 Notes

This project was developed as part of the Infosys Springboard Virtual Internship 7.0.

The project was completed by Team B (Group 1).

The dashboard and analysis are intended for educational, demonstration, and internship purposes.

The Retail Supply Chain Sales Dataset was sourced from Kaggle and used for analytical and educational purposes.

The project demonstrates industry-oriented concepts in business intelligence, data analytics, dashboard development, and supply chain analysis.

⭐ Project Highlights

7 Dashboard Pages • 9 Reusable DAX Measures • Interactive Power BI Reporting • Supply Chain Analytics • Business KPI Monitoring • Data-Driven Decision Support
