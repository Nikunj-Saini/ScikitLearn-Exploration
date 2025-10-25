
# Day 67 – Ridge & Lasso Regression with Scikit-Learn

Today, I learned about **Regularization** — a method to reduce overfitting in linear models by penalizing large coefficients.

##  What I Learned
- **Overfitting** occurs when the model learns noise instead of pattern.
- **Ridge Regression (L2 Regularization):**
  - Adds the square of coefficients as penalty.
  - Shrinks coefficients but doesn’t make them zero.
- **Lasso Regression (L1 Regularization):**
  - Adds absolute value of coefficients as penalty.
  - Can shrink some coefficients to zero (feature selection).
- Implemented both models using `Ridge` and `Lasso` from Scikit-Learn.
- Compared results with a standard Linear Regression model.

##  Code Summary
- Generated synthetic data with multiple features.
- Trained Linear, Ridge, and Lasso Regression models.
- Compared metrics and visualized coefficient shrinkage.

##  Next Step
Tomorrow, I’ll study **Logistic Regression**, which is used for classification problems.

---

*Repository:* [ScikitLearn-Learning-Series](https://github.com/nikunjsaini/ScikitLearn-Learning-Series)
