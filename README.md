 Week 4: Basic Machine Learning 
● Project Title: Implementing a Simple Linear Regression Model 
● Description: Use a dataset to create a linear regression model to predict a numerical outcome. Evaluate model performance and visualize the results. 

Dataset Reference: California Housing Prices Dataset 


Project Overview
•	Goal: Predict median_house_value using a single numerical feature.
•	Dataset: California Housing Prices
•	Approach: Simple Linear Regression
Steps:
•	Data Preprocessing
•	Exploratory Data Analysis (EDA)
•	Model Implementation
•	Performance Evaluation
•	Visualization


Key insights and findings 

1.	Mean Squared Error (MSE): This metric represents the average of the squared differences between the predicted and actual house values. In this case, the MSE appears large due to the high scale of house prices, which are typically in the hundreds of thousands.
2.	R-squared (R²) Score: R² = 0.4589 → Our model explains around 45.9% of the variance in house prices using just median income. This means the model captures a moderate relationship between income and house value.
3.	For a simple linear regression with only one feature, this is decent, not perfect, but it shows a meaningful trend.
4.	The simple linear regression model using median income as the sole predictor explains about 46% of the variability in housing prices. While it is not highly accurate, it confirms that income is a significant factor affecting house prices. However, other factors also contribute to price variability and are not captured in this simple model.

