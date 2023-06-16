# Salary-Prediction-Uisng-Excel

![](Salary_Prediction_Image.jpg)


# Introduction

This data was gotten from Kaggle and the analysis was carried out using Microsoft Excel to predict employee salary using different variables. 

# Problem Statement 

The aim of this analysis is to build a model & answer the question of a sales company if years of experience has an effect on the salary of employees.

# Skills & Concept used:

- Statistics
- Equation of a straight line
- Linear Regression
- Coefficient of Correlation (Measures the degree of relationship between 2 variables)
- Coefficient of Determination (explains how good your model is ie it explains how the difference in one variable can be explained by the difference in the second/other variable )
- Data Science
- Data Analysis
- Data Transformation
- Data Visualization & Design (Using appropriate visuals to send appropriate message to stakeholders)

# Data Source:

A simple Csv file was downloaded from kaggle.com.

# Data Transformation/Cleaning:

I carried out transformation by removing blanks from the data so as not to affect my final linear regression model. The image below shows the that after transformation

![](Initial_data.jpg)

# Linear Regression

A new sheet was created that contains only the predictor variable and target variable data as shown below.

![](Linear_regression_data.jpg)

r was calculated using excel function to ascertain if there is a relation between the 2 variables using the formula shown below.

![](Correlation_formula.jpg)

The result for r is shown in the image below: 

![](correlation_output.jpg)

r = 0.93033 simply means there is a strong positive relationship of about 93% between the target and predictor variable.

# Data Visualization

A scatter plot was plotted between the 2 variables to ascertain the relationship. The plot is shown in the image below.

![](Scatter_Plot.jpg)

Next a line of best fit was added to the scatter plot to ascertain the model and value for r square(r^2) as shown below.

![](Scatter_Plot_Model.jpg)

r^2 = 0.8655 means the model 86.55% accurate . It simply tells us how strong our model is.

From the scatter plot, the linear regression model which is similar to the equation of a straight line y = mx + c is shown in the image below.

![](Linear_Regression_Model.jpg)

Now that we have the model as shown above, the model was tested by defining the model in different cells in excel as shown below.

![](Model_formula.jpg)

