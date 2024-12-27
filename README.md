Polynomial Linear Regression

Overview
This project demonstrates the implementation of polynomial regression to model a quadratic relationship in synthetic data. It compares the performance of simple linear regression and polynomial regression models, highlighting the improved fit achieved by increasing the polynomial degree.

Features
Synthetic Data Generation:
Creates data based on the equation 

𝑦 = 0.5𝑥^2 + 1.5𝑥 + 2 + noise

Data Visualization:
Scatter plots to visualize the relationship between variables.

Model Training:
Implements simple linear regression and polynomial regression.

Model Evaluation:
Calculates 
𝑅^2 scores to compare model performance.

Prediction and Visualization:
Predicts new data and visualizes results with polynomial regression.


Steps
Generate Synthetic Data:
Creates input (𝑥) and output (y) variables with random noise.

Train-Test Split:
Splits the data into training and testing sets.

Simple Linear Regression:
Fits a linear model to the data and evaluates performance.

Polynomial Regression:
Applies polynomial transformations of degrees 2 and 3.

Fits models to transformed data and evaluates performance.

Visualization:

Displays scatter plots and model predictions for comparison.


Key Libraries

pandas: For data handling.
numpy: For numerical operations.
matplotlib: For visualizations.
scikit-learn: For regression models, transformations, and performance metrics.


Results
Linear Regression: Demonstrates poor performance due to the quadratic nature of the data.
Polynomial Regression:
Degree 2: Achieves a significantly better fit.
Degree 3: Further improves the model's predictive power.


Insights
Polynomial regression effectively captures nonlinear relationships.
Increasing the polynomial degree can improve model fit but requires careful evaluation to avoid overfitting.


License
This project is released under the MIT License.

Author
Francis Aroh