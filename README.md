# Sales-Predicting-Regression-Model

## Introduction:
This report presents a regression analysis aimed at predicting sales based on marketing expenditures across TV, radio, and newspaper platforms. The objective is to understand the impact of each marketing channel on sales and to develop a predictive model for future sales forecasting.

Data Description:
The dataset consists of records containing information on sales and marketing expenses across TV, radio, and newspaper channels.

## Variables:

Sales: The target variable representing sales figures.
TV: Expenditure on TV advertising.
Radio: Expenditure on radio advertising.
Newspaper: Expenditure on newspaper advertising.

## Methodology:

Regression Analysis: A multiple linear regression approach was employed to model the relationship between sales and marketing expenditures across various channels.
Assumptions: The analysis assumes a linear relationship between marketing expenses and sales, independence of observations, homoscedasticity, and normality of residuals.

## Model Building:

Predictors: TV, radio, and newspaper expenditures were used as predictors for the regression model.
Training and Testing: The dataset was divided into training and testing sets to evaluate model performance.

## Interpretation of Coefficients:

&#10686;Intercept (const): The intercept term represents the baseline sales value when all predictor variables (TV, newspaper, radio) are set to zero. In this case, it suggests that even without any advertising expenditure, there would still be a base level of sales, estimated to be approximately 4.4192 units.

&#10686;TV coefficient: The coefficient for TV advertising expenditure is 0.0537. This indicates that for each unit increase in TV advertising spending, sales are expected to increase by approximately 0.0537 units, holding other variables constant.

&#10686;Newspaper coefficient: The coefficient for newspaper advertising expenditure is 0.0054. This suggests that for each unit increase in newspaper advertising spending, sales are expected to increase by approximately 0.0054 units, controlling for other factors.

&#10686;Radio coefficient: The coefficient for radio advertising expenditure is 0.1061. This implies that for each unit increase in radio advertising spending, sales are expected to increase by approximately 0.1061 units, assuming other variables remain constant.

## Model Performance:

&#10686;R-squared (R^2): The R-squared value of 0.911 indicates that approximately 91.1% of the variance in sales is explained by the independent variables (TV, newspaper, radio) included in the model. This suggests a strong fit of the model to the data.

&#10686;Mean Squared Error (MSE): The mean squared error of 3.3510 represents the average squared difference between the actual sales values and the predicted sales values by the model. Lower values of MSE indicate better model performance, indicating that the model's predictions are generally close to the actual sales figures.

## Overall Interpretation:

&#10686; The coefficients provide insights into the relative impact of each advertising channel on sales. Among the three channels, radio advertising appears to have the largest impact on sales, with a coefficient of 0.1061, followed by TV advertising with a coefficient of 0.0537, and newspaper advertising with the smallest coefficient of 0.0054.

&#10686;The high R-squared value suggests that the model effectively captures the variation in sales explained by the chosen predictors. However, it's important to consider other factors not included in the model that may also influence sales.

&#10686;The model's performance, as indicated by the low MSE, suggests that it is capable of making accurate predictions of sales based on advertising expenditures across TV, radio, and newspaper channels.

These findings can inform marketing strategies, helping businesses allocate their advertising budgets more effectively to maximize sales.
