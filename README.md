# FLO-RFM-Analysis

- Recency, frequency, monetary value (RFM) is a model used in marketing analysis that segments a company’s consumer base by their purchasing patterns or habits. In particular, it evaluates customers’ recency (how long ago they made a purchase), frequency (how often they make purchases), and monetary value (how much money they spend).

# Business Problem
- FLO wants to segment its customers and determine marketing strategies according to these segments.For this, the behavior of the customers will be defined and groups will be formed according to these behavior clusters.

# Dataset Story
- The dataset consists of information obtained from the past shopping behaviors of customers who made their last purchases as OmniChannel (both online and offline shopper) in 2020 - 2021.

- master_id: Unique client number
- order_channel : Which channel of the shopping platform is used (Android, ios, Desktop, Mobile, Offline)
- last_order_channel : The channel where the last purchase was made
- first_order_date : The date of the customer's first purchase
- last_order_date : The date of the last purchase made by the customer
- last_order_date_online : The date of the last purchase made by the customer on the online platform
- last_order_date_offline : The date of the last purchase made by the customer on the offline platform
- order_num_total_ever_online : The total number of purchases made by the customer on the online platform
- order_num_total_ever_offline : Total number of purchases made by the customer offline
- customer_value_total_ever_offline : The total price paid by the customer for offline purchases
- customer_value_total_ever_online : The total price paid by the customer for their online shopping
- interested_in_categories_12 : List of categories the customer has purchased from in the last 12 months
