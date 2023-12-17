# CLV Prediction Using BG-NBD and Gamma-Gamma Models

## Business Problem

FLO aims to outline a roadmap for its sales and marketing endeavors. In order for the company to formulate medium to
long-term plans effectively, it is essential to anticipate the potential value that current customers will contribute to
the company in the future.

## Dataset Story

The dataset consists of information obtained from the historical shopping behaviors of customers who engaged in
OmniChannel (both online and offline shopping) for their latest purchases from Flo during the years 2020-2021.

## Features

- `master_id` - Unique customer identifier
- `order_channel` - Indication of the platform used for shopping (Android, iOS, Desktop, Mobile)
- `last_order_channel` - The channel used for the most recent purchase
- `first_order_date` - Date of the customer's initial purchase
- `last_order_date` - Date of the customer's most recent purchase
- `last_order_date_online` - Date of the customer's last online purchase
- `last_order_date_offline` - Date of the customer's last offline purchase
- `order_num_total_ever_online` - Total number of purchases made online by the customer
- `order_num_total_ever_offline` - Total number of purchases made offline by the customer
- `customer_value_total_ever_offline` - Total amount spent by the customer in offline purchases
- `customer_value_total_ever_online` - Total amount spent by the customer in online purchases
- `interested_in_categories_12` - List of categories in which the customer has made purchases in the last 12 months