# Customer-Behavior-Analysis

                                                            Home Page 
<img width="1473" height="807" alt="Screenshot 2026-04-10 112701" src="https://github.com/user-attachments/assets/76cbc3e1-9ae7-40e5-ac81-d3916f6d7b6b" />


                                                            Over view Page
<img width="1437" height="792" alt="Screenshot 2026-04-10 115512" src="https://github.com/user-attachments/assets/39970bbb-3733-467a-8218-22a662c1a5ec" />

Customer Behavior Dashboard Analysis
Project Overview
The primary objective of this project is to analyze customer purchasing patterns and behavioral trends using a comprehensive dataset. This dashboard provides actionable insights to optimize business strategies, improve customer retention, and understand sales performance across different dimensions.

🛠️ Tools & Technologies Used
Power BI: For data modeling and creating interactive visualizations.

Power Query: Used for data cleaning, transformation, and ETL processes.

DAX (Data Analysis Expressions): Implemented to create complex calculated measures such as Total Purchase, Return Rates, and Customer Metrics.

Data Source: SQL / Excel (Mention the specific one you used here).

🔍 Key Insights & Analysis
1. Core KPI Metrics
The dashboard highlights four critical business indicators:

Total Customers: 250K

Total Purchase Value: 681M

Total Quantity Sold: 751K

Total Returns: 101K

2. Returns Analysis
The pie chart reveals that 41% of products were returned, while 59% were kept. This high return rate suggests a need for deeper investigation into product quality or description accuracy to improve inventory management.

3. Payment Method Preferences
Transaction volume is remarkably balanced across three main payment methods:

Credit Card: 229M

PayPal: 227M

Cash: 225M
This indicates that customers are comfortable using both digital and traditional payment gateways.

4. Category-Wise Performance
Sales are distributed almost equally across four major categories: Home, Clothing, Electronics, and Books (ranging from 169M to 171M). This signifies a well-balanced market demand across all product lines.

5. Demographic Distribution
The gender analysis shows an exact 50% - 50% split between Male and Female customers, suggesting that the brand’s appeal is perfectly gender-neutral.

6. Monthly Sales Trends
The time-series analysis shows consistent growth from January to August, peaking at 63M. However, there is a significant decline starting from September through December (dropping to 46M-47M). This trend identifies a crucial seasonal dip that requires targeted marketing campaigns during the year-end.

How to Use This Repository
Download the .pbix file included in the repository.

Open it using Power BI Desktop.

Explore the interactive filters (Slicers) like Churn to see how metrics change dynamically.


                                                            Product Page


<img width="1437" height="806" alt="Screenshot 2026-04-10 115929" src="https://github.com/user-attachments/assets/e304344b-8716-4409-9efa-b87675a1ddd9" />

Customer Analysis & Product Performance (Deep Dive)
🔍 Key Insights from the Second Dashboard
1. Advanced KPI Metrics
Total Product Sale: 64M (The actual volume of items moving through the inventory).

Leave Churns: 50K (This is a crucial metric identifying customers who have stopped using the service/product).

Returns %: 2.46% (A very healthy return percentage, showing efficiency in product quality).

2. Demographic Analysis (Age Groups)
The funnel chart represents sales distribution across different age brackets:

Age 50+: Leading the segment with 275M in purchases.

Age 18-34: Follows with 203M.

Age 35-49: Contributes 191M.

Under 18: Representing a niche market with 12M.

Insight: This shows that the older demographic is your primary revenue driver.

3. Top Customers (Top 5 Performers)
The horizontal bar chart identifies the highest-spending individuals:

Michael Johnson is the top customer with a total purchase of 339K, followed closely by Michael Smith (322K) and Michael Brown (300K).

4. Category by Quantity
This chart shows how many items were sold per category:

Clothing (189K), Home (188K), Electronics (188K), and Books (187K).

Insight: Demand is almost perfectly uniform across all product types, indicating a highly diversified and stable inventory.

5. Quarterly Performance (Quarter By Total Purchase)
The combined bar and line chart shows a steady performance in the first three quarters:

Qtr 1 & Qtr 2: Consistent at 182M - 183M.

Qtr 3: Slight dip to 177M.

Qtr 4: A significant drop to 139M.

Strategic Advice: This highlights the need for end-of-year promotional campaigns to boost Q4 performance.

                                                          Over All
                                                          
<img width="1432" height="793" alt="Screenshot 2026-04-10 115942" src="https://github.com/user-attachments/assets/985036ee-5efa-4957-b4d1-53bdff5a6ec1" />

📑 Detailed Transactional Data View
🔍 Purpose of this View
While the first two pages provide high-level summaries and trends, this page offers a Matrix/Table View for deep-dive analysis. It allows stakeholders to look at individual customer transactions, preferred payment methods, and specific product categories.

🔍 Key Features & Insights
1. Individual Customer Tracking
The table tracks high-value customers like Michael Johnson, Michael Smith, and Michael Brown.

It showcases their specific buying habits, such as Michael Johnson purchasing 57 items in the Home category using Cash, totaling 45,856.

2. Multi-Dimensional Breakdown
The table is structured to show the relationship between:

Customer Name: Identifying loyal or high-spending clients.

Payment Method: Seeing which gateway a specific customer prefers (e.g., PayPal vs. Credit Card).

Product Category: Understanding what specific items are driving the most volume for individual users.

3. Data Integrity & Totals
Sum of Quantity: Totaling 751,234 units.

Sum of Total Purchase Amount: Totaling 681,346,299.

This page serves as a "Source of Truth" to verify the accuracy of the visual charts on the previous pages.

4. Interactive Slicers
To make this granular data manageable, I have included three primary filters:

Year: To see transaction history by specific timeframes.

Churn: To identify the buying patterns of customers who are at risk of leaving.

Gender: To filter specific demographic buying lists.


