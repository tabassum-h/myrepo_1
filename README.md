# Task 1: Data Cleaning & Preprocessing

## Task Description
This task focuses on fundamental data cleaning and preprocessing techniques essential for machine learning. The objective was to take raw data (Titanic dataset) and prepare it for machine learning models by handling missing values, encoding categorical variables, scaling numerical features, and dealing with outliers.

## Solution Approach
The implementation follows a structured data preprocessing pipeline:

1. **Data Loading & Exploration**: Initial examination of the dataset structure and statistics
2. **Missing Value Treatment**: 
   - Median imputation for numerical features (Age)
   - Mode imputation for categorical features (Embarked)
   - Column removal for features with excessive missing values (Cabin)
3. **Categorical Encoding**:
   - One-hot encoding for nominal variables (Sex, Embarked)
   - Label encoding for demonstration purposes (Name)
4. **Feature Scaling**: Standardization of numerical features
5. **Outlier Handling**: Detection using boxplots and removal using IQR method
6. **Final Dataset Preparation**: Separation of features and target variable

## Key Learnings
- Practical experience with real-world data cleaning challenges
- Understanding different techniques for handling missing data
- Comparison of encoding methods for categorical variables
- Importance of feature scaling in machine learning
- Techniques for identifying and treating outliers

## Files Included
- `Data_Cleaning_Preprocessing.ipynb`: Jupyter notebook with complete implementation
- `README.md`: This documentation file

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Run cells sequentially (Shift+Enter)
3. The notebook includes all necessary imports and downloads the dataset automatically

## Interview Questions Answered
The notebook also includes answers to 8 common interview questions about data preprocessing concepts covered in this task.
