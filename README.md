1. Mean Absolute Error (MAE)
   Definition:
   MAE measures the average absolute difference between the predicted values and the actual values. It gives a straightforward interpretation of how far off, on average, the predictions are from the true values.

In this assignment, the MAE is 10.07, which is a pretty high number, so the predictions are not accurate.

2. Mean Squared Error (MSE)
   Definition:
   MSE is the average of the squared differences between predicted and actual values. Squaring emphasizes larger errors more heavily.

The MSE is really high (161.69), which indicates a huge fault in the data.

3. Root Mean Squared Error (RMSE)
   Definition:
   RMSE is simply the square root of MSE. It brings the error metric back to the same scale as the target variable, making it more interpretable.

Since RMSE is the square root of MSE, then the value of it will be the square root of 161.69, which is 12.72. The model predicts 12.72 percentage points off from the actual discount.

# 📈 Model Evaluation Metrics

## 1. **Mean Absolute Error (MAE)**

**Definition:**  
MAE measures the average absolute difference between the predicted values and the actual values. It provides a straightforward interpretation of how far off, on average, the predictions are from the true values.

**Result:**  
`MAE = 10.07`

**Interpretation:**  
A mean absolute error of 10.07 indicates that, on average, the model's predictions are about 10 percentage points away from the actual discounts. This is relatively high and shows that the model's predictions are not very accurate.

---

## 2. **Mean Squared Error (MSE)**

**Definition:**  
MSE is the average of the squared differences between predicted and actual values. By squaring the errors, it penalizes larger errors more than smaller ones.

**Result:**  
`MSE = 161.69`

**Interpretation:**  
This high MSE value suggests that the model is making large errors in some predictions. It indicates a significant flaw, possibly in the model, features, or data quality.

---

## 3. **Root Mean Squared Error (RMSE)**

**Definition:**  
RMSE is the square root of the MSE. It brings the error metric back to the same scale as the target variable, which in this case is the discount percentage.

**Result:**  
`RMSE = √161.69 ≈ 12.72`

**Interpretation:**  
An RMSE of 12.72 means the model's predictions are, on average, about 12.72 percentage points off from the actual discounts. This reinforces that the model may not be performing well and needs further tuning or data cleaning.

---

## 4. **R² Score (Coefficient of Determination)**

**Definition:**
R² shows how well the model explains the variability of the target variable. A value of 1 means perfect prediction, while 0 means no explanatory power.

**Result:**
`R² = 0.67`

**Interpretation:**
The model explains about 67% of the variance in discount percentages, which is a moderately strong result. It shows that the model captures a good portion of the pattern in the data, though there's still room to improve by refining the features or exploring more complex models.
