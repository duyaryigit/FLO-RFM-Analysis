## FLO-RFM-Analysis

- Recency, frequency, monetary value (RFM) is a model used in marketing analysis that segments a company’s consumer base by their purchasing patterns or habits. In particular, it evaluates customers’ recency (how long ago they made a purchase), frequency (how often they make purchases), and monetary value (how much money they spend).



![](image.jpg)

---

### Business Problem
- FLO wants to segment its customers and determine marketing strategies according to these segments. For this purpose, the behaviors of the customers will be defined and groups will be formed according to these behavior clusters.



---

### Dataset Story
- The dataset consists of information obtained from the past shopping behaviors of customers who made their last purchases as OmniChannel (both online and offline shopper) in 2020 - 2021.


|Value| Description                                         |
|:----|:----------------------------------------------------|
|**master_id :**| Unique client number                                   |
|**order_channel :**| Which channel of the shopping platform is used (Android, IOS, Desktop, Mobile, Offline)                |
|**last_order_channel :**| The channel where the last purchase was made |
|**first_order_date :** | The date of the customer's first purchase     |
|**last_order_date :**| The date of the last purchase made by the customer                                 |
|**last_order_date_online :**| The date of the last purchase made by the customer on the online platform                 |
|**last_order_date_offline :**| The date of the last purchase made by the customer on the offline platform |
|**order_num_total_ever_online :**| Total number of purchases made by the customer online      |                                
|**order_num_total_ever_offline :**| Total number of purchases made by the customer offline                |
|customer_value_total_ever_offline : | The total price paid by the customer for offline purchases |
|customer_value_total_ever_online : |The total price paid by the customer for their online shopping |
|**interested_in_categories_12 :**| List of categories the customer has purchased from in the last 12 months |

### seg_map:

<p align="center">
  <img src="https://github.com/duyaryigit/FLO-RFM-Analysis/blob/main/segments.png?raw=true" alt="RFM Segmentation"/>
</p>

---

The dataset is not shared because it's exclusive to Miuul Data Science & Machine Learning Bootcamp.
