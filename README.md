# Predictive-Analytics-sample-questions
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Random Data 2

DESCRIPTION

Perform the steps as mentioned below to create a random data set and perform linear regression on the data:

 

1. Set seed to 1

2. Create 500 observations based on Standard Normal Distribution (Mean = 0 & Standard Deviation = 1.0) and store them into variable X

3. Create 500 observations based on Normal Distribution with mean as 0.5 and variance as 0.75 and store them into variable err

4. Using X and err, generate y as y = -1+0.5*X+err

5. Fit a polynomial regression model as follows:

First, fit & transform X using fit_transform and polynomial features of degree 2
Use this transformed X and y for fitting a linear regression model
Print the values of its coefficients and intercept in a file named 'output/output.csv'
6. Predict the values for y using the above model

Use the above model to predict the values of y based on the transformed X
Calculate the Mean Square Error in the predicted y and actual y
Print its value to the same file output.csv below the existing rows created in Step 5

Input Format:

All the required data will be generated in the solution. No need to read any input file
Output Format:

You have to perform the operations as required by the above questions and write (written above as print) your output to a file named output.csv, which should be present at the location output/output.csv
output.csv should contain the following values on 3 separate rows:
Coefficients  of fitting the model rounded to 3 decimal places and in the form such as [1.234 0.435 -1.572]
Intercept of fitting the model rounded to 3 decimal places such as 1.523
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
