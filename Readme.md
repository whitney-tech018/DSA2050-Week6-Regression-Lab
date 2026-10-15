DSA2050 Week 6: Guided Regression Lab

Whitney Jebor - 673308

Lab Objective

The objective of this lab was to build and evaluate regression models to predict sales revenue using advertising spend, store visits, discount percentage, region, customer segment, and product category.

Models Compared

- Mean Baseline
- Median Baseline
- Linear Regression
- Ridge Regression
- Decision Tree Regression

Best Model and Selected MAE

Ridge Regression with alpha = 10 achieved the lowest test MAE of KES 13,624.90. This means its predictions differed from actual sales by approximately KES 13,625 on average.

Two Key Findings

1. Ridge Regression performed substantially better than the mean and median baselines, which had negative R² values.
2. Prediction errors differed across customer segments, with Retail having the highest MAE and SME the lowest. The deep Decision Tree also showed overfitting, with zero training MAE but a much higher test MAE.

Three Limitations

1. The dataset contains only 320 observations, which may not represent all real-world sales patterns.
2. The model excludes potentially important factors such as seasonality, competitor prices, and changing customer demand.
3. The model requires further validation on new data to confirm that its performance remains reliable over time.