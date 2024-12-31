# Source Code
For full source code, click [here](https://github.com/FilipLe/World-Happiness/blob/main/src/Happiness_Project.ipynb)

## Outcome
Random Forest was the best. The Random Forest algorithm's strength lies in its ability to combine predictions from multiple decision trees, each trained on different subsets of the data and features. This ensemble approach inherently reduces overfitting by aggregating diverse predictions to achieve a more generalized and reliable output.

## Data Preprocessing + Feature Engineering
To read more about the data preprocessing + feature engineering, check out [../data](https://github.com/FilipLe/World-Happiness/tree/main/data)

## Parameter Tuning + Model Evaluation
#### Nested Cross Validation
1. Defining Hyperparameter Grids:
<br>For each model above, define a range of values for each hyperparameter that will be considered during the search.

2. Cross-Validation:
<ul>
  <li>
    Divide training data into multiple folds 
  </li>
  <li>
    Inner Loop: Tuning Parameters
  </li>
  <li>
    Outer Loop: Training with Optimal Parameters
  </li>
</ul>

## Predictive Methods
### Traditional Decision Tree
#### Method
Splits data into branches based on feature thresholds to make predictions, allowing to capture non-linear patterns and feature interactions
#### Problem
Tends to overfit the training data and can create overly complex trees that don't generalize well to new data.
### Logistic Regression
#### Method
Predicts binary outcomes by fitting a logistic curve to estimate probabilities, making it ideal for classification problems
#### Problem
Assumes a linear relationship between the features and the outcome, which might oversimplify complex interactions in the data
### K-Nearest Neighbor
#### Problem
Makes predictions by looking at the K closest training examples and taking a majority vote/average of their values
#### Cons
Distance measurements become less meaningful in high-dimensional spaces.
### Lasso Regression
#### Method
Performs feature selection by adding penalty term that shrinks coefficients to zero, effectively eliminating less important features
#### Problem
Arbitrarily chooses between features and may eliminate important variables that are moderately correlated with stronger predictors
### Random Forest
#### Method
Combines multiple decision trees and aggregate their predictions to reduce overfitting and improve accuracy
#### Problem
Computationally expensive
