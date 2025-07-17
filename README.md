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
    
## 🔧 Project Pipeline

  ### 1. 🧼 Data Preprocessing & Feature Engineering
    - Parsed timestamps to calculate actual delivery duration (target)
  
    - Extracted hour of day and day of week features
      
      - Handled missing values
      
      - Encoded categorical features
  
  ### 2. 📈 Exploratory Data Analysis
      - Visualized distributions and relationships using countplots and scatterplots
      
      - Detected and removed outliers
  
  ### 3. 🤖 Model Building
      - Split data into training and test sets
      
      - Applied feature scaling for neural networks
      
      - Built a regression neural network using TensorFlow/Keras
      
      - Tuned hyperparameters (activation functions, optimizers, epochs)
  
  ### 4. 📉 Model Evaluation
      - Tracked training with loss curves
      
      - Evaluated performance using:
      
      - Mean Squared Error (MSE)
      
      - Root Mean Squared Error (RMSE)
      
      - Mean Absolute Error (MAE)

## 📚 Tech Stack Used
      - Python (Pandas, NumPy, Matplotlib, Seaborn)
      
      - Scikit-learn
      
      - TensorFlow / Keras
      
## 🚀 Future Improvements
      - Tried ensemble models (Random Forest, XGBoost)
      
      - Hyperparameter tuning via GridSearch
## 📌 Results
      - Achieved reasonable accuracy using a custom neural network to estimate delivery times, helping improve ETAs shown to customers.
      
Feel free to ⭐ this repo if you find it helpful!




 
