# Testing Assumptions in Linear Regression 

When using **linear regression** for predictive modeling, it's critical to validate that certain assumptions hold. This helps ensure reliable and interpretable results.

## Key Assumptions

Linear regression assumes:
1. **Linearity**: The relationship between predictors and the outcome is linear.
2. **Independence**: Observations are independent of each other.
3. **Homoscedasticity**: Constant variance of errors.
4. **Normality**: Errors are normally distributed.
5. **No Multicollinearity**: Predictors are not highly correlated with each other.

Each of these assumptions should be tested before relying on the model.

### Testing Linearity

To test for linearity:
- **Scatterplots** of each predictor against the outcome variable
- **Residual vs. Fitted Plot**: Residuals should show no clear pattern.

### Testing Independence

To verify independence:
1. **Durbin-Watson Test**: Tests for autocorrelation.
2. **Residuals vs. Time Plot**: Useful for time series data to check for patterns.

### Checking Homoscedasticity

**Homoscedasticity** implies that residuals have constant variance across all levels of the predictor variables. Use:
- Residuals vs. Fitted plot to visually inspect variance.
- **Breusch-Pagan Test** to statistically check for heteroscedasticity.

### Testing Normality

Normality can be assessed by examining the **distribution of residuals**:
- **Histogram** or **QQ Plot** to check for approximate normal distribution.
- **Shapiro-Wilk Test** as a statistical test for normality.

### Multicollinearity

To test for multicollinearity:
- Calculate the **Variance Inflation Factor (VIF)** for each predictor.
- A high `VIF` (generally > 10) indicates potential multicollinearity problems.

## Summary

Testing and validating assumptions in **linear regression** is essential for building accurate models. Failing to validate these assumptions can lead to unreliable results.

![Linear Regression Assumptions](https://www.example.com/image-link "Linear Regression Assumptions")

> "Assumptions are the foundation of reliable models. Verify them to ensure accurate predictions and interpretations."

## Further Reading

For more details on linear regression assumptions, visit:
- [Introduction to Linear Regression](https://www.statisticssolutions.com/what-is-linear-regression/)