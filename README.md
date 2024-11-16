### SalesAnalysis
Tableau Project on SuperStore Sales Analysis

### Tableau Public Link

This project has been uploaded to Tableau public and here is the link
https://public.tableau.com/views/CapstoneProject2_17169742399760/SalesDashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

### Problem Statement

#### Dataset Information

The Sample - Superstore.xls excel sheet contains 3 tabs namely Orders, People and Returns. 

A) The Orders tab contains 9,994 rows and 21 columns namely 1) Row ID	2) Order ID	3) Order Date	4) Ship Date 5) Ship Mode	6) Customer ID	7) Customer Name	8) Segment	9) Country/Region	10) City	
11) State	12) Postal Code	13) Region	14) Product ID	15) Category	16) Sub-Category	17) Product Name	18) Sales	19) Quantity	20) Discount	21) Profit

B) The People tab contains 4 rows and 2 columns namely 1) Regional Manager	2) Region

C) The Returns tab contains 800 rows and 2 columns namely 1) Returned	2) Order ID

#### Instructions
Use Sample - Superstore.xls data.
Note that you can use either Tableau Public or Desktop to find the answer.
If you are using Tableau Desktop, the Sample Superstore dataset should be present in the Saved Data sources and will also be present in your My Tableau Repository folder on your local machine.
Data should be an extract and not a ‘Live’ connection.

#### Tableau Project Requirement
The workbook should have a single dashboard.
Each worksheet/view/chart should meet the business requirement.
All worksheets should be hidden.
Workbook should be published to Tableau Public if possible.

#### Submission Guidelines
Copy-Paste the screenshots for every view in a word document and upload the document for verification.
Provide the screenshot of the final dashboard as per the requirements mentioned in the project.

#### Business Requirement
Connect to the Sample Superstore dataset and build a Dashboard that will show the Sales Performance.

#### View 1: Total Sales
The sheet should only display the Total Sales in thousands, along with the header “Total Sales”.
The Total Sales displayed should have the color code “#76b7b2”. Use the Color Palette.
Disable Tooltip for this view.
Use the background color of your choice.
Name the sheet as “Total Sales”.

##### View 2: Total Profit
Requirements are the same as for the view “Total Sales”.

##### View 3: Total Volume
Requirements are the same as for the view “Total Sales”, except it’s not a currency value.

##### View 4: Sales Per Customer
Requirements are the same as for the view “Total Sales“.

##### View 5: Pie Chart
Pie Chart should display the percent of Total Sales by Region.
Use the Summer Color Palette. Pie Chart should have black borders.
Tooltip should be formatted as seen below showing Region Name, Percent of Total Sales, and the Total Sales value formatted in currency and displayed in thousands (K).
Note: Drag all the filters mentioned in the general requirement to this sheet named Pie Chart.

##### View 6: Bar Chart
Horizontal Bar Chart should display the top N states by Sales.
Using a Parameter, the user should be able to change the value of N.
Use the color of your choice for the bars along with the labels displayed in $.
Data should always be sorted in descending order.

##### View 7: Bubble Chart
Bubble chart should display Sales by sub-category.
Bubbles should be colored by category.
Use the color of your choice for the bubble.
Tooltip should display only sub-category along with the sales value in $ in thousands (K).

##### View 8: Line Chart
A continuous line chart should display the Sales trend by Month-Year.
X-axis should display month and year in the format MMM YY. For example, Mar 22 [Year 2022].
Hide the axis titles only.
Tooltip should display only Month-Year, along with the sales value in $ in Thousands (K).
Use Order Date as a Date Range filter.
Name the sheet as shown below and color the tab.

#### Dashboard Requirements
Dashboard Name: Sales Dashboard
Dashboard Title: Superstore Sales Performance
Dashboard description: Sales overview of the superstore data
Dashboard size: Should be set to FIXED size. Width – 1055, Height – 850
Dashboard Filters:
Filters to be present in dashboard:
Order Date – Show as Range of date. This filter should be applied to all worksheets.
Segment – Show as multiple values (drop-down) with the Apply button and showing only relevant values. This filter should be applied to all worksheets.
Ship Mode – Show multiple values (drop-down) with the Apply button and show only relevant values. This filter should be applied to all worksheets.
State – Show multiple values (drop-down) with the Apply button and show only relevant values. This filter should be applied to all worksheets except the bar chart.
Filter Formatting:
Format the filter background to any color.
Add borders if necessary.
Place all these filters in a horizontal container and distribute them evenly.

#### Dashboard Containers:
Horizontal Container 1: Should have the name of the dashboard and add an image showing a shopping cart (add an image with transparent background) to the left of it as shown below. You can rename this container “Title/Logo” as it will help you distinguish between containers.
Horizontal Container 2: This should contain all the filters arranged in a horizontal container. Name this container “Filters”. Distribute the contents evenly.
Horizontal Container 3: Arrange all the scorecards in a horizontal container.
Horizontal Container 4: Pie Chart and Bar Chart should be arranged and placed in a horizontal container. Name it accordingly.
Horizontal Container 5: Bubble Chart and Line Chart should be arranged and placed in a horizontal container. Name it accordingly.
Vertical Container: Place all these horizontal containers one above the other, top to bottom, in the order they are numbered.

#### Dashboard Formatting:
Legends: Hide the titles for the legends and place it next to their associated charts in such a way that they don’t overlap with the chart.
Borders: Add borders if needed per chart or per container, whichever is visually comprehensive.
Actionable Filters:
Use the Pie chart and Bubble chart as Actionable Filters.
Parameters: Place the parameter close to the Bar chart and place it somewhere on the Sheet title.
Fit View: Fit the Dashboard to “Entire View”, wherever applicable.
Sheet Titles: Describe each visualization with a meaningful title.
Hide Sheets: After the dashboard is all set to be published, hide all the sheets, and clean up your workbook. Also, you can hide all unused fields if needed.

### Purpose of Solving this problem

Analyzing the sales data of a store like Superstore using Tableau can provide valuable insights for decision-making across various operational, marketing, and strategic areas. Tableau's powerful visualization capabilities make it easier to identify trends, patterns, and actionable insights. Here's a breakdown of the key purposes:

#### 1. Monitor and Improve Sales Performance
Revenue Trends: Track total sales, profit margins, and revenue growth over time.
Category Insights: Identify top-performing product categories and subcategories.
Seasonal Analysis: Discover seasonality patterns and high-demand periods.
Regional Performance: Analyze sales performance by region, state, or city to identify strong and weak markets.

#### 2. Understand Customer Behavior
Purchase Patterns: Identify which products are purchased frequently or together.
Customer Segmentation: Group customers by buying habits, spending levels, or location.
Loyalty Analysis: Determine the lifetime value of customers and their retention patterns.

#### 3. Optimize Inventory Management
Stock Levels: Highlight overstocked or understocked items.
Turnover Rates: Understand how quickly products are sold.
Demand Forecasting: Use historical sales data to predict future demand and optimize inventory.

#### 4. Identify Profitability Drivers
Profit Margins: Pinpoint which products, categories, or regions yield the highest profits.
Cost vs. Revenue: Compare operational costs with revenue generation.
Discount Analysis: Assess the impact of discounts on sales and profitability.

#### 5. Evaluate Marketing Effectiveness
Campaign Impact: Measure how promotions and campaigns affect sales.
Product Popularity: Identify which promotions drive the most traffic and conversions.
Cross-Selling Opportunities: Analyze product combinations to target upselling or bundling strategies.

#### 6. Enhance Operational Efficiency
Shipping and Delivery: Examine delivery times and costs to optimize logistics.
Order Patterns: Identify peak order times to allocate resources effectively.
Returns Analysis: Understand reasons for product returns to reduce future occurrences.

#### 7. Drive Strategic Decision-Making
Market Expansion: Use regional sales data to identify opportunities for opening new stores.
Pricing Strategies: Evaluate pricing trends to remain competitive.
Customer Demographics: Target specific segments more effectively based on their preferences and buying behaviors.

#### 8. Detect Anomalies and Address Issues
Low Performance Areas: Quickly identify products or regions with declining sales.
Fraud Detection: Spot unusual patterns that could indicate fraud or errors.
Customer Complaints: Analyze feedback data tied to sales trends.

#### Why Tableau for This Analysis?
Interactive Dashboards: Allow users to drill down into details and uncover specific insights.
Real-Time Data Integration: Update dashboards with the latest sales data automatically.
Custom Visualizations: Create graphs, maps, heatmaps, and more for intuitive data interpretation.
Easy Collaboration: Share dashboards across teams to align strategies.
Predictive Analysis: Use built-in tools or integrate with models to predict future trends.

#### Outcome
Analyzing sales data using Tableau empowers decision-makers to boost revenue, optimize operations, and deliver better customer experiences while aligning strategies with real-world data insights.






