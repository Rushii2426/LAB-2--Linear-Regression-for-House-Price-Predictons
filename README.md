# LAB-2--Linear-Regression-for-House-Price-Predictons

# Aim
To develop a Linear Regression model for predicting house prices using a suitable
dataset.

# 1. Theory
Linear Regression is a supervised machine learning algorithm used to predict a
continuous numerical target variable from one or more input features. In simple linear
regression, the relationship between the input and output is represented by a straight line:
y = b₀ + b₁x
For multiple linear regression, several input features are used:
y = b₀ + b₁x₁ + b₂x₂ + ... + bx

In this experiment, the notebook uses a house-price dataset and develops a multiple linear
regression model using features such as average area income, average area house age,
average number of rooms, average number of bedrooms, and area population. The model
is trained using the training data and evaluated on test data using metrics such as Mean
Squared Error (MSE), R-squared (R²), Mean Absolute Error (MAE), and Root Mean
Squared Error (RMSE).
The notebook also includes regularized linear models such as Ridge and Lasso and uses
feature scaling for the regularized-model workflow. The final model can be used to
predict the price of a new house from its feature values.


# 2. Materials Used
● Python / Google Colab
● Jupyter Notebook (.ipynb)
● Pandas
● NumPy
● Matplotlib
● Seaborn
● Scikit-learn
● House-price dataset used in the notebook
● GitHub for code submission

3. Procedure

1. Import the required Python libraries..

2. Load the house-price dataset

3. Inspect the dataset and its features.

4. Select suitable input features and the target price variable.

5. Split the data into training and testing sets.

6. Train a Linear Regression model using the training data.

7. Generate predictions for the test data.

8. Evaluate the model using MSE, R2, MAE and RMSE.

9. Visualize actual prices against predicted prices.

10. Use the trained model to predict the price of a new house from user-provided feature values.

11. Compare/inspect regularized models such as Ridge and Lasso where included in the notebook.

12. Record the important outputs and observations.
