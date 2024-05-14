# EXP-10           Implementation of Multivariate Linear Regression

NAME:RAMYA.P

REGISTER NUMBER: 212223240137

DEPARTMENT: AIML

## Aim
To write a python program to implement multivariate linear regression and predict the output.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

	
## Algorithm:
### Step1:
Start the program.
### Step2:
Write a program to perform multivariate regression in anaconda navigator.
### Step3:
Run the program.
### Step4:
Print the output.
### Step5:
End the program.

## Program:
```
#Program to find Univariate Linear Regression
#Developed by: RAMYA.P
#Register number: 212223240137

import pandas as pd
from sklearn import linear_model
data=pd.read_csv("car.csv")
x=data[['Weight','Volume']]
y=data[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predictCO2=regr.predict([[3300,1300]])
print('predicted CO2 for the corresponding weight and volume',predictCO2)
```
## Output:
![image](https://github.com/23014107/Multivariate-Linear-Regression/assets/151625620/eeb7ec5e-6bdb-4577-93e7-ce2f4da312e9)

## Result:
Thus the multivariate linear regression is implemented and predicted the output using python program.
