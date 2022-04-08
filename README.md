# MechaCar_Statistical_Analysis
## Overview
> In this project we`ve been given a dataset which include the mpg result for 50 MechaCar prototypes with multiple metrics. Multiple linear regression results analyzed and designed a linear model for predict the 'mpg'. R script, R Markdown file and its output as html file were provided with the Resources folder which include the screenshots of analysis.
## Linear Regression to Predict MPG
> Following image shows the results of first analyze and try to answer following questions.
> ![Picture1](/Resources/ss1.png)
> * Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
> Variables can be listed as follows: Intercept, AWD, Ground Clearance, Spoiler angle, vehicle length and vehicle weight. 
> * Is the slope of the linear model considered to be zero? Why or why not?
> Even though we have small amount of p-value, we can not consider the slope is equal to 0. Differen variables gave us the different results and furthermore we can only reject the null hypothesis since p-value is smaller than the significance level which is 0.05 %. 
>  * Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? 
> When we look up to the r-squared value %71 of it can be effectively used. Even it is a huge number, we are still far from a ideal prediction of MPG of MechaCar prototypes. However most likely we can predict correctly.
## Summary Statistics on Suspension Coils
> In this part we are trying to find an answer to folling question and added image shows our resutls related to the purpose. /n
>The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
> ![picture2](/Resources/ss2.png)  ![picture3](/Resources/ss3.png)
>Current manufacturing data satisfy the requirement of not exceeding 100Psi , however when we look up individually lot 3 does not meet design specifications.
## T-Tests on Suspension Coils
>Test on the all manufacturing lots, p-value is greater than the significance level. According to the results we do not have enough evidence to reject null hypothesis. Mean of all lots also close enough the population mean. /n
> Following image shows that individually and all lots test.
![Picture4](/Resources/ss4.png)
> Lot 1 and Lot 2 test results tell us their p-values are not low as 0.05% to reject the hypothesis. However for the lot 3 we can reject it since its p-value lower than the significance level. Lot 1 and lot 2 mean values are satisfy the population mean, however lot 3 is lower than the same level but we can say not so statistically different.
## Study Design: MechaCar vs Competition
> Following metrics could be interest of customers based on cost.
* Horse Power
* Safety
* Design
* Uniqueness details. 
> Our null hypothesis is: Is the metrics satisfy the cost?
> Alternative hypothesis: Is it not related to metrics to predict the cost justification? /n
> To determine the answers we can perform on t-tests both all data and individual variables. Linear regression statistical summary also helps us to look up the parameters. /n
> A sample data from populations regarding to the designed car and its competitors would be needed for the tests.
