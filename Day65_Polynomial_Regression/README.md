# Day 65 – Polynomial Regression with Scikit-Learn

Today, I explored **Polynomial Regression**, an advanced version of Linear Regression that allows us to model **curved (non-linear)** relationships between features and the target variable.

##  What I Learned
- Linear Regression fits a straight line — but many real-world relationships are non-linear.
- Polynomial Regression adds **squared, cubic, or higher-order terms** of features to capture curvature.
- Used `PolynomialFeatures` and `LinearRegression` from Scikit-Learn.
- Built a **pipeline** for easy transformation and model fitting.
- Compared Linear vs Polynomial fits visually.

##  Code Summary
- Generated non-linear synthetic data using `make_regression` + noise.
- Applied polynomial transformation (degree = 2 or 3).
- Trained a model and visualized the polynomial curve fit.

##  Next Step
Tomorrow, I’ll move to **Multiple Linear Regression**, exploring how to handle multiple features and interpret coefficients.

---


