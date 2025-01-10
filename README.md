# E-commerce

An e-commerce platform that provides a seamless online shopping experience, featuring user-friendly navigation, secure transactions, and comprehensive product management.

## Project Overview

In the dynamic world of e-commerce, data-driven insights are key to staying competitive. Our Power BI project provides an in-depth analysis of the O-List store's performance, offering valuable insights into sales trends, customer behavior, and product performance.

With interactive dashboards and detailed visualizations, we can track key metrics such as total sales, product-wise performance, and customer demographics. These insights enable us to optimize inventory, enhance customer experience, and drive strategic growth.

### 1. In this project scenario, I have been asked to create a dashboard for Olist, an e-commerce website. The stakeholder wants to know the insight of specific KPIs and any other valuable insights to share on the dashboard. The KPIs to show are given in the image below:

![image](https://github.com/user-attachments/assets/45a56d87-63fe-451e-9bee-15bd93f2b510)

## 2. Dataset
   
1.	Domain: e-commerce
2.	Project Name: Olist store Analysis
3.	Dataset Name: Total 9 Files
4.	Data Type: CSV Data
5.	Data set zip Folder Size: 45 MB

## 3. Data Cleaning

I cleaned the data in Excel before importing it to PowerBI, I explored the data to find any inconsistencies, duplicates, incorrect format, or missing values. I’ll share some of the inconsistencies and incorrect format I found and how I corrected them, for example in the customer dataset city names were in lower case I used the proper formula and with the help of the helper column I replaced the values. Then in the geolocation dataset, geolocation_city column names are in incorrect format and have special characters e.g £ and Ã , to check all the inconsistencies I used spell check and filter features. characters replaced: *,-, 4o. 4Âº ¡ © Â ³ “§ replaced with s” ¢ ª º.

![image](https://github.com/user-attachments/assets/1e17c223-1a23-46ef-8b0a-f6405a6cd78b)

In the product dataset, there was some empty product category name, and each product id is unique hence I removed those blank rows. In this way, I cleaned the dataset and then imported the files into PowerBI.

## 4. Transforming

After importing all the files, I created some extra columns while referencing the order purchase timestamp column to get insight into the day, month, and year of order like day of week, weekend/weekday in the order dataset.

![image](https://github.com/user-attachments/assets/854f0baf-7070-4dfa-9191-20ab95bc06a3)

## 5. Data Modelling

![image](https://github.com/user-attachments/assets/7e2a4eea-f8af-4bfc-bf06-d0fd18f6da52)

## Insights

## Weekday Vs Weekend Payment Statistics:

The Analysis of Payment Will give you an idea of understanding of buying behaviour of Customer. Here Majority of sales occurs on Weekdays which is 77% and Weekends account for the remaining 23%. here overall donut chart shows that weekdays are the most important time to focus on sales.

## Average Shipping Days for Petshop Category :

The average shipping days Time for the Petshop Category takes 11 days for Shipping, this chart helps to identify areas where they can improve their delivery time maintain customer satisfaction, and meet the expectations of their customers.

## Review scores and Payment Type:

Here the visual shows the distribution of orders by payment types. the most Used Payment type is Credit card 46K of orders, boleto is 2nd place , vouchers are the least used Payment types This analysis helps in understanding How customer Satisfaction and their payment preferences use this information to identify satisfied customers and encourage them to make repeat purchases.

## Average Price and Average Payment Value of Sao Paulo City:

average price and average payment value both are higher in the city of Sao Paulo than in other cities this suggests that the cost of Living is high in Sao Paulo city.

## Average shipping days vs Review Scores :

The average shipping days for products with a review of 1,2 stars are higher than the average shipping days for products with reviews of , 3, 4, and 5 stars. This Analysis suggests that customers who receive their products late are more likely to leave negative reviews.

## Year Wise Sales:

Sales have been increasing steadily each year because the global economy is growing, *more people are using digital payments.

![image](https://github.com/user-attachments/assets/767ac1b6-fc77-4309-980f-a533b732e554)
