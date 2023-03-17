# Introduction

## Dataset Description
Brazilian E-Commerce Public Dataset by Olist

The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil.

This is real commercial data, it has been anonymised.

This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.

After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments

**Data Diagram:**
![image](https://user-images.githubusercontent.com/104210926/191186082-c3773020-101a-4f09-9c38-270b3ee49f26.png)

## Problem Definition
**The notebook will present 3 goals of analysis to help more understand about Olist as below:**
1. Olist number of orders analysis monthly 
2. Utilize descriptive analytics to get insights on how delivery affects the number of orders
3. Solution to improve delivery % build a linear regression model to predict delivery time

## Conclusions
1. Order growth unusual since 11-2017 go with lots of 1 & 2-star reviews.
2. Customers complain the most about two things:
    - Product quality (Low quality, wrong product, etc.)
    - Delivery (Late, not as expected, damaged package, etc.)
3. It takes about 83 hours (3.4 days) to prepare the seller's goods for the carrier during peak times, which is 25% of the total delivery time.
4. Since 03-2018, a delivery time has improved, but the cost is increasing. Orders number tend to decrease during this period.
5. Delivery Late Rate, Delivery Time and Delivery Freight affect the number of orders.

## Solutions
**Improve Delivery Freight**
1. Solution:
    - Olists continues to deliver orders booked at São Paulo state
    - Olists should find Third-party logistics providers to provide goods that are outside of São Paulo state
2. Evaluation:
    - Third-party logistics providers have substantial experience, technology, and warehousing spread all over the city → Reduce delivery freight
    - Back in 2015 and 2016, when Shopee entered the Vietnam e-commerce market, they do not have much experience in supply chain fields in VietNam, so they cooperated with Third-Party Logistics.

**Improve Delivery Time**
1. Set a target for the seller to deliver cargo to the carrier within a time.
2. Evaluation: 
    - Top e-commerce companies like Shopee, Lazada have applied target for goods preparation time. 
    - Warn seller about peak day (Afternoon; Beginning of the week; 1 week before the end of the month; Black Friday, Valentine, ...)

**Predict Delivery Time - Improve Late Delivery Rate**

→ Reduce 2.2% Delivery Late Rate

