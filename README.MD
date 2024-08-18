# Meal Delivery Demand Forecasting

## Project Overview

This project focuses on analyzing a dataset from a meal delivery company that operates across various cities. The dataset contains detailed information on meal orders, including pricing, promotions, and order quantities. The primary goal is to forecast meal demand and understand the impact of various factors such as pricing, email promotions, and homepage features on the number of orders.

## Dataset Description

The dataset consists of the following columns:

- **id:** Unique identifier for each record.
- **week:** The week number during which the data was recorded.
- **center_id:** Identifier for the fulfillment center responsible for dispatching the meal orders.
- **meal_id:** Identifier for the specific meal being ordered.
- **checkout_price:** The price at which a customer checks out with their meal.
- **base_price:** The original (base) price of the meal.
- **emailer_for_promotion:** A binary variable (0 or 1) indicating whether an email promotion was used.
- **homepage_featured:** A binary variable (0 or 1) indicating whether the meal was featured on the homepage.
- **num_orders:** The number of meal orders for a given instance (target variable).

## Project Objectives

1. **Exploratory Data Analysis (EDA):**
   - Analyze trends in meal orders over time.
   - Explore the relationship between pricing, promotions, and order volumes.
   - Identify any seasonal patterns or trends in the data.

2. **Feature Engineering:**
   - Create new features such as price discounts and lagged order variables.
   - Explore interactions between promotional features to capture combined effects.

3. **Demand Forecasting:**
   - Implement time-series forecasting models like ARIMA, SARIMA, and Prophet.
   - Build regression models to predict the number of orders based on features.
   - Perform causal analysis to understand the impact of promotions on order volumes.

4. **Model Evaluation:**
   - Evaluate time-series models using metrics like MAE, RMSE, and MAPE.
   - Cross-validate regression models to ensure robust predictions.

5. **Business Optimization:**
   - Use insights from the analysis to recommend strategies for pricing, promotions, and resource allocation.

## Files in Repository

- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Jupyter notebooks containing EDA, feature engineering, and modeling steps.
- `models/`: Trained models and scripts for demand forecasting.
- `reports/`: Summary reports and visualizations of key findings.
- `README.md`: Project overview and instructions.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone  https://github.com/kiplah/Meal-Delivery-Data-analysis-with-Python.git
   cd Meal-Delivery-Data-analysis-with-Python
