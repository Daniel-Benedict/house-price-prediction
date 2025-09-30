# house-price-prediction

This repository focuses on predicting house prices using two machine learning models:
Linear Regression
Gradient Boosting Regressor (GBR)
The primary file is:
housesales.ipynb: A Jupyter Notebook containing the code for data analysis, model training, and evaluation.
Additionally, the dataset used is:
kc_house_data.csv: A CSV file containing the housing data.

This is the given sample Data set 
<img width="1185" height="616" alt="Screenshot 2025-09-30 192555" src="https://github.com/user-attachments/assets/34ddcee1-2af3-480e-a222-09e1a39ebd33" />

While the repository doesn't explicitly mention staged loss plots, it's common to visualize model performance through various plots. Here are some typical graphs you might encounter or can generate:
1. Feature Importance Plot: Displays the importance of each feature in predicting house prices.
X-axis: Features
Y-axis: Importance score
Purpose: Helps identify which features most influence the model's predictions.
2. Residuals Plot: Shows the difference between actual and predicted values.
X-axis: Predicted values
Y-axis: Residuals (errors)
Purpose: Assesses the model's accuracy and identifies any patterns in errors.
3. Learning Curve: Plots model performance over training iterations.
X-axis: Number of estimators (trees)
Y-axis: Mean Squared Error (MSE)
Purpose: Evaluates how the model's error decreases as more trees are added.
<img width="435" height="408" alt="Screenshot 2025-09-30 192710" src="https://github.com/user-attachments/assets/f71430b9-2616-4bd8-aa36-356ddb9aa791" />
Hence by adding more trees we train the model and the errors will reduce 

Thank you
