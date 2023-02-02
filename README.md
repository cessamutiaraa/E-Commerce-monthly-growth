# Summary
This project focused on analyzing the monthly growth of completed orders and revenue of The Look E-Commerce (fictitious E-Commerce on Google BigQuery) in percentage breakdown by product categories and analyze the profit-to-cost ration to gain insight (time frame Jan 2019 - Apr 2022) using SQL-Google BigQuery

# Dataset
The dataset used is The Look E-Commerce (fictitious clothing site in Google Bigquery) in Jan 2019 - Apr 2022. https://console.cloud.google.com/marketplace/product/bigquery-public-data/thelook-ecommerce?q=search&referrer=search&project=sincere-torch-350709

# Project Goal
Analyzing the monthly growth of TPO (# of completed orders) and TPV (# of revenue) in percentage breakdown by product categories and analyze the monthly growth to gain insight (time frame Jan 2019 - Apr 2022)

# Methodology
## Data Preparation & Cleaning
Query process was done on Google BigQuery https://console.cloud.google.com/bigquery?sq=630202522940:b721f92aa5cb4b89a2729c8cc78c88d4

### Monthly Growth

![image](https://user-images.githubusercontent.com/123222363/216271557-3237a504-2bd0-49df-903d-5ea46af507cc.png)
![image](https://user-images.githubusercontent.com/123222363/216271594-17cf9f08-d8c7-4602-92a2-be498814c90e.png)

The query resulted the monthly growth of TPV (# of revenue) and TPO (# Completed Order) by product categories from the time frame of Jan 2019 - Apr 2022.

### Profit-to-cost Ratio

![image](https://user-images.githubusercontent.com/123222363/216274430-c821424e-0619-455b-abd2-d41f8edaa56c.png)
![image](https://user-images.githubusercontent.com/123222363/216274574-7ae47fc1-bff9-4c97-80b9-a386574f0871.png)

## Data Analysis & Visualization

The result of the query was being processed on Google Sheet for further analysis https://docs.google.com/spreadsheets/d/1laorOAUSSmrKfm_VrzAKNma0mSwu1AxeZzLEx496tuQ/edit?usp=sharing

From the time frame of 2019 - 2022 , a large drop of Avg TPV and Avg TPO of all products category occured in 2020,before the curve started to show the downtrend until 2022 (In 2022, the data provided only from Jan - June).
![image](https://user-images.githubusercontent.com/123222363/216272648-5228952e-6d96-4955-a151-6a811da1ff31.png)
![image](https://user-images.githubusercontent.com/123222363/216272816-4902b772-5ba1-4018-8bba-b4cd6339e3c7.png)

From the above graph of profit to cost ratio from 2019 - 2022, the product category that had the lowest ratio was Clothing Sets. And the highest ratio was Blazers & Jackets. We could say that Blazer & Jackets had a better return of investment compared to the rest categories.

## Insight & Recommendation
The profit to cost ratio of each product category shows the total profit compared with the total cost as well as the return of investment, and indirectly indicates the customer’s consumption pattern. And the Avg TPV and Avg TPO showed the downward trend for the last 3.5 years,
From the analysis, TheLook eCommerce needs to evaluate the product category that they sell in their marketplace to match their customer’s consumption pattern and boost their TPV and TPO, so does the profit.
