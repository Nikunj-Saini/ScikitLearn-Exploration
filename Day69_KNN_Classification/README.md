# Day 69 – K-Nearest Neighbors (KNN) Classification with Scikit-Learn

Today, I learned how **K-Nearest Neighbors (KNN)** works — a simple yet powerful classification algorithm that makes predictions based on the closest data points.

##  What I Learned
- KNN is a **non-parametric**, **instance-based** learning algorithm.
- It classifies new data points by looking at the **k nearest neighbors** in the training data and taking a majority vote.
- Steps I practiced:
  - Generated sample data using `make_classification`
  - Trained and tested KNN with different k values
  - Visualized decision boundaries
  - Compared performance for multiple k values

##  Key Parameters
- `n_neighbors`: Number of nearest neighbors (k)
- `metric`: Distance metric (default: Euclidean)
- `weights`: Determines how neighbors contribute to classification (`uniform` or `distance`)

##  Evaluation
- Used accuracy score and confusion matrix for performance evaluation.
- Observed how changing *k* affects model bias and variance.

##  Next Step
Next, I’ll move to **Support Vector Machines (SVM)** — a powerful algorithm for both linear and non-linear classification.


