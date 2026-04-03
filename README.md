# Advertising Sales Prediction

## Objective
Predict product sales based on TV, Radio, and Newspaper advertising budgets
using Linear Regression.

## Dataset
- File: Advertising.csv
- Total Records: 200
- Independent Variables: TV, Radio, Newspaper (advertising spend in thousands)
- Dependent Variable: Sales (in thousands of units)

## Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Workflow
- Step 1: Load the dataset
- Step 2: Remove unwanted columns
- Step 3: Check for missing values
- Step 4: Display statistical summary
- Step 5: Correlation analysis between columns
- Step 6: Split data into independent and dependent variables
- Step 7: Split dataset into training and testing sets (80/20)
- Step 8: Build and train Linear Regression model
- Step 9: Test the model on unseen data
- Step 10: Evaluate model performance
- Step 11: Display model coefficients and intercept
- Step 12: Compare actual vs predicted sales values
- Step 13: Visualize actual vs predicted sales using scatter plot

## Model Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## How to Run
1. Clone this repository
2. Install required libraries:
   pip install pandas numpy matplotlib scikit-learn
3. Make sure Advertising.csv is in the same folder as the script
4. Run the script:
   python advertising_analysis.py

## Result
The Linear Regression model successfully predicts sales values based on
advertising budgets. Model performance is evaluated using MSE, RMSE, and
R² Score. A scatter plot visualizes the relationship between actual and
predicted sales values.
