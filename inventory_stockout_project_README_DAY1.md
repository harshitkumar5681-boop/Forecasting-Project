# Inventory Stockout Risk Prediction & Reorder Intelligence

## Project Overview

This project develops a data-driven inventory intelligence system that
predicts stockout risk and recommends optimal reorder quantities for
retail stores.

Retail businesses frequently lose revenue due to stockouts caused by
demand fluctuations, supplier delays, and poor inventory planning. This
system analyzes operational variables such as demand, stock levels,
supplier reliability, and promotions to predict stockout probability and
improve inventory decisions.

------------------------------------------------------------------------

## Problem Statement

Retailers struggle to maintain optimal inventory levels due to:

- long-term demand trends
- seasonal demand patterns
- promotional demand spikes
- supplier lead time variability

As a result: - products go out of stock - sales opportunities are lost -
customer satisfaction decreases

### Objective

Develop a predictive analytics system that: - identifies stockout risk

------------------------------------------------------------------------

## Dataset Description

  Feature                      Description
  ---------------------------- --------------------------------
  product_id                   Unique product identifier
  store_id                     Store location identifier
  current_stock                Current inventory level
  daily_demand                 Expected product demand
  lead_time_days               Supplier delivery time
  supplier_reliability_score   Supplier reliability metric
  promotion_active             Indicates promotional campaign
  weather_impact               External demand factor
  stockout_risk                Target variable (Yes/No)

------------------------------------------------------------------------

## Project Architecture

Dataset → Data Cleaning → Exploratory Data Analysis → Feature
Engineering → Machine Learning Model → Stockout Prediction 

------------------------------------------------------------------------

## Key Features

### 1. Stockout Risk Prediction

Predict the probability that a product will go out of stock.

### 2. Demand Pattern Analysis

Analyze demand variability due to promotions, supplier delays, and
external factors.

Visualize operational insights for inventory managers.

------------------------------------------------------------------------

## Technology Stack

**Programming** - Python

**Libraries** - pandas - numpy - scikit-learn - matplotlib - seaborn

**Version Control** -GitHub

------------------------------------------------------------------------

## Machine Learning Approach

Target Variable: stockout_risk

Algorithms: - Logistic Regression - Random Forest

Evaluation Metrics: - Accuracy - Precision - Recall - ROC-AUC

------------------------------------------------------------------------

## Business Impact

The system can help retailers:

-   reduce stockout events
-   improve demand forecasting
-   optimize reorder timing
-   improve inventory turnover

------------------------------------------------------------------------

## Project Structure

inventory-stockout-product/ │ ├── data/ │ └── inventory_dataset.csv │
├── notebooks/ │ └── exploratory_analysis.ipynb │ ├── models/ │ └──
stockout_model.pkl│ └── README.md

------------------------------------------------------------------------

## Author

Harshit Kumar
MBA Student- IIT (ISM) Dhanbad
