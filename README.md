# Task 20: Documentation of Preprocessing Steps

## Summary of Preprocessing

1. Loaded the Titanic dataset using Pandas.
2. Displayed the dataset's structure and summary statistics.
3. Identified missing values in the dataset.
4. Filled missing values in the **Age** column using the mean.
5. Filled missing values in the **Embarked** column using the mode.
6. Removed the **Cabin** column due to a large number of missing values.
7. Checked for and removed duplicate records.
8. Detected outliers in the **Fare** column using the IQR method.
9. Removed the detected outliers.
10. Converted the **Sex** column into numerical values using Label Encoding.
11. Converted the **Embarked** column using One-Hot Encoding.
12. Applied Min-Max Scaling to the **Age** feature.
13. Applied Standardization to the **Fare** feature.
14. Generated a correlation matrix and heatmap.
15. Created new features (**FamilySize** and **IsAlone**) through feature engineering.
16. Converted data types where necessary.
17. Cleaned inconsistent text data.
18. Split the dataset into training and testing sets.
19. Balanced the training dataset using Random Oversampling.
20. Saved the cleaned and preprocessed dataset as **cleaned_titanic.csv**.

### Conclusion

The dataset has been successfully preprocessed and is now suitable for machine learning tasks. Missing values, duplicates, outliers, and categorical variables were handled appropriately, numerical features were scaled, new features were created, and the dataset was prepared for model training.
