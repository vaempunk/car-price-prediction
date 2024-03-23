# Car price prediction

Predict car price by characteristics ([Kaggle competition link](https://www.kaggle.com/competitions/autoam-car-price-prediction))

## Data

**Features**:

- model
- year
- motor_type
- running
- color
- type
- status
- motor_volume
- price

**Samples**: 1642

## Metrics

MAE = $\sum_{i=1}^n |f(x_i) - y_i|$

## Model

LightGBM (gradient boosting with decision tree)
