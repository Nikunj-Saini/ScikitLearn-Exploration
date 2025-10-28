# Day 68 – Logistic Regression (Classification) with Scikit-Learn

Today, I began my journey into **Classification Algorithms** by learning **Logistic Regression** — a method used for binary classification.

##  What I Learned
- Logistic Regression predicts **probabilities** using the **sigmoid function**:
  \[
  P(y=1) = \frac{1}{1 + e^{-(b_0 + b_1x_1 + ... + b_nx_n)}}
  \]
- The output is between 0 and 1, representing the probability of a class. 
- Steps followed:
  - Loaded a binary classification dataset
  - Trained a Logistic Regression model using Scikit-Learn
  - Evaluated using **accuracy**, **confusion matrix**, and **classification report**
- Visualized decision boundaries for better understanding.

##  Code Summary
- Used `make_classification` from Scikit-Learn to generate binary data.
- Trained and tested a Logistic Regression classifier.
- Compared predicted vs actual values and visualized results.

##  Next Step
Tomorrow, I’ll move to **K-Nearest Neighbors (KNN)** — another popular classification algorithm.

---

*Repository:* [ScikitLearn-Learning-Series](https://github.com/nikunjsaini/ScikitLearn-Learning-Series)
