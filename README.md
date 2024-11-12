# Assignment: Exploring Underfitting and Overfitting Using Polynomial Regression

## Objective:

In this homework, you will explore the concepts of *underfitting* and *overfitting* by implementing polynomial regression models of various degrees on a synthetic dataset. 
The goal is to study how the complexity of the model affects its performance and generalization ability. You'll evaluate models using cross-validation and visualize the results in Python using Plotly.


## Assignment Tasks

### 1. Data Generation (10 minutes)

- Generate a synthetic dataset by defining a true underlying function
$ y(x) = \cos(1.5 \pi x) $, and add some noise to it.
- Use *30 random data points* sampled from $ x \in [0, 1] $.
- Visualize the data points and the true function using *Plotly*.

### 2. Implement Polynomial Regression Models (20 minutes)

- Create polynomial regression models for degrees *1, 4, 10, and 15* using scikit-learn’s *Pipeline* and *PolynomialFeatures*.
- Fit the models to the dataset.
- For each degree, use *10-fold cross-validation* to compute the *Mean Squared Error (MSE)*.

### 3. Visualize the Results (15 minutes)

For each degree, visualize:
  - The predicted polynomial model.
  - The true function.
  - The data points.

Use *Plotly* to create an interactive plot comparing the models of different degrees.

### 4. Analysis (15 minutes)

Based on the results and visualizations, answer the following questions:

1. Which degree results in *underfitting*? Explain why.
2. Which degree leads to *overfitting*? Justify your answer.
3. Which model generalizes the best based on the MSE from cross-validation? Explain how the cross-validation scores support your conclusion.
4. How would increasing or decreasing the number of data points affect the model fitting? Hypothesize the effect on underfitting and overfitting.
5. Suggest a degree that best balances model complexity and performance.


## Guidelines & Deliverables

- *Python Notebook*: Submit a fully commented Jupyter notebook (.ipynb file) with the following sections:
- *Data Generation*: Code to generate and visualize the data.
- *Model Fitting*: Code for fitting polynomial regression models for degrees 1, 4, 10, and 15.
- *Cross-Validation*: Code to compute MSE for each model using 10-fold cross-validation.
- *Visualization*: Interactive Plotly plots comparing models.
- *Analysis*: Text cells with answers to the analysis questions.


## Bonus (Optional) (if you have time)
1. *Regularization*: Implement *Ridge Regression* on the same dataset and compare the performance with the polynomial models you tested.
2. *Explore More Degrees*: Test higher-degree polynomials (e.g., degree 20 or 25) and observe the behavior.


## Grading Criteria:
- *Correctness* (40%): Code correctness, proper fitting, cross-validation, and visualization.
- *Clarity* (30%): Code readability and proper comments/documentation.
- *Analysis* (30%): Insightful answers to the analysis questions, demonstrating understanding of underfitting, overfitting, and generalization.

This assignment should take approximately *one hour* to complete, including coding and analysis.
