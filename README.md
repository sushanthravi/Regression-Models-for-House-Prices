# Regression-Models-for-House-Prices
In this project, we applied various regression techniques, including **linear regression**, **ridge regression**, **lasso regression**, and **elastic net**, to predict **house prices** using a provided dataset of housing attributes.


The main focus was on understanding how regularization techniques can improve model performance by reducing overfitting and selecting relevant features.

---

### Key Steps:

1. **Data Preparation**:
   - The dataset included features like the number of bedrooms, bathrooms, living area, and other housing attributes. We split the data into training and test sets (75%/25%) and scaled the features to ensure each variable contributes equally to the regularization.

2. **Linear Regression**:
   - We started with a simple linear regression model, which helped establish a baseline for performance using **Mean Squared Error (MSE)** and **R-squared** values.

3. **Ridge and Lasso Regression**:
   - We implemented both ridge and lasso regression to tackle overfitting. Using **cross-validation**, we optimized the regularization parameter (\(\alpha\)) for each model, which controls the strength of the regularization.
   - We observed that **ridge regression** works by shrinking the coefficients without eliminating any features, while **lasso regression** performs feature selection by forcing some coefficients to zero, producing a more interpretable model.

4. **Elastic Net**:
   - Combining the strengths of both ridge and lasso, **elastic net** was used to handle correlated features and provide a balance between regularization and feature selection.

5. **Coefficient Analysis**:
   - For all models (ridge, lasso, and elastic net), we visualized how the coefficients change with varying \(\alpha\) values. This allowed us to see how regularization impacts the feature importance and model complexity.

6. **Model Evaluation**:
   - After training the models, we evaluated them on the test data using **MSE** and **R-squared**. We compared the performance of the different models and analyzed the effect of scaling on the results.

---

### Conclusion:
This project provided a thorough exploration of how **regularization techniques** like ridge, lasso, and elastic net can improve the performance of regression models, particularly in scenarios where multicollinearity or overfitting may arise. By balancing bias and variance, these techniques ensure a more robust predictive model for house prices.

### Group Members:
- **Sushanth Ravichandran**
- **Sankeerth Viswanadhuni**
