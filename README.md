# MechaCar_Statistical_Analysis

## Deliverable 1: Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/91839403/156890974-fdb40e8d-fc5e-48c7-bb17-de4f51c82a58.png)



![image](https://user-images.githubusercontent.com/91839403/156889706-cd7ba633-7b94-457e-aedb-ca5c57deb01c.png)

### Analysis of results

#### Significant Variables
The two most significant variables that impacted MPG in this study are Vehicle Length and Ground Clearance.  The t value for these are 9.563 and 6.551 respctivels. The t-value being large indicates a low probability that the results occured by chance.  The P value for these same variables are extremely small.  The null hypothesis (Ho) would say Vehicle Length and Ground Clearance do not impact MPG.  The P values <.05 say we can reject the null hypothesis, so Vehicle Length and Ground Clearance do effect MPG.  are significant because their p-values indicate that changes in the independent variable's value are related to changes in the dependent variable and we can reject the null hypothesis.  We should alos note in this case that MPG is the dependant varible and Vehicle Length and Ground Clearance are independant variables.  Rejecting the null hypotheses therefore means that Vehicle Length and Ground Clearance (independnt variables) cause a change in MPG (dependant variable).

#### Slope of regression line
The slope of this linear model is not considered to be zero because our correlation to correlation between the dependant and independant variables is significant.  We can write a prediction equation from the output of the analysis including only those variables shoes to be statistically significant.  The Prediction equation would be MPG = -01 + 6.267(Vehicle_Length) + 3.546(Ground_Clearance)  That line has a slope > 0.

#### Prediction accuracy
The linear model does an effective job of predicting mpg of the test cars.  The p-value of 5.35e-11 is extremely small.  This low p-value allows us to reject Ho, the Null Hypothesis that the independant variables have no effect on the dependant variable (MPG).  So this statistical analysis says that the linear model can predict MPG.  The R-Squared value of 71.5% says it can predict the result 75% of the time.  That indicates that the modle does a good job predicting MPG.


## Deliverable 2: Summary Statistics on Suspension Coils 

![image](https://user-images.githubusercontent.com/91839403/156892386-c32ec546-8c23-49c1-a769-55f07728085e.png)

![image](https://user-images.githubusercontent.com/91839403/156892369-57559c10-dfc9-4a4c-9446-b02064e99c99.png)

The design specifications for the suspension coils requires that the variance of the suspension coils must not exceed 100 pounds per square inch.  The analysis above shows that when combined the variance of all lots combined is 62.29.  This passes the specification of being less than 100.

Reviewing each lot individually a potential issue does show up.  Lot 1 and Lot two have low Variance of .98 and 7.47 respectively.  Lot 3 however has a variance of 170 exceeding the limit of 100.  This is significantly higher that both the limit and the other 2 lots.  Lot three thus should be rejected.

## Deliverable 3: T-Tests on Suspension Coils

### All Lots combined t-test

The t-Test performed on all coil lots resulted in a p-value of .06.  This is greater than the significance level of .05 and thus we fail to reject the null hypothesis. The null hypothesis (Ho) is that the mean of all coil lots is 1500 psi.  Based on these results, failing to reject the null hypothesis, the true mean across all lots is 1500 psi.

![image](https://user-images.githubusercontent.com/91839403/156893191-ed56101b-543f-42ee-b41b-faa66920cb90.png)

### Lot 1 t-test
The t-Test performed on coil lot 1 resulted in a p-value of .06.  This is greater than the significance level of .05 and thus we fail to reject the null hypothesis. The null hypothesis (Ho) is that the mean is 1500 psi.  Based on these results, failing to reject the null hypothesis, the true mean for lot 1 is 1500 psi.

![image](https://user-images.githubusercontent.com/91839403/156893057-955398f5-2760-45b7-aa98-fc5e28e2da1b.png)

### Lot 2 t-test

The t-Test performed on coil lot 2 resulted in a p-value of .607.  This is greater than the significance level of .05 and thus we fail to reject the null hypothesis. The null hypothesis (Ho) is that the mean is 1500 psi.  Based on these results, failing to reject the null hypothesis, the true mean for lot 2 is 1500 psi.

![image](https://user-images.githubusercontent.com/91839403/156893156-756a5e99-6ea4-40b4-ac3b-a0e119889a5b.png)

### Lot 3 t-test

The t-Test performed on coil lot 3 resulted in a p-value of .042.  This is less than the significance level of .05 and thus we reject the null hypothesis. The null hypothesis (Ho) is that the mean is 1500 psi.  Based on these results, rejecting the null hypothesis, the true mean for lot 2 is different from 1500 PSI and that difference is statistically significant.

![image](https://user-images.githubusercontent.com/91839403/156893144-e00f798b-c6da-4c77-a9b9-2098f204be9f.png)

## Deliverable 4: Study Design- MechaCar vs Competition

### Metric to be tested?

#### Metric: Sales price as a % of List Price.  
Purpose to determine if Fuel Efficiency, Safety Rating, Suspension, Vehicle Manufacturer, Vehicle Type (Car, Truck, SUC, Van) impact the ability to realize the list price of the car. 

#### What is the null hypothesis or alternative hypothesis?
Ho: The Null Hypothesis is that Actual Price paid is not impacted by these variables

#### What statistical test would you use to test the hypothesis? And why?

This could be done with linear regression on multiple variables.  This would enable us to determine what varibales most influence sales price as a percent of list price and the predictability of the model.

#### What data is needed to run the statistical test?

Car Manufacturer.
Vehicle Type.
City or highway fuel efficiency of each vehicle.
Safety rating of each vehicle.
Suspension rating of each vehicle.

This would be of interest if you were working to understand what cars you sell that realize the best results vs selling price and why.  This could be used by someone interested in getting into the auto sales business, the owner of a dealership and even car manufacturers to understnad how they perform vs. the competition and what drives that result.

