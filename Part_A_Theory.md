# Part A: Theory

## 1. What is Supervised Learning?

Supervised Learning is a machine learning technique in which a model learns from labeled data and predicts outputs for new data.

Example: Predicting house prices using house features.

---

## 2. Difference Between Regression and Classification

| Regression | Classification |
|------------|---------------|
| Predicts continuous values | Predicts categories |
| Output is a number | Output is a label |
| Example: House Price Prediction | Example: Spam Detection |

---

## 3. Simple Linear Regression

Simple Linear Regression is used to find the relationship between one independent variable and one dependent variable.

Formula:

y = mx + c

Where:
- y = Dependent Variable
- x = Independent Variable
- m = Slope
- c = Intercept

Example: Predicting house price using house area.

---

## 4. Assumptions of Linear Regression

1. Linear relationship between variables.
2. No multicollinearity among features.
3. Constant variance of errors (Homoscedasticity).
4. Errors are normally distributed.
5. Observations are independent.

---

## 5. Bias-Variance Tradeoff

- High Bias: Model is too simple and underfits the data.
- High Variance: Model is too complex and overfits the data.

A good model maintains a balance between bias and variance.

---

## 6. Overfitting and Underfitting

### Overfitting
- High training accuracy
- Low testing accuracy
- Poor generalization

### Underfitting
- Low training accuracy
- Low testing accuracy
- Poor performance

---

## 7. Gradient Descent

Gradient Descent is an optimization algorithm used to minimize model error.

### Types:
- Batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent

---

## 8. Evaluation Metrics

### MAE
Measures average absolute error.

### MSE
Measures average squared error.

### RMSE
Square root of MSE.

### R² Score
Measures how well the model explains variance.

- R² = 1 → Perfect model
- R² = 0 → Poor model

---

## 9. Conclusion

Regression models are used to predict continuous values such as house prices. Comparing different regression models helps identify the most accurate model.
