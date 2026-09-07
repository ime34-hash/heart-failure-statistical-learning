# Heart Failure Statistical Learning
Statistical learning and machine learning analysis of clinical heart failure data using R.

This project applies progressively more advanced statistical learning methods to clinical and demographic data to evaluate predictors of heart failure outcomes and compare predictive modeling approaches.

## Methods

The analysis covers:

- Regression and classification
- Statistical inference
- Cross-validation and bootstrap resampling
- Model selection and regularization
- Principal components and partial least squares
- Nonlinear modeling and generalized additive models
- Classification and regression trees
- Bagging, random forests, boosting, and BART

## Analysis Notebooks

### 1. Regression & Statistical Inference
Examines relationships between clinical variables using regression modeling and statistical inference.

### 2. Classification & Predictive Modeling
Explores clinical predictors of mortality using classification and predictive modeling techniques.

### 3. Resampling & Model Validation
Uses cross-validation and bootstrap resampling to evaluate model performance and stability.

### 4. Model Selection & Regularization
Compares subset selection, stepwise selection, ridge regression, lasso, principal components regression, and partial least squares.

### 5. Nonlinear Modeling
Evaluates polynomial regression, splines, LOESS, and generalized additive models to capture nonlinear relationships.

### 6. Tree-Based Methods
Applies decision trees, pruning, bagging, random forests, boosting, and Bayesian Additive Regression Trees to classification and regression problems.

## Key Findings

- Increasing model complexity did not consistently improve predictive performance; simpler, more interpretable models often performed comparably to or better than more complex alternatives.
- Ejection fraction and serum creatinine consistently emerged as key predictors of mortality risk across multiple modeling approaches, aligning with the findings of Chicco and Jurman (2020).
- Cross-validation and model selection showed that a relatively small subset of clinical variables could capture much of the useful predictive signal.
- Tree pruning improved mortality classification performance, reinforcing the value of controlling model complexity and reducing overfitting.
- More advanced ensemble methods did not universally outperform simpler approaches, highlighting the importance of empirical model comparison rather than assuming greater complexity produces better predictions.

## Tools & Techniques

**Language:** R

**Statistical Learning:** Regression, Classification, Regularization, Cross-Validation, Bootstrap Resampling, GAMs, Tree-Based Models

**Machine Learning:** Random Forests, Boosting, BART

## Dataset & Attribution

This project uses the [Heart Failure Clinical Records](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records) dataset from the
UCI Machine Learning Repository. The dataset contains clinical records from
299 patients with heart failure and includes demographic, clinical, and
laboratory variables used to analyze and predict mortality outcomes. 

**Source:** UCI Machine Learning Repository  
**Dataset:** Heart Failure Clinical Records  
**DOI:** [10.24432/C5Z89R](https://doi.org/10.24432/C5Z89R)

**License:** CC BY 4.0

The dataset is associated with:

[Chicco, D., & Jurman, G. (2020). *Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone.* BMC Medical Informatics and Decision Making, 20, 16.](https://doi.org/10.1186/s12911-020-1023-5)
