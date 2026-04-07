# Customer-Churn-Analysis

## Project Background
Redblue Telco, is a telecommunications company in the state of california that provides home phone and internet sevices to customers over more than 1000 cities and zip codes. 

By the end of the last quarter, the company have a critical problem about 28% of their customers decided on not renewing their subscribtions, meaning the customer churn rate is very high and above the goal of 10%, and the company is now facing a big challenge on retaining its customers. So, this project thoroughly analyses to uncover the factors leading to high customer churn rates and to help business stakeholders understand why customers leave and what can be done to retain them. 

In addition, we build a predictive model to identify customers who are likely to churn, by understanding churn patterns, company can take proactive measures to improve customer retention.

Insights and recommendations are provided on the following key areas:
- **Churn Analysis**: Identification of factors that influence churn, focusing on metrics of customer churn rates and number of churn
- **Product Level Performance**: An analysis of Redblue's various product lines, understanding their impact on churn.
- **Marketing Campaign Success**: An assessment of the marketing campaign on customer churn.
- **Regional and Demographical Comparison**: An evaluation of churn by region and demographic.

## Dataset
The dataset contains many fields including customer data, product data, order data, sales data, geographic data, and churn data.

## Insights
### Executive Summary
At the start of the last quarter, Redblue Telco had 6,589 customers with an average revenue per user of $268.64. However, by the end of the quarter, 1869 of its customers (around 28% of them) had decided not to renew their subscriptions, mostly due to offers and device quality that were inferior compared to competitors. As a result, company lost around 31% of its revenue in the following quarter. 

The fact that churned customers had higher quarterly ARPU than retained customers explains why revenue churn was greater than customer churn. And they tended to churn early in their subscription lifecycle. These indicate Churned customer is early-stage customers with high usage but weak retention.


### Product Insights
- More than half of the customers who received an offer E from marketing team, or more precisely 68%, decided not to renew their subcription. Around three times higher than the other offers.
- Fiber optic users made up the largest group, but 42% of them churned, that's the highest among all internet type.
- Nearly a half of all customers choosed month-to-month contract rather than the other two options which had longer term. But they were the ones with the highest churn rate, even more than 50%.
- In terms of services, internet service and unlimited data demonstrate relatively weak performance with regard to customer churn, customers who opted for these services had churn rate two to three higher than those who do not. On the other hand, online backup, online security, and tech support performed quite well in reducing customer churn. 



### Demographic and Geographic
- Customers who referred more acquintances to subscribe demonstrated more loyalty.
- Older customers were more likely to cancel their subscription. The 66-80 year-old customers had the highest churn rate.
- The Majority of Redblue's customers were from San Diego, but the customer churn rate for this city was the highest, at 67%.  

## Recommendations
Based on the insights found, here are some recommended actions that might be applied to reduce the churn rate:
- Address the main reason for churn with several approaches:
  * Increase the value of the company's offerings by providing more competitive packages, both in terms of price and features in order to compete with competitors.
  * Consider working with leading vendors to provide the latest and more attractive devices.
  * Improve customer support training to ensure a friendly, professional, and solutive attitude.
- Conduct an in-depth analysis of why Offer E is causing a high churn rate (53%). Consider replacing or improving Offer E with a more relevant and engaging offer.
- Provide incentives to convert month-to-month customers to long-term contracts, such as additional discounts or free premium services.
- Segment customers by age and adjust marketing strategies and offers accordingly.
- Conduct deeper geographical analysis to understand why San Diego has a very high churn rate (65%).
- Use the churn prediction model that has been built to identify customers who have the potential to churn. Then proactively intervene with the identified customers.

The SQL queries utilized to seperate data can be found here.

The SQL queries utilized to clean, organize, and prepare data to dashboard can be found here.

The SQL queries utilized to analyze data exploratory can be found here.

The interactive dashboard can be found here.

The notebook of churn prediction modeling can be found here.

Model files to predict customer churn can be found here.

All dataset can be found here.


