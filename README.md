# Titanic Data Preprocessing

## Overview
This project focuses on preparing the Titanic dataset for machine learning tasks. The goal is to clean, transform, and engineer features that improve model performance in predicting passenger survival.

## Steps Performed
1. **Data Cleaning**  
   - Handled missing values.  
   - Dropped irrelevant column: *Cabin*.  

2. **Outlier Treatment**  
   - Addressed extreme values in numerical features.  

3. **Feature Encoding**  
   - Converted categorical features (*Sex*, *Embarked*) into numerical format.  

4. **Feature Scaling**  
   - Standardized *Age* and *Fare* to reduce bias from differing ranges.  

5. **Feature Engineering**  
   - Created a new feature: *FamilySize* = SibSp + Parch + 1.  

## Outcome
The cleaned dataset is now ready for model training and survival prediction. This preprocessing ensures better accuracy and generalization in machine learning models.  

---
