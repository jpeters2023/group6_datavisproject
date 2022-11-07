# Data Visualization and Analysis on Olist's profitability 

## What issues or questions are we adressing:

Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners

The purpose of our analysis will be threefold:

1.  **The product-dimension**: We will be analyzing the performance and profitability of various products independent of their locations

2.  **The customer-dimension**: We will analyze the demographics of the customers ordering on Olist and we will try to identify who the most profitable customer segments are

3.  **The location-dimension**: The data-set provides longitude and lattitude coordinates for their customers and sellers. We can then analyze what regions or cities are more profitable and how profitable the shipping of products relates to their location.

## What is the source of data we will be using

The source of data we will be using is the free *"Brazilian E-Commerce Public Dataset by Olist"* dataset. This data set is available on the following link: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The data set has information on 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. They also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

![alt text](https://i.imgur.com/HRhd2Y0.png)


## What statistical techniques will we be using:

1. We will be using hypothesis testing to validate the correlation between product profitability and other variables (e.g. location).

2. We will also be using clustering to cluster the different types of customers. 
