# Lab 2 - Linear Regression

## Aim

To develop a Linear Regression model for predicting house prices using a suitable dataset.

## Objective

To analyze the USA Housing dataset and develop regression models for predicting house prices.

## Dataset

The practical uses the **USA Housing Dataset (****`USA_Housing.csv`****)**.

The dataset contains information such as:

- Average Area Income
- Average Area House Age
- Average Area Number of Rooms
- Average Area Number of Bedrooms
- Area Population
- Price

The **Price** column is used as the target variable.

## Models Used

- Simple Linear Regression
- Multiple Linear Regression
- Ridge Regression
- Lasso Regression

## Data Processing

- Dataset was loaded using Pandas.
- Dataset structure and statistical information were analyzed.
- Missing values were checked.
- Duplicate records were checked.
- The `Address` column was removed.
- Correlation between numerical features was analyzed.

## Model Evaluation

The regression models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Regularization

Ridge and Lasso Regression were applied to study regularization techniques.

GridSearchCV with 5-fold cross-validation was used to find suitable hyperparameter values.

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Files

- `Lab2_Linear_Regression.ipynb` – Google Colab notebook containing the practical code.
- `Dataset/USA_Housing.csv` – Dataset used for house price prediction.

## Conclusion

The USA Housing dataset was used to develop and evaluate different regression models for house price prediction. Simple Linear Regression, Multiple Linear Regression, Ridge Regression and Lasso Regression were implemented and evaluated using suitable performance metrics... rewrite properly gor github
