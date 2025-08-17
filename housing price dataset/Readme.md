# Linear Regression Implementation

This repository contains the implementation of Task 3 for the AI & ML Internship, focusing on Linear Regression.

## Contents
1. `linear_regression.ipynb`: Jupyter notebook with complete implementation
2. This README file with explanations
3. Answers to interview questions

## Implementation Details

### Dataset
The implementation uses either:
1. A custom dataset uploaded to Google Drive (path needs to be specified)
2. The Boston Housing dataset as a fallback

### Steps Performed

1. **Data Loading and Exploration**
   - Mounted Google Drive to access dataset
   - Displayed basic dataset information and statistics

2. **Data Preprocessing**
   - Checked for missing values
   - Analyzed feature correlations

3. **Simple Linear Regression**
   - Selected one strongly correlated feature
   - Split data into training and test sets
   - Trained the model and made predictions
   - Evaluated using MAE, MSE, RMSE, and R²
   - Visualized the regression line

4. **Multiple Linear Regression**
   - Selected multiple relevant features
   - Trained a more complex model
   - Evaluated performance metrics
   - Interpreted coefficients

5. **Model Validation**
   - Analyzed residuals to check assumptions
   - Created Q-Q plot for normality check

6. **Interview Questions**
   - Provided detailed answers to all theoretical questions

## How to Use
1. Upload your dataset to Google Drive
2. Update the file path in the notebook
3. Run all cells sequentially

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

## Results
The implementation demonstrates:
- How to properly implement linear regression
- Model evaluation techniques
- Interpretation of results
- Validation of regression assumptions