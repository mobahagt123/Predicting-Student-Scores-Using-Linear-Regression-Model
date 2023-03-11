# Predicting-Student-Scores-Using-Linear-Regression-Model


## This is A project about Data Science aim to build a model that predicting student scores from their hours of studying

### Introduction

We Have a student score data which have 2 variables, hours of studying and scores achieved by each student.
The Data set have 25 rows and 2 variables.

### Objectives

Our Task is to build the best predictive model that predict students scores from their hours of studying.

### proposed problem Solution

I will use Machine Learning regression analysis to model our data and create the prediction model, using different regression algorithms and use Mean square error to evaluate models performance and choose best performing models, after that i will check best 3 models for validation (check variance and bias), finally i will tune the best performing model.

### Statistical Modeling

**Methodology**

* **Building A simple linear regression model using Hours of Study as Explanatory Var and Scores as Response Var.**
* **I will use Statsmodel module to build our model to calculate the slope and intercept.**
* **Then Evaluate Our model By plotting the fitted(predicted scores) against residuals and plotting the residuals probability.**

### Model Results

**The Equation of our linear regression is : $$\hat{Y} = 2.48 + 9.77 X$$**

**This Means For every one hour increase in study time the scores increases by 9.77 point**

**Our R_squared is 0.95 which means our relationship is strong and hours variable can explain scores very well**

### Model Evaluation

* **1-Plotting Residuals against Predicted Values**
* **2-Probability plot of residual Values**

### Conclusion

### Conclusion

We built A model that predicts Student scores with 95% variability, which means that 95% of our data can be explained by our model, Also our model has a high performance with little or no bias or variance.

