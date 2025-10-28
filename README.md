1. **Project Overview**
Objective: Find the predicted hospitalization cost using the best models and determine the variable importance scores, and identify the redundant variables
Tools: Jupyter notebook, Tableau dashboard
Dataset: Kaggle - Health insurance dataset
Deliverables: ML prediction model, Tableau interactive dashboard

2. **Business Problem**
The company’s leadership team wants to understand:
  - identify factors contributing to hospitalization costs 
  - learn the interdependencies of different factors - BMI, Heart issues, HBA1C, smoker status, surgeries, cancer history.
  - This analysis helps predict the hospitalization costs.

3. **Approach**
Step 1: Data Exploration & Cleaning (Python)
  - Remove duplicates
  - Imputing missing data and null values
  - Encoding categorical columns for better model performance
  - Performing necessary datatype conversion of columns
  - EDA of raw data 

Step 2: Model building (ML)
  - Drop irrelevant column data
  - Train-test split
  - Create pipeline for model creation by applying scaling and regression models
  - Calculate best score with grid search, random forest and gradient boost regression models
  - Find out best features to be included for better performance
  - Calculate model accuracy scores for all the models
  - Predict with 3 regression models and calculate the errors in prediction
  - Calculate the average cost of hospitalization for all three models


Step 3: Tableau dashboard:
Link: https://public.tableau.com/views/Healthcarecapstonefinal/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

4. **Key Insights**

- Patients with more than one major surgeries and heart issues prefer tier 1 hospitals
- Smokers hospitalization costs are more than non-smokers.
- The chances of diabetes is higher for people whose age is more than 40.

5. **Final Deliverables**

Dashboard: View on Tableau Public - https://public.tableau.com/views/Healthcarecapstonefinal/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link



