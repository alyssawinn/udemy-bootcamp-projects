# Data Analytics Portfolio


## (PYTHON) Striker Analytics
Through a comprehensive analysis of the raw performance dataset [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/main/performance_data.xlsx), I've gained valuable insights into the characteristics and performance metrics of strikers. By segmenting and classifying the strikers based on their attributes and performance, I've provided a framework for identifying top-performing strikers and predicting their performance type.

Click [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/main/Striker_Analytics.ipynb) to see the Jupyter Notebook file. The steps taken:
 1. Data Cleaning - replaced missing ordinal values with the median value and converted various variables from float to int data types
 2. Exploratory Analysis - ran descriptive analysis to verify there were no outliers, compared Footedness by Nationality and Conversion Rate
 3. Statistical Analysis - verified Consistency and Hold-up Play were normally distributed, concluded there is no significant difference in Consistency between different Nationalities, and concluded there is a weak positive but significant correlation between Consistency and Hold-up Play
 4. Feature Engineering - created a Total Contribution Score variable by summing various performance measures, encoded the nominal variables Footedness and Marital Status, and created dummy variables for Nationality
 5. Clustering Analysis - created a Striker Ranking variable to segment regular and excellent strikers based on the Total Contribution Score
 6. Predictive Analysis - used a logistic regression model to calculate the accuracy score and confusion matrix to verify how accurate the model predicted the striker ranking

![image](https://github.com/user-attachments/assets/4241126f-ecda-47ec-a22d-7498fe634f3e)

## (EXCEL) Business Insights Dashboard
Click [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/558b9b0b95599a0adf0ace9dc3c02c5ec62c86e0/Business%20Insights%20Dashboard%20Project.xlsx) and click 'View Raw' to download .xlsx file and see the results.

Using a dataset of orders, I created 4 PivotTables and a Business Insights Dashboard with the associated PivotCharts showing the following:
 * Average discount rate and profit margin by product category
 * Average sales and quantity sold by region for each product category
 * Total number of products sold from each product category to different customer segments
 * Total amount of revenue for each product category to different customer segments

 ![image](https://github.com/user-attachments/assets/ea778a4c-7e3c-4291-bf34-d98a5d673b0f)


## (EXCEL) Bank Churn Analysis
Click [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/4bae85ac9f3c1b66afb7fef0dbc743c85cf8375c/Bank%20Churn%20Analysis%20Project.xlsx) and click 'View Raw' to download .xlsx file and see the results.

Using the instructions in the .xlsx file, I analyzed customer bank churn data using PivotTables and the Data Analysis ToolPak to answer the following questions:
 1. What is the average credit score for each country?
 2. How does the average account balance vary between genders within each country?
 3. What is the distribution of active vs. inactive members that own a credit card?
 4. What is the churn rate per number of products used?
 5. What is the average credit score for churned vs. not churned customers across different tenure? (See screenshot below)
 6. Is there any significant difference in average earnings between churned vs. not churned customers?
 7. Is there any significant difference in average credit score among geographic location?
    
 ![image](https://github.com/user-attachments/assets/91da744a-3b72-4984-aec7-120320f1a53a)

