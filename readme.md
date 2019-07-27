Predictions with linear regression models 

Introduction:  

To begin with all, in this project we are going to program a code to solve and predict the results of data set with the Lineal Regression simple and multivariable. 

The lineal regression , as its name says, It is a straight line that across of a set of points in the cartesian plane that can adapt in the best way between them and how this can help us to make predications or take decisions taking some intervals where the predictions or values can be and all of this is because the lineal regression is a Statistics technique  that use the relation between the variables, in this case the independent variable “X” and the dependent variable “Y” and in any cases more variables (multiple variable lineal regression) where we are going to characteristic the relation between the independents and dependents variables and how this can use to explorer that.  

Also, in the investigations problems the simple lineal regression is not enough to solve that, and for that reason is used the multiple variable lineal regression that have more than one independent variable and this is so important because this allow us to predict a better answer because this can solve and represent a structure more complex inside some range of independent variables. 

We are going to use the regression coefficients that allow us to make the best regression depending of our data and for this we are going to use the Least Squares compute the error that both are use the simple lineal regression or multiple variable lineal regression. 

And in this project, we are going to solve two problems, the first one is a relation of two variables where the variable “x” (independent) are the years, and the variable “y” (dependent) is the nitrogen oxide produced. And the last one is a relation of multivariable where the variable “y” (dependent) is the hours by job, and the variables “xn” (independents) are different ways of affect the variable “y”. 

Motivation:   

The motivation to do this problem is that with the lineal regression we are using datasets as a we said before and we can learn about the relation between the independent and dependent variable (including that this is a statistic technique) and how that relation can help us to make predictions in base of that.  

Other motivations that why we do this, is that the lineal regression can be used in different situations or fields as Social Investigation to compute the analyze of economic measure in the different aspects of the human behavior, also in marketplaces to find what are the best way to invest money, or predict the amount of sell of a product, and that’s not all, because also we can use in physics, mathematics, chemistry, biologic etc. to find the relation between the variables and to compute or calibrate measures.  

To conclude we can say that the best motivation that we get to do this, is that we can compute different things in a lot of fields, and that this in the end can help us to solve problems of the actuality, to avoid future problems or future mistakes, to help the nature or environment and even include to us with the predictions.  

Salto de página
 

Objective:  Our objectives are: 

Program a code to predict results using a model of simple lineal regression  

Program a code to predict results using a model of multivariable linear regression for five independents variables. 

Problem Description:  

Problem 1 

Assessing the deposition of nitrogen from the atmosphere is an important task of the National Atmospheric Deposition Program (NADP), which is associated with many institutions. This program studies atmospheric deposition and its effect on agricultural crops, surface waters of forests and other resources. Nitrogen oxides can have effects on atmospheric ozone and the amount of pure nitrogen found in the air we breathe. A researcher got the following data: 

Graph the data. 

Fit a linear regression model and calculate R2.  

What can you say about the trend of nitrogen oxide over time? 

Years = [1978,1979,1980,1981,1982,1983,1984,1985,1986.1987,1988,1989,1990,1991,1992,1993,1994,1995,1996,1997,1998,1999] 
 Oxygen Nitro = [0.73,2.55,2.90,3.83,2.53,2.77,3.93,2.03,4.39,3.04,2.03,4.39,3.04,3.41,5.07,3.95,3.14,3.44,3.63,4.50,3.95,5.24,3.30,4.36,3.33] 

Problem 2: 

The following data reflects information obtained in 17 hospitals in the US Navy located in various parts of the world. The regressors are variables of the workload, that is, concepts that result in the need for personnel in a hospital. A brief description of the variables is presented below: 

Y = monthly work hours, 

X1 = average daily load of patients, 

X2 = monthly x-ray exposures, 

X3 = bed days occupying per month, 

X4 = eligible population in the area / 1000, 

X5 = average duration of a patient's stay, in days. 

 

 
X1=[44.02,20.42,18.74,49.20,44.92,55.48,59.28,94.39,128.02,96.00,131.42,127.21,252.90,409.20,463.70,510.22]  
X2=[2463,2048,3940,6505,5723, 11520,5779,5969,8461,20106, 13313,10771,15543,36194,34703,39204,86533] 

X3= [472.92,1339.75,620.25,568.33,1497.60,1365.83,1687.00,1639.92,2872.33,3655.08,2912.00,3921.00,3865.67,7684.10,12446.33,14098.40,15524.00] 

X4= [18.0,9.5,12.8,36.7,35.7,24.0,43.3,46.7,78.7,180.5,60.9,103.7,126.8,157.7,169.4,331.4,371.6] 

X5 = [4.45,6.92,4.28,3.90,5.50,4.60,5.62,5.15,6.18,6.15,5.88,4.88,5.50,7.00,10.75,7.05,6.35] 

Y = [566.52,696.82,1033.15,1003.62,1611.37,1613.27,1854.17,2160.55,2305.58,3503.93,3571.59,3741.40,4026.52,10343.81,11732.17,15414.94,18854.45] 
Proposed Solution
