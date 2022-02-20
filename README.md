 ![cars.png](https://github.com/charleside2001/MechaCar_Statistical_Analysis/blob/main/images/cars.png) 
# Overview of MechaCar Statistical Analysis
This objective of this project is to assist AutosRUs’ upper management in reviewing production data to provide insights that may help the manufacturing team.
The following analysis were performed
 * Multiple linear regression analysis to identify which variables in the dataset    predict the mpg of MechaCar prototypes
 * Create summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
 * Run t-tests to determine if the manufacturing lots are statistically different from the mean population
 * Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings

## Linear Regression to Predict MPG
  *1.*  The variables/coefficients that provide a non-random amount of variance to the mpg values in the dataset are Ground_clearance, vehicle_length and Intercept 


  *2.*  This analysis shows that the slope of the linear model is not zero. This is because the  p-value 5.35e-11 is less than assumed significance level of 0.05%.

 

  *3.* The coefficient of determination or R-squared value of this regression model is 71% accuracy.This value is closer to 1 than 0. Conclusively, this linear model prediction mpg of MechaCar prototypes is  effective.
  
  #### Linear Regression
  ![linear_reg.png](https://github.com/charleside2001/MechaCar_Statistical_Analysis/blob/main/images/linear_reg.png) 

  
## Summary Statistics on Suspension Coils,
 * The summary statistics for this regression model on shows that the current manufacturing data for  Lot 1 and Lot 2 met the design specification. these two lots have the same  mean and median summary statistics with nominal variances and standard deviations. Lot 3 on the other hand has the highest variance and standard deviation.
 
 #### Total Summary
 ![total_summary.png](https://github.com/charleside2001/MechaCar_Statistical_Analysis/blob/main/images/total_summary.png) 
 
 
 #### Lot Summary
 ![lot_summary.png](https://github.com/charleside2001/MechaCar_Statistical_Analysis/blob/main/images/lot_summary.png) 


## T-Tests on Suspension Coils

Comparing the three t-test samples with the assumed significance level of 0.05 percent, lot1 (p-value = 1), lot2 (p-value = 0.6072) and lot3 (p-value = 0.04168). The inference of that there is sufficient evidence to show that lot1 and lot2 hypothesis are acceptable while lot3 is not

#### T-test
![t_test.png](https://github.com/charleside2001/MechaCar_Statistical_Analysis/blob/main/images/t_test.png) 

## Study Design: MechaCar vs Competition
 *1.* MechaCar has an advantage of higher horsepower and mpg (highway fuel efficiency) over other brands of cars. These are factors for consumers to consider in their decision making.
 *2.* Perform t-test using dataset for other brands of cars and compare with results from MechaCar, perform null and alternative hypothesis on dataset to identify differences in analysis and compare results with the population of other brand of cars.
