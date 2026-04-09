# Customer-Churn-Analysis

## Table of Contents
- [Project Background](#project-background)
- [Dataset](#dataset)
- [Insights](#insights)
  * [Executive Summary](executive-summary)
  * [Product Insights](product-insights)
  * [Demographic and Geographic](demographic-and-geographic)
- [Recommendations](#recommendation)

## Project Background
Redblue Telco is a telecommunications company in the state of california that provides home phone and internet sevices to customers over more than 1000 cities and zip codes. 

By the end of the last quarter, the company have a critical problem about 28% of their customers decided on not renewing their subscribtions, meaning the customer churn rate is very high and above the goal of 10%, and the company is now facing a big challenge on retaining its customers. So, this project thoroughly analyses to uncover the factors leading to high customer churn rates and to help business stakeholders understand why customers leave and what can be done to retain them. 

Insights and recommendations are provided on the following key areas:
- **Churn Analysis**: Identification of factors that influence churn.
- **Product Level Performance**: An analysis of Redblue's various product lines, understanding their impact on churn.
- **Marketing Campaign Success**: An assessment of the marketing campaign on customer churn.
- **Regional and Demographical Comparison**: An evaluation of churn by region and demographic.

## Dataset
The dataset contains many fields including customer data, product data, order data, sales data, geographic data, and churn data.

## Insights
### Executive Summary
At the start of the last quarter, Redblue Telco had 6,589 customers with an average revenue per user of $268.64. However, by the end of the quarter, 1869 of its customers (around 28% of them) had decided not to renew their subscriptions, mostly due to offers and device quality that were inferior compared to competitors and the lack of professionalism in the attitude of support staff. As a result, company lost around 31% of its revenue in the following quarter. 

The fact that churned customers had higher quarterly ARPU than retained customers explains why revenue churn was greater than customer churn. And they tended to churn early in their subscription lifecycle. These indicate churned customers are early-stage customers with high usage but weak retention.

<img width="999" height="599" alt="Home" src="https://github.com/user-attachments/assets/aba6ab35-7f29-47e9-922b-24e1be160447" />


### Product Insights
- More than half of the customers who received an offer E from marketing team, or more precisely 68%, decided not to renew their subcription. Around three times higher than the other offers.
- Fiber optic users made up the largest group, but 42% of them churned, that's the highest among all internet type.
- Nearly a half of all customers choosed month-to-month contract rather than the other two options which had longer term. But they were the ones with the highest churn rate, even more than 50%.
- In terms of services, internet service and unlimited data demonstrate relatively weak performance with regard to customer churn, customers who opted for these services had churn rate two to three higher than those who do not. On the other hand, online backup, online security, and tech support performed quite well in reducing customer churn. 

<img width="999" height="599" alt="Product Insight" src="https://github.com/user-attachments/assets/47450bd9-cfd3-44ef-9b4a-33865073603a" />


### Demographic and Geographic
- Customers who referred more acquintances to subscribe demonstrated more loyalty.
- Older customers were more likely to cancel their subscription. The 66-80 year-old customers had the highest churn rate.
- The Majority of Redblue's customers were from San Diego, but the customer churn rate for this city was the highest, at 67%.

<img width="999" height="599" alt="Demographic and Geographic" src="https://github.com/user-attachments/assets/6ebc3560-fa0a-4e7c-b22d-64a99a193def" />


## Recommendations
Based on the insights found, here are some recommended actions that might be applied to reduce the churn rate:
- Address the main reason for churn with several approaches:
  * **Increase the value of the company's offerings by providing more competitive packages, both in terms of price and features** in order to compete with competitors.
  * **Consider working with leading vendors to provide the latest and more attractive devices**.
  * **Improve customer support training to ensure a friendly, professional, and solutive attitude**.
- As churned customers tended to churn early in the subscription lifecycle, **focus on retaining early-stage customers**.
- Conduct an in-depth analysis of why Offer E was causing a high churn rate (68%). **Consider replacing or improving Offer E with a more relevant and engaging offer**.
- **Provide incentives to convert month-to-month customers to long-term contracts**, such as additional discounts or free premium services.
- **Conduct an evaluation of network quality and stability, installation processes, latency performance, complaint rates, and the effectiveness of after-sales service in fiber optic segment**. Fiber optic was the largest segment with highest churn. This indicates that customer acquisition was already excellent, but the customer experience still left something to be desired.
- **Maintain and expand services that reduce churn**. Online backup, online security and technical support have been shown to help reduce churn, so consider making these features part of standard packages, add-ons or bundles for customers at high risk of churn.
- **Offer referral incentives that also strengthen customer loyalty to the brand**. As customers who refer others were generally more loyal, referrals can be used not only for customer acquisition but also as an indicator of engagement.
- **Develop specific strategy for older customers**. They are likely to be more sensitive to service quality, clarity of information, and technical support.
- **Conduct deeper geographical analysis to understand why San Diego has a very high churn rate (67%)**. This city deserves to be priority for improvement because majority of customers were based here, so the impact on total revenue could be significant.

===

The SQL queries utilized to clean, organize, and prepare data to dashboard can be found [here](https://github.com/msyariffakhrezi/Customer-Churn-Analysis/blob/main/data%20cleaning.sql).

The interactive dashboard can be found [here](https://public.tableau.com/app/profile/muhamad.syarif.fakhrezi/viz/CustomerChurnAnalysis_17399800693450/Home?publish=yes).

The dataset can be found [here](https://github.com/msyariffakhrezi/Customer-Churn-Analysis/tree/main/dataset).
