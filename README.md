# Porter Delivery Time Prediction
This project aims to build a regression model that accurately predicts the delivery time for food orders made via Porter, India's leading intra-city logistics platform.

## Problem Statement
Porter partners with various restaurants to deliver food to customers. The objective is to estimate the delivery time for an order using historical data that includes order details, restaurant info, and delivery partner availability.
## Dataset Overview
Each row in the dataset corresponds to a unique delivery. Key features include:

  - **created_at, actual_delivery_time:** Timestamps to compute delivery duration
  
  - **store_primary_category:** Restaurant category
  
  - **order_protocol:** Order placement method
  
  - **total_items, num_distinct_items, subtotal:** Order composition
  
  - **total_onshift_partners, total_busy_partners:** Delivery partner availability
  
  - **estimated_store_to_consumer_driving_duration:** Approx. travel time




 
