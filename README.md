# Aimes Iowa House Prices
### Advanced Regression Techniques - Predict sales prices and practice feature engineering, RFs, and gradient boosting

- The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 
- The Dataset includes information regarding 2,580 homes and 82 variables. The variables consist of information regarding the home like number of bathrooms, roof style, and square footage.

## Goal of This Project 
- Clean the dataset and build and select a machine learning model that will best predict the sales price of the home.

## Models Used
1. Decision Tree
2. Random Forest
3. SVR
4. Lasso
5. Ridge
6. Multiple Linear Regession
7. Elastic Net
8. XGBoost

## Findings
- Improve the quality and condition of everything inside and outside the house, including detached garages. 
  - Aim for quality level 9 / excellent
- Homes with air conditioning, high total square footage, and high number of bathrooms tend to sell for a higher price. 
- The model that produced the best R-Squared of the test set was Ridge since 93.4% of the data fit the model.  However, it was pretty close to Lasso and Elastic Net.
- We can look at coefficients to make logical conclusions about which features are more important than others
  - By looking at the coefficients, I found the top 10 features to be from Overall quality, Neighborhood, Sale Condition, Overall Condition, Condition1 (Proximity to parks), and MsSubclass (describes the type of home that was sold).

## Folder
- Files: 
  - Includes House Prices as well as data description text file
