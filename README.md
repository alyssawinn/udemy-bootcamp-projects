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
## (EXCEL) Business Insights Dashboard
### Project Background
Red Cart, established in 2005, is a (fictional) mass merchandiser corporation that operates sells a wide variety of goods, serving both businesses and individual customers.

The company has a small subset of order data, including sales, statuses, and profit margin for various regions. This project analyzes this data in order to uncover critical insights that will improve Red Cart's marketing strategy and commercial success.

Inisghts and recommendations are provided on the following key areas:
 * **Sales Trends Analysis**: Evaluation of sales patterns, by sales channel and customer segment, focusing on Profit Margin and Total Revenue.
 * **Product Level Performance**: An analysis of Red Cart's various product categories, understanding their impact on sales.
 * **Regional Comparisons**: An evaluation of orders by region.

The raw sales data and interactive Excel dashboard can be downloaded [here](https://github.com/alyssawinn/data-analytics-portfolio/blob/558b9b0b95599a0adf0ace9dc3c02c5ec62c86e0/Business%20Insights%20Dashboard%20Project.xlsx).

### Executive Summary
The South region leads in profitability, with Clothing and Sports & Outdoors showing the highest margins, while the West excels in Beauty & Health. Wholesale channels dominate revenue generation, particularly in Home & Kitchen, Beauty & Health, and Clothing, but Electronics consistently underperforms across all segments. To maximize profitability, prioritize high-margin categories like Beauty & Health, introduce premium products in popular but low-revenue areas such as Beauty & Health in the North region and Electronics in the West, and refine discount strategies for low-performing segments.

 ![image](https://github.com/user-attachments/assets/ea778a4c-7e3c-4291-bf34-d98a5d673b0f)

 #### Sales Trends
  * The **South region dominates** with the highest profit margin in Clothing (42%) and Sports (42%), while the **West region excels** in Beauty (35%).
  * **Wholesale channels** are top performers, with Home and Beauty categories leading revenue generation, while Electronics underperforms across all segments.

#### Product Performance
 * **High-margin categories** like Beauty (25%) have the lowest discount rates (7%), making it a key driver of profitability.
 * **Low-revenue but popular categories** for premium product introductions include North and South Beauty, West Clothing, and West Electronics.

#### Regional Comparisons
 * **Strengths**: Home & Kitchen in the West and South regions, and Clothing in the South and East regions consistently outperform.
 * **Weaknesses**: Beauty and Sports & Outdoors in the South region, and Clothing in the West region face challenges in driving sales despite high potential.

#### Recommendations
 1. **Prioritize high-margin categories** (e.g., Beauty & Health, Clothing in the South region) for marketing and inventory investments.
 2. **Reassess discount strategies** for low-margin categories where discounts don't drive sufficient sales or profitability, like Electronics and Sports & Outdoors for Business customers.
 3. **Introduce premium product lines** in popular but low-revenue categories to increase average revenue per sale (e.g., Beauty & Health in the North region, Electronics in the West).
 4. Focus marketing on **regional strengths** (e.g., Clothing in the South and East regions) while addressing regional weaknesses (e.g., Beauty & Health in the South region, Clothing in the West).
 5. Enhance the **online user experience** for Wholesale and Business Home & Kitchen channels, which are the most profitable.
 6. Develop **loyalty programs** targeting top-performing customer segments, such as Wholesale Home & Kitchen and Business Sports.
 7. Reduce returns and cancellations by improving product descriptions, quality assurance, and flexible return policies for Electronics and Clothing.

<br> <br>
## (EXCEL) Bank Churn Analysis
### Project Background
Pinnacle Banking Group, a (fictional) European company headquartered in Frankfurt, engages in the provision of full banking and related services.

Pinnacle has a sample set of data, including information about their customers, tenure, product utilization, and churn status. This project statistically analyzes this data to help understand factors contribution to customer churn.

The customer data and statistical analyses can be downloaded [here](https://github.com/alyssawinn/udemy-bootcamp-projects/blob/main/Bank%20Churn%20Analysis%20Project.xlsx).

Inisghts and recommendations are provided on the following key areas:
 * **Credit Score and Account Balance Analysis**: Evaluation of credit scores and account balance, focusing on tenure and location. Evaluation of credit utilization of active vs. non-active members.
 * **Churn Evaluation**: An analysis of Pinnacle's customers' churn statuses and statistical significance of various measures.

 ### Executive Summary
The analysis reveals that Spain has the highest average credit score, while Germany leads in average account balances, highlighting potential economic and behavioral differences across countries. Gender disparities in account balances are evident, with German females outperforming males, whereas in France and Spain, males hold a slight advantage. Churn rates are not directly linked to product utilization or earnings, but customers using 4 products exhibit lower churn, suggesting a potential loyalty threshold; additionally, customers with lower credit scores, particularly in the 6-10 year tenure group, are more prone to churn.

 #### Credit Score Analysis
  * Spain customers have the highest average credit score (601), indicating better credit management or different lending standards.
  * Germany customers have the lowest average credit score (580), which could suggest more lenient credit granting policies, differences in financial behavior or credit scoring criteria, or economic factors that might affect credit performance.
  * France is almost aligned with the overall average (593), indicating its credit profile is typical of the dataset's overall customer base.
  * There is no significant difference between average credit score and location.

#### Account Balance Analysis
  * Country plays a significant role in average account balances. Germany leads overall ($134K), followed by France ($131K), and Spain lags behind significantly ($120K). This could reflect differences in economic conditions, saving habits, or bank strategies in these countries.
  * Germany is the only country where females outperform males significantly ($140K to $128K). This could indicate targeted financial products, economic factors, or behavioral differences. In France and Spain, males outperform females, but the gap is narrower.
  * Spain consistenly lags in average balances, suggesting structural or economic challenges, or different levels of customer engagement.

#### Churn Evaluation
  * Product utilization does not correlate to churn. However, there is a lower churn overall for customers utilizing 4 products hinting at a "stickiness" factor where customers are engaging with all available products feel more integrated with the bank's ecosystem, which could slightly reduce churn.
  * For every tenure group, customers who have not churned tend to have a slightly higher credit score compared to those who have churned.
  * There is no significant difference between average earnings and churn status.

![image](https://github.com/user-attachments/assets/5389f0b3-84e6-4d10-a39d-c6ed22d97d89)

#### Recommendations
 1. Investigate why **churn rate drops at 4 products**. Is there a threshold effect (e.g. bundle discount, higher customer satisfaction, or loyalty benefits)?
 2. **Focus retention efforts on customers with lower credit scores** especially in the 6-10 year group, where churned customers have the lowest average credit scores.
 3. Investigate the 3-5 year group for anomalies or unique factors leading to churn, such as dissatisfaction or unmet expectations despite good financial standing.
 4. **Monitor new customers** as those with lower credit scores are at a higher risk for churn. Early engagement strategies may help reduce churn in this group.


