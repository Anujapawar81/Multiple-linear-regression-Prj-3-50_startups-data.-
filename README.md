# Multiple-linear-regression-Prj-3-50_startups-data.-

**Objective:**

The primary objective of this project is to predict the profit of an organization based on the money they spend on R&D, Administration, Marketing, and the city in which they operate.

**Solution Overview :**

**Methodology:**

**Data Preparation:**

•	Import necessary packages in Jupyter Notebook.
•	Extract and load the dataset and copy the data.

**Data Preprocessing:**

•	Identify and handle incorrect 0 values in the dataset.
•	Impute the incorrect data using the median of the respective columns.

**Exploratory Data Analysis (EDA**):

**Visual Representation:**
The first step in EDA was to visualize the relationships between variables. the correlation between the variables can be visualized with the help of scatterplot , barplot,histplot, lineplot ,piechart & regplot.
•	Analyze the data to gain insights.

**Categorical Variable Analysis:**

•	Analyze the impact of the "State" variable on profit using one-way ANOVA.
•	The analysis suggests that "State" is not a significant factor in profit variation.

**Correlation Analysis:**

A heatmap used  to identify correlations between the variables 	

**Outlssier Detection:**

Checking the outliers helping with boxplot.

**Feature Selection:**

Choose R&D Spend and Marketing Spend as independent variables for predicting profit.

**Model Building:**

•	Create a multiple linear regression model using Scikit-Learn.
•	Split the data into training and testing sets with an 80:20 ratio.
•	Train the model on the training data and test it on the testing data.

**Model Evaluation:**

•	Assess the model's performance using the R-squared (r2_score).
•	Assumptions

Achieve an r2_score of approximately 94.92, indicating a strong model fit.
The Adjusted R2 score of  The 90.82 Root Mean Squared Error (RMSE) value was calculated to be 8355.89 The mean squared error(MSE) value was calculated to be 69821055. The mean absolute error(MAE) value was calculated to be 6333.4245
