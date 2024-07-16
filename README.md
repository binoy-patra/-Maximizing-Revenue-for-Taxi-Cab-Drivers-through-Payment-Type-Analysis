# Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

## Introduction
In the fast-paced taxi booking sector, optimizing revenue is essential for long-term success and driver satisfaction. Our goal is to use data-driven insights to maximize revenue streams for taxi drivers. This project aims to determine whether payment methods impact fare pricing by focusing on the relationship between payment type and fare amount.

## Business Problem
Understanding the relationship between payment methods and fare amounts can provide strategic insights for taxi companies. By analyzing this relationship, taxi companies can develop strategies to encourage payment methods that maximize revenue for drivers.

## Objective
The primary objective of this project is to run a hypeothesis test to examine the relationship between the total fare and the method of payment. We use Python hypothesis testing and descriptive statistics to extract useful information that can help taxi drivers generate more cash. Specifically, we want to find out if there is a significant difference in fares for those who pay with credit cards versus those who pay with cash.

## Research Question
Is there a relationship between the total fare amount and the payment type, and can we nudge customers towards payment methods that generate higher revenue for drivers without negatively impacting customer experience?

## Methodology
1. **Data Collection and Processing**
2. **Descriptive Analysis**
3. **Hypothesis Testing**

## Dataset Overview
Dataset Credit: [data.world](https://data.world/)
- **Total Observations**: 6,405,008
- **Total Columns**: 18
- **Columns Used**: 'passenger_count', 'trip_distance', 'duration', 'payment_type', 'fare_amount'

## Descriptive Analysis

### Journey Insights
![Images](https://github.com/binoy-patra/Maximizing-Revenue-for-Taxi-Cab-Drivers-through-Payment-Type-Analysis/blob/main/Journey%20insights.png)
![image](https://github.com/user-attachments/assets/6baef384-1222-4155-aa1c-f49b8bdc5b06)

**Insights**
- Credit card payments show a higher average fare of $13.60 with greater variability ($6.37 standarddeviation) compared to cash payments, which average $12.18 with a standard deviation of $6.13.
- This suggests potential opportunities for revenue optimization through targeted payment method incentives in taxi services.


### Preference of Payment Types
![Images](https://github.com/binoy-patra/Maximizing-Revenue-for-Taxi-Cab-Drivers-through-Payment-Type-Analysis/blob/main/Payment%20Type%20Ref.png)

**Insights**
- **Cash**: 32.5%
- **Card**: 67.5%

The proportion of customers paying with cards is significantly higher than those paying with cash, with card payments accounting for 67.5% of all transactions compared to cash payments at 32.5%. This indicates a strong preference among customers for using card payments over cash, potentially due to convenience, security, or incentives offered for card transactions.

### Passenger Count Analysis
![Images](https://github.com/binoy-patra/Maximizing-Revenue-for-Taxi-Cab-Drivers-through-Payment-Type-Analysis/blob/main/Passenger%20Count%20Analysis.png)

**Insights**
- Among card payments, rides with a single passenger (passenger_count = 1) comprise the largest proportion, constituting 40.08% of all card transactions.
- Similarly, cash payments are predominantly associated with single-passenger rides, making up 20.04% of all cash transactions.
- There is a noticeable decrease in the percentage of transactions as the passenger count increases, suggesting that larger groups are less likely to use taxis or may opt for alternative payment methods.

These insights emphasize the importance of considering both payment method and passenger count when analyzing transaction data, as they provide valuable insights into customer behavior and preferences.

### Hypothesis Testing and Result
- **Null hypothesis**: There is no difference in average fare between customers who use credit cards and customers who use cash.
- **Alternative hypothesis**: There is a difference in average fare between customers who use credit cards and customers who use cash.

With a T-statistic of 165.5 and a P-value of less than 0.05, we reject the null hypothesis, suggesting that there is indeed a significant difference in average fare between the two payment methods.

### Recommendations
1. **Encourage Credit Card Payments**:
   - Implement incentives or discounts for credit card transactions to encourage more customers to use this payment method.
   - Enhance security and convenience of credit card transactions to boost adoption rates.

2. **Optimize Payment Infrastructure**:
   - Invest in reliable and efficient payment processing systems to minimize transaction failures and delays, ensuring a smooth experience for customers using credit cards.

This structured approach provides a comprehensive view of how payment methods impact fare amounts and offers strategic recommendations to maximize revenue for taxi cab drivers.

## Conclusion
Based on our analysis, we found that credit card payments are associated with higher fare amounts compared to cash payments. Encouraging customers to pay with credit cards can help taxi drivers maximize their revenue. Implementing strategies such as offering incentives for credit card transactions and enhancing the convenience and security of credit card payments can drive higher adoption rates and ultimately boost revenue.

## Contact
For any questions or further information, please contact me at [binoypatra20@gmail.com](mailto:binoypatra20@gmail.com).
