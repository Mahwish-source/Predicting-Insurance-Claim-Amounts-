#Task 4
# Predicting-Insurance-Claim-Amounts-
"Machine learning project to predict insurance claim amounts using patient health and demographic data."

# Task Objective
# The objective of this task is to build a regression model that predicts
# medical insurance claim amounts (charges) from personal and lifestyle data.
# We also aim to understand how features like BMI, age, and smoking status
# influence these charges.

#  Approach
# 1. Load the Medical Cost Personal Dataset using pandas.
# 2. Perform basic exploration and visualize relationships between features
#    (especially BMI, age, and smoking status) and insurance charges.
# 3. Encode categorical variables where needed (e.g., sex, smoker, region).
# 4. Split the data into training and testing sets.
# 5. Train a Linear Regression model to predict 'charges'.
# 6. Evaluate the model using error metrics such as Mean Absolute Error (MAE)
#    and Root Mean Squared Error (RMSE).
# 7. Interpret the results and identify which factors have the greatest impact
#    on insurance claim amounts.

# Results and Insights
# The regression model provides estimated insurance charges for individuals
# based on their profile. Visualizations reveal that higher BMI and being a
# smoker are typically associated with larger medical costs, while age also
# shows a positive relationship with charges. MAE and RMSE values indicate
# how close the model's predictions are to actual charges, helping us judge
# its usefulness for real-world cost estimation.

