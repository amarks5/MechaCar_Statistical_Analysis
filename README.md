# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/linear_regression_predict_mpg_image.png)
* Vehicle Length and Ground Clearance are the most significant variables in our dataset (denoted by arrows) indicating a non-random effect on the MPG. Our p-values for Vehicle Length = 2.60e-12 and Ground Clearance = 5.21e-08. In addition, the intercept was statistically significant, suggesting there are other factors unaccounted for in our dataset that could have an effect on MPG.
* The slope is not considered zero. Our p-value = 5.35e-11 (orange box) is lower than our significance level. Therefore, there is significance evidence to reject the null hypothesis. By rejecting our null hypothesis, we are saying the relationship between our variables and MPG is subject to more than random chance. 
* Regardless of our findings above, the r-squared value of 0.7149 (blue box) tells us the model is 71% accurate which is pretty good, of course there is still room for improvement.

## Summary Statistics on Suspension Coils
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_total_summary.PNG)
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot_summary.PNG)
## T-Tests on Suspension Coils
Suspension Coils Cumulative T-Test
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_cumulative_ttest.PNG)
* Comparing results from the t-test across all lots shows they are not statistically different from the population mean. With the p-value being 0.06028 we fail to reject the null hypothesis.

![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot1.PNG)
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot2.PNG)
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot3.PNG)
## Study Design: MechaCar vs Competition
