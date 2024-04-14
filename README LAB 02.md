**Abstract:**

This lab assignment focuses on implementing multivariable linear regression using Gradient Descent and applying it to real data. Multivariable linear regression extends the concept of univariate or single variable linear regression by incorporating multiple features to fit the line of best fit with training data. Through this assignment, we will explore the process of training a prediction model using Gradient Descent and making predictions based on the trained model. 

**Introduction:**

The purpose of this report is to use real data to develop and analyze multivariable linear regression using Gradient Descent. After the prediction model has been trained, the goal is to comprehend how this method operates and generate predictions. By constructing a line of best fit with training data that includes multiple features, multivariable linear regression expands on the idea of single-variable linear regression. 

**Methods:**

To develop multivariable linear regression, we used the linear algebra approach and the for-loop approach. Using fuel consumption data, the for-loop approach used Gradient Descent in Python to get the ideal parameter values (θ0, θ1, θ2, θ3, θ 4). First, we set the learning rate (α) to 0.001 and started the parameters with modest values. Gradient Descent was another technique used by the linear algebra approach to get the ideal parameter values. To facilitate vectorized solution, I adjusted the dataset by adding a new column of ones. Then, we estimated the optimal parameter values using the linear algebra approach. 

**Results:**

We have effectively ascertained the ideal parameter values for the for loop method and monitored the associated expenses J (θ0, θ1, θ2, θ3, θ4) for every iteration. To show how the cost decreases with more iterations, we created a plot that shows the cost versus the number of iterations. Additionally, we created a "line of best fit" by utilizing the ideal parameter values that we had chosen for a column vector. In addition, we estimated the expected values of CO2 emissions and compared them with the predicted values after validating our model using test data. 

**Discussion or Analysis:**

The outcomes of both methods show how useful Gradient Descent is for multivariable linear regression. We developed precise CO2 emission forecast models based on model year, engine size, cylinder count, and combined mpg by fine-tuning the parameter values. The accuracy of our models in predicting CO2 emissions was demonstrated by the comparison of anticipated and expected values. 

**Conclusions:**

In summary, our use of Gradient Descent in multivariable linear regression analysis demonstrated its effectiveness in estimating CO2 emissions based on a variety of parameters. We were able to obtain important insights into the optimization process and the significance of feature selection in the development of precise prediction models by putting both the for loop and linear algebra approaches into practice. This report highlights the value of multivariable linear regression as an effective method for evaluating actual data and developing well-informed forecasts.
