# Restaurant Food Demand Prediction and Inventory Planning Using Machine Learning

## Project Overview

This project focuses on predicting food demand using historical food order data and Machine Learning techniques.

Accurate demand forecasting can help food-service businesses plan food preparation, manage inventory, reduce food wastage, and avoid stock shortages.

The project uses historical food demand data along with information related to meals, fulfilment centers, pricing, promotions, and operational characteristics.

Three Machine Learning models were implemented and compared:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Based on the evaluation results, Random Forest Regressor was selected as the final model.

---

## Objectives

The main objectives of this project are:

1. To analyze historical food demand data.
2. To integrate food, meal, and fulfilment center information.
3. To perform Exploratory Data Analysis (EDA).
4. To identify important factors affecting food demand.
5. To engineer useful features such as discount and price ratio.
6. To develop Machine Learning models for demand prediction.
7. To compare different regression models.
8. To select the best-performing model.
9. To generate future food demand predictions.
10. To support inventory and food preparation planning.

---

## Dataset

The project uses a Kaggle-origin food demand forecasting dataset.

The dataset contains information related to:

- Food orders
- Meal categories
- Cuisine types
- Meal prices
- Promotions
- Homepage featuring
- Fulfilment centers
- City and region information
- Operational area

### Dataset Files

The project uses the following files:

```text
train.csv
test_QoiMO9B.csv
meal_info.csv
fulfilment_center_info.csv
