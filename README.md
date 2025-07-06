# Sales and Customer Dashboard

## Overview
This project involved the development of two interactive dashboards – a Sales Dashboard and a Customers Dashboard – designed to provide key stakeholders (sales managers, executives, and marketing teams) with actionable insights into sales performance and customer behavior. The goal is to enable data-driven strategic decisions and foster a deeper understanding of business trends.


## Problem Statement
The primary objective of this project was to address critical information gaps within the organization:
- Sales managers lacked a unified and dynamic view of year-over-year sales trends, hindering their ability to analyze performance and identify growth opportunities.
- Marketing teams required deeper insights into customer segments, loyalty, and behavior to refine strategies and improve customer satisfaction.
- These dashboards aim to centralize and visualize key performance indicators, providing a clear, interactive platform for addressing these challenges.  

## Key Requirements. 
Need to build two dashboards to help stakeholders, including sales managers and executives to analyze sales performance and customers.  
### **Sales Dashboard**

sales dashboard is to present an overview of the sales metrics and trends in order to analyze year-over-year sales performance and understand sales trends.

Key requirements:

- **KPI Overview**

    Display a summary of total sales, profits and quantity for the current year and the previous year.

- **Sales Trends**

    1. Present the data for each KPI on a monthly basis for both the current year and the previous year.

    2. Identify months with highest and lowest sales and make them easy to recognize.

- **Product Subcategory Comparison**
    1. Compare sales performance by different product subcategories for the current year and the previous year.
    2. Include a comparison of sales with profit.
- **Weekly Trends for Sales & Profit**
    1. Present weekly sales and profit data for the current year.
    2. Display the average weekly values.
    3. Highlight weeks that are above and below the average to draw attention to sales & profit performance.

### Customers Dashboard

Aims to provide an overview of customer data, trends and behaviors. It will help marketing teams and management to understand customer segments and improve customer satisfaction.

- **KPI Overview**
    1. Display a summary of total number of customers , total sales per customer and total number of orders for the current year and the previous year.
- **Customer Trends**
    1. Present the data for each KPI on a monthly basis for both the current year and the previous year.
    2. Identify months with highest and lowest sales and make them easy to recognize.
- **Customer Distribution by Number of Orders**
    1. Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior, loyalty and engagement.
- **Top 10 Customers By Profit**
    1. Present the top 10 customers who have generated the highest profits for the company.
    2. Show additional information like rank, number of orders, current sales, current profit and the last order date.

### Design Requirements

**Dashboard Dynamic**
- The Dashboard should allow users to check historical data by offering them the flexibility to select any desired year.
- Provide users with the ability to navigate between the dashboards easily.
- Make the charts and graphs interactive, enabling users to filter data using the charts.

**Data Filters**
- Allow users to filter data by product information like category and subcategory and by location information like region, state and city.  

## Finalizing the charts

#### For Sales Requirement

1. For each KPI will be using banners
2. For showing the sales, profit and quantity we will be using the line chart current year vs prev year with two circle indicators indicating the minimum and maximum point of the year.
3. For Product category and sub-category → Bar in Bar Chart
4. For profit and sales → Bar chart
5. For weekly trends of sales and profits → Line chart with square path

#### For Customer Requirement
1. For each KPI will be using banners
2. For showing the total customers, orders and sales per customer we will be using the line chart current year vs prev year with two circle indicators indicating the minimum and maximum point of the year.
3. Showing the customer distribution based on number of orders we will be using Histogram.
4. Showing the top 10 customers by profit we will be using a Table with features as Rank, Customer Name, Last Order, Total Sales, Orders, Profit.


## Methodology / Approach
The dashboard development followed a user-centric design approach, prioritizing stakeholder requirements and data-driven insights:

- **Requirement Gathering:** Collaborated with hypothetical sales managers and marketing teams to identify their key performance indicators (KPIs) and analytical needs.
- **Data Understanding & Exploration:** Thoroughly explored the dataset to understand its structure, identify potential issues, and determine suitable metrics.
- **Dashboard Design & Prototyping:** Designed intuitive layouts for both dashboards, focusing on logical flow and visual hierarchy.
- **Visualization Selection:** Chose appropriate chart types (e.g., line charts for trends, bar-in-bar for comparisons, banners for KPIs) to effectively communicate insights and ensure clarity.
- **Interactivity Implementation:** Incorporated dynamic filters (year, product, location) and chart-as-filter actions to allow users to explore data at various levels of detail.

##  Key Findings & Insights
**The dashboards reveal several critical insights:**

**Sales Dashboard Insights:** 

- **Seasonal Performance:** Identified a consistent surge in sales during Q4 (October-December), indicating strong holiday season performance. Conversely, a noticeable dip in Q1 suggests opportunities for targeted promotions or new strategies during this period.

- **Product Profitability:** Analysis of product subcategories revealed that while some subcategories might have high sales volume like 'Phone' & 'Chairs' , consistently generate higher profit margins, highlighting their strategic.

- **Weekly Fluctuations:** The weekly trends chart helps in pinpointing specific weeks with exceptional performance (above average) or those requiring attention (below average), allowing for agile operational adjustments, On an average the weekly sales are above $10k and and profits are $1k.

**Customers Dashboard Insights:**
- **Customer Loyalty:** The customer distribution by orders chart indicated that a significant portion of customers two-three time buyers. This highlights a clear that most if the customers are loyal and in-order to increase the retention we need to promote loyalty programs or referral strategies to encourage repeat purchases.

- **High-Value Customers:** The 'Top 10 Customers By Profit' section clearly identifies the most valuable customers. These customers contribute a substantial percentage of overall profit, emphasizing the importance of personalized retention strategies this segment.

- **Customer Growth:** Monthly customer trends show periods of significant customer acquisition or churn, providing insights for marketing campaign timing and effectiveness. On an average every year the customer growth is of 5-6%.

- **Orders Growth:** YoY Growth in orders is significantly visible and also there is a spike in orders after the month of October which is relevant to the sales insight and can be helpful to increase the number of orders in that period by implementing different promotion strategies like discount and seasonal offers.

## Dashboard Walkthrough

**Sales Dashboard:**  
- **KPI:** Large, clear banners at the top display total sales, profits, and quantity for the current and previous year, providing an immediate performance snapshot.

- **Sales Trends:** A dual-axis line chart shows monthly sales, profit, and quantity, allowing for direct year-over-year comparison. High/low points are highlighted for quick identification.

- **Product Subcategory Comparison:** A bar-in-bar chart visually compares sales and profit across different product subcategories, enabling easy identification of profitable product lines.

- **Weekly Trends:** A line chart with square paths displays weekly sales and profit, with average lines and highlights for above/below average weeks, offering granular performance insights.

**Customers Dashboard:**

- **KPI:** Similar to the sales dashboard, banners summarize total customers, sales per customer, and total orders for current and previous years.

- **Customer Trends:** Line charts illustrate monthly trends for customer count, sales per customer, and total orders, revealing seasonal customer behavior.

- **Customer Distribution:** A bar chart shows the count of customers based on the number of orders placed, providing insights into customer loyalty tiers.

- **Top 10 Customers:** A detailed table lists the top 10 customers by profit, including their rank, number of orders, current sales, current profit, and last order date.

**Interactivity & Filters:**  
- **Dynamic Year Selection:** A prominent 'Year Selector' filter allows users to dynamically view historical data for any desired year across both dashboards.

- **Navigation:** Dedicated navigation buttons/tabs facilitate seamless switching between the Sales and Customers Dashboards.

- **Interactive Charts:** Specific charts of the Sales dashboard like the product comparision and weekly trend charts are interactive and the table in the customer dashboard is interactive.

- Data Filters: Comprehensive filter options are available for refining data by:

        Product Information: Category, Subcategory

        Location Information: Region, State, City


## Impact & Value Proposition
**These dashboards provide significant value by:**  
- **Empowering Data-Driven Decisions:** Sales managers can quickly identify underperforming products or regions, allowing for timely interventions and strategic resource allocation.

- **Optimizing Marketing Efforts:** Marketing teams can segment customers more effectively, leading to more targeted campaigns, improved customer satisfaction, and increased loyalty.

- **Enhancing Performance Monitoring:** Stakeholders gain a clear, real-time understanding of key performance indicators and trends, facilitating proactive management and strategic planning.

## Future Enhancements
- Integration of marketing campaign data to analyze ROI.

- Implementation of forecasting models for sales and customer growth.

- Development of a Customer Lifetime Value (CLTV) metric.

- Adding drill-down capabilities to individual customer profiles.

## Links
Live Dashboard: [Tableau Link](https://public.tableau.com/views/SalesDashboard_17515113910860/SalesDashboard?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link)

GitHub Repository: [GitHub Repository URL ](https://github.com/AdityaKumbhar21/Sales_and_Customer_Dashboard)

## Your Role & Contributions
As an individual project, I was responsible for the entire lifecycle, including data sourcing (simulated), cleaning, dashboard design, visualization development, and documentation.

## Contact Information.  
Name: Aditya Kumbhar.  
Email: adityakumbhar915@gmail.com.  
LinkedIn: [Linkedin Profile](www.linkedin.com/in/aditya-kumbhar-688a17252)