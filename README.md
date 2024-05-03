The Diwali Sales Performance Analysis project examines sales data during the festive period, focusing on customer behavior, product preferences, and sales trends. By analyzing factors like demographics and product categories, it aims to provide actionable insights to optimize marketing strategies and improve sales performance for future Diwali seasons. 

Dataset:DiwaliSalesData.csv
It has rows:11251 and columns:15
Here's an explanation of each column in the dataset for analysis:
1.User_ID: Unique identifier for each user/customer.
2.Cust_name: Name of the customer.
3.Product_ID: Unique identifier for each product.
4.Gender: Gender of the customer.
5.Age Group: Age group of the customer.
6.Age: Age of the customer.
7.Marital_Status: Marital status of the customer (1 for married, 0 for unmarried).
8.State: State where the customer is located.
9.Zone: Zone or region where the state belongs.
10.Occupation: Occupation of the customer.
11.Product_Category: Category of the purchased product.
12.Orders: Number of orders placed by the customer.
13.Amount: Amount spent by the customer.
14.Status: This column seems to have no values, so it may be empty or irrelevant for analysis.
15.Unnamed1: Another column with no values, likely empty or irrelevant for analysis.

Steps handling in data analysis are:
1.Import Libraries: Import necessary Python libraries for data analysis such as Pandas, NumPy, and Matplotlib or Seaborn for visualization.
2.Load Data: Use Pandas to load the dataset from the CSV file into a DataFrame.
3.Data Cleaning:
Drop irrelevant columns like "Status" and "Unnamed1".
Handle missing values if any (e.g., filling missing values, dropping rows/columns).
4.Exploratory Data Analysis (EDA):
Explore the dataset to understand its structure, summary statistics, and distributions.
Use descriptive statistics and visualizations to gain insights into the data (e.g., histograms, box plots, count plots).
5.Feature Engineering (optional):
Create new features if needed based on existing data to enhance analysis (e.g., calculating total spending per customer, categorizing age groups differently).
6.Data Analysis:
Analyze sales performance by various factors such as gender, age group, state, product category, and occupation.
Calculate metrics such as average spending per order, total sales per state, popular product categories, etc.
7.Visualization:
Create visualizations to present insights effectively using Matplotlib or Seaborn.
Plot charts like bar plots, pie charts, and box plots to visualize relationships and trends in the data.
Statistical Analysis (optional):
Conduct statistical tests if necessary to validate hypotheses or make inferences about the data.
8.Summarize Insights:
Summarize key findings and insights from the analysis.
Provide actionable recommendations based on the insights.
