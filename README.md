# pCLV-and-MBA

## Project Overview
In this project, I used an open-source dataset of online retail transactions, available at UCI Online Retail Dataset. This dataset spans two years and includes fields such as invoice number, stock code, description, quantity, invoice date, price, customer ID, and country. The goal of this project was to build models that predict Customer Lifetime Value (CLV) and gain insights into customer purchasing patterns.

## Customer Lifetime Value (CLV)
CLV is a metric that represents the total revenue a company expects to earn from a customer over the entire duration of their relationship. Predicting CLV can offer several benefits to businesses:

Customer Retention: Identifying customers with a high CLV allows businesses to target retention efforts, improving long-term profitability.
Financial Forecasting: CLV serves as a key metric for predicting future revenue and cash flow, helping businesses plan for long-term growth.
Resource Allocation: By understanding the future value of different customer segments, businesses can allocate resources more effectively.

## Market Basket Analysis (MBA)
Additionally, I performed a Market Basket Analysis to uncover trends in customer buying behavior and identify associations between products.

Project Steps
1. Exploratory Data Analysis (EDA): This step involved cleaning and transforming the dataset to prepare it for modeling, including handling missing data and ensuring the data was properly formatted.

2. Modeling CLV: I used the BG/NBD (Beta-Geometric / Negative Binomial Distribution) and Gamma-Gamma models to predict CLV based on customer transaction data.

3. Market Basket Analysis: Using the Apriori algorithm, I performed an association rule mining analysis to identify common purchasing patterns among customers.
