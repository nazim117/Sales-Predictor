
# Linear Regression Task: Predict Sales Based on TV Advertising Spend

## Overview
This task involves using a one-variable linear regression model to predict sales based on the amount spent on TV advertising. 
The goal is to explore the relationship between advertising spend and sales, fit a linear regression model, and evaluate its performance.

---

## Dataset
The dataset contains two columns:
- `TV`: The amount spent on TV advertising (in dollars).
- `Sales`: The corresponding sales revenue (in dollars).

The data is synthetically generated, with a clear linear trend and some random noise to simulate real-world variability.

---

## Steps to Complete the Task
1. **Explore the Data**:
   - Load the dataset and inspect its structure.
   - Use descriptive statistics and visualizations (e.g., scatterplots) to understand the relationship between `TV` and `Sales`.

2. **Fit a Linear Regression Model**:
   - Use the `TV` column as the independent variable (X).
   - Use the `Sales` column as the dependent variable (y).
   - Fit the model using Python libraries like `sklearn`.

3. **Evaluate the Model**:
   - Assess model performance using metrics like Mean Squared Error (MSE) and R² Score.
   - Visualize the regression line overlaid on the scatterplot of the data.

4. **Interpret the Results**:
   - Understand the slope (rate of change in sales per dollar of TV spend) and intercept (expected sales when no TV spend occurs).
   - Discuss the real-world implications of the model.

5. **Validate Assumptions**:
   - Check residual plots to validate assumptions of linear regression (e.g., linearity, constant variance).

---

## Tools and Libraries
- **Python**:
  - `pandas` for data manipulation.
  - `matplotlib` for data visualization.
  - `sklearn` for regression modeling and evaluation.

---

## Tips
- Visualize your data before modeling to confirm a linear relationship.
- Interpret both the model's performance metrics and the coefficients in the context of the problem.

---
