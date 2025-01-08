# Udemy Data Analytics Bootcamp Projects

## (POWER BI) Website Performance Analytics
### Project Background
Focus Digital is a small (fictional) startup company specializing in providing freelance web development services.

The company has 3 months of data about their website performance metrics. This project analyzes and synthesizes this data to provide valuable insights into user behavior and website efficiency to optimize user experience and increase conversion rates.

Insights and recommendations are provided on the following key areas:
 * **Conversion Rate Analysis**: An evaluation of conversion rate by visitor type, traffice source, and location.
 * **Bounce Rate Analysis**: An assessment of bounce rate by visitor type.
 * **Page Performance**: A breakdown of page views, session duration, and conversion rates by the page the visitors exited the site.

An interactive PowerBI dashboard can be downloaded [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/main/dashboard_project.pbix). <br>
The raw Excel metrics dataset loaded into PowerBI can be found [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/main/website_performance_analytics.csv).

### Executive Summary
#### Overview of Findings 
Focus Digital's performance shows a solid foundation in conversion rates but highlights key areas for improvement to maximize user engagement and reduce bounce rates. An average 48% bounce rate is relatively high, which suggests room for improvement in the first-touch experience. However, the conversion rate remains strong among visitors who stay on the site, indicating that those who engage are likely to convert. Conversion rates for new and returning visitors are nearly identical, which suggests a consistent user experience. However, the bounce rates for both groups are similarly high (around 50%), signaling that both new and returning visitors might not be fully engaged from the outset. Traffic sources perform similarly, with direct search slightly outperforming at 5.08% with organic following closely at 5.03%. A high direct traffic conversion rate often suggests strong brand recognition and user loyalty, as people are actively seeking out the site. The overall conversion rate across all channels is still relatively low, highlighting a need for improved targeting and engagement strategies. Conversion rates are highest in Denver, San Francisco, Jacksonville, and New York. There's an opportunity to capitalize on these high-conversion cities with tailored campaigns to further boost performance. <br>

Below is the dashboard from PowerBI. The entire interactive dashboard can be downloaded [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/main/dashboard_project.pbix). <br>

![image](https://github.com/user-attachments/assets/7aa2de77-4ffb-4462-83e9-e73cde25e068)

#### Recommendations
Based on the uncovered insights, the following recommendations have been provided:
 * **Optimize Landing Pages**: Focus in improving the first user experience to reduce bounce rates, especially for new visitors. Testing landing page designs, content relevancy, and call-to-action clarity could significantly reduce drop-offs.
 * **Refine Traffic Source Strategy**: Further optimize organic search efforts while fine-tuning paid and referral traffic targeting to increase conversion rates from these channels. Experiment with ad creatives, content relevance, and user intent to enhance engagement.
 * **Leverage High-Performing Regions**: Capitalize on cities with higher conversion rates by running targeted, localized marketing campaigns to increase engagement and conversions in these areas.
 * **Conversion Rate Optimization (CRO)**: Invest in sitewide conversion optimization initiatives, such as A/B testing landing pages, simplifying user flows, and enhancing CTA visibility, to improve the overall conversion rate.

By addressing these key areas, the website can enhance user experience, reduce bounce rates, and ultimately drive more conversions across various traffic sources and visitor segments.

<br> <br>
## (PYTHON) Striker Analytics
### Project Background
SportQuest Recruitment, established in 2020, is a global (fictional) recruitment company helping future college players with their college and pro careers.

The company has significant amounts of data related to strikers, encompassing both demographic information and performance metrics. This project thoroughly analyzes this data to create a framework for identifying which metrics predict a top-performing striker.

The Jupyter Notebook file utilized for statistical analysis, feature engineering, clustering analysis, predictive analysis, and visualization can be found [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/main/Striker_Analytics.ipynb). <br>
The raw Excel performance dataset loaded into Jupyter can be found [here](https://github.com/alyssawinn/udemy-bootcamp-projects/blob/main/striker_data.csv).

### Executive Summary
The most significant performance measures to determine a top-performing striker were summed to create a Total Contribution Score. The fields are Goals Scored, Assists, Shots on Target, Dribbling Success, Aerial Duels Won, Defensive Contribution, Big Game Performance, and Consistency. If the total score is above 123.39, the striker is classified as a top performer. This was tested in a logistic regression model to verify how accurate the model predicted a top-performing striker and concluded that it accurately predicted whether a striker was an average or top performer 96% of the time.

![image](https://github.com/user-attachments/assets/4241126f-ecda-47ec-a22d-7498fe634f3e)

<br> <br>
### (EXCEL) Business Insights Dashboard
Click [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/558b9b0b95599a0adf0ace9dc3c02c5ec62c86e0/Business%20Insights%20Dashboard%20Project.xlsx) and click 'View Raw' to download .xlsx file and see the results.

Using a dataset of orders, I created 4 PivotTables and a Business Insights Dashboard with the associated PivotCharts showing the following:
 * Average discount rate and profit margin by product category
 * Average sales and quantity sold by region for each product category
 * Total number of products sold from each product category to different customer segments
 * Total amount of revenue for each product category to different customer segments

 ![image](https://github.com/user-attachments/assets/ea778a4c-7e3c-4291-bf34-d98a5d673b0f)

<br> <br>
### (EXCEL) Bank Churn Analysis
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

