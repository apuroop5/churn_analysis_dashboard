# churn_analysis_dashboard
This project focuses on analyzing customer churn patterns to understand the factors that lead to customer attrition and to support data-driven retention strategies. Using Power BI, an interactive dashboard was built to visualize key metrics such as churn rate, geography-wise performance, customer demographics, and product usage behavior.
The analysis helps businesses identify high-risk customer groups, monitor churn trends, and take proactive actions to improve customer loyalty and satisfaction.
The dashboard is based on the Churn_Modelling.csv dataset, which contains 10,000 customer records with the following key features:
Geography: Country of the customer (France, Germany, Spain)
Gender: Male or Female
Age Group: Teenager, Adult, Senior Citizen
Credit Score: Categorized as Bad, Good, or Best
Number of Products: Number of products held by the customer
Exited: Indicates whether the customer has churned (1) or stayed (0)

Dashboard Insights:
Total Customers- 10,000
Churned Customers- 2,000
Overall Churn Rate- 20%
Germany records the highest churn rate (~30%), followed by Spain and France.
Adults represent the largest segment driving churn, while teenagers and senior citizens have lower churn rates.
Customers with fewer products are more likely to leave.
Higher credit scores are generally associated with lower churn probability.

Dashboard Features:
KPI Cards: Display total customer count, churn count, and churn rate.
Bar Charts: Show customer distribution by geography and churn by age group.
Column Chart: Represents churn percentage by country.
Pie Chart: Visualizes churn distribution by credit score performance.
Line Chart: Shows churn rate trends across the number of products.
Slicers: Allow filtering by Gender and Churn Status for deeper exploration.
Insights Panel: Highlights key findings directly on the dashboard for quick interpretation.


Tools & Technologies Used:
Power BI – for dashboard creation and interactivity
Power Query – for data transformation and cleaning
Microsoft Excel / CSV – as the data source
DAX (Data Analysis Expressions) – for calculated measures and KPIs
