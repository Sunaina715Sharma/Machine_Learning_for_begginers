# Machine_Learning_for_begginers
as a bigginer need to look for types of algorithms and models we have
There are many models and various algorithms like linear regression (for multiple and linear relations, Logistic Regression, Decission Tree etc. So lets Start with the very first and simplest algorithm that is Simple Linear Regression
so lets start with simple linear regression
SIMPLE LINEAR REGRESSION      
Regression models describe the relationship between variables by fitting a line to the observed data. Linear regression models use a straight line, while logistic and nonlinear regression models use a curved line. Regression allows you to estimate how a dependent variable changes as the independent variable(s) change.
Simple linear regression is used to estimate the relationship between two quantitative variables. You can use simple linear regression when you want to know


First! How strong the relationship is between two variables (e.g. the relationship between rainfall and soil erosion).
Second ! The value of the dependent variable at a certain value of the independent variable (e.g. the amount of soil erosion at a certain level of rainfall).

If you have more than one independent variable, use multiple linear regression instead( we will study this further).

Simple linear regression is a type of regression analysis where the number of independent variables is one and there is a linear relationship between the independent(x) and dependent(y) variable. The red line in the above graph is referred to as the best fit straight line. Based on the given data points, we try to plot a line that models the points the best. The line can be modelled based on the linear equation shown below.

y = a_0 + a_1 * x      ## Linear Equation


The motive of the linear regression algorithm is to find the best values for a_0 and a_1. Before moving on to the algorithm, let’s have a look at two important concepts you must know to better understand linear regression.

#Cost Function
The cost function helps us to figure out the best possible values for a_0 and a_1 which would provide the best fit line for the data points. Since we want the best values for a_0 and a_1, we convert this search problem into a minimization problem where we would like to minimize the error between the predicted value and the actual value.


We choose the above function to minimize. The difference between the predicted values and ground truth measures the error difference. We square the error difference and sum over all data points and divide that value by the total number of data points. This provides the average squared error over all the data points. Therefore, this cost function is also known as the Mean Squared Error(MSE) function. Now, using this MSE function we are going to change the values of a_0 and a_1 such that the MSE value settles at the minima.


#CODING
I HAVE ATTECHED A FILE NAMED "SIMPLE_LINAR_REGRESSION




