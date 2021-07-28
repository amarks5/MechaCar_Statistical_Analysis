# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/linear_regression_predict_mpg_image.png)
* Vehicle Length and Ground Clearance are the most significant variables in our dataset (denoted by arrows) indicating a non-random effect on the MPG. Our p-values for Vehicle Length = 2.60e-12 and Ground Clearance = 5.21e-08. In addition, the intercept was statistically significant, suggesting there are other factors unaccounted for in our dataset that could have an effect on MPG.
* The slope is not considered zero. Our p-value = 5.35e-11 (orange box) is lower than our significance level. Therefore, there is significance evidence to reject the null hypothesis. By rejecting our null hypothesis, we are saying the relationship between our variables and MPG is subject to more than random chance. 
* Regardless of our findings above, the r-squared value of 0.7149 (blue box) tells us the model is 71% accurate which is pretty good, of course there is still room for improvement.

## Summary Statistics on Suspension Coils
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_total_summary.PNG)
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot_summary.PNG)
* When looking at the Total Summary data above, we see the variance is well below the 100 psi limit and meets the specifications. However, when you look at the lots individually you can clearly see there is something wrong with Lot 3. Lot 3 is much higher than the acceptable limit coming in at 170.29.
## T-Tests on Suspension Coils
Suspension Coils Cumulative T-Test
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_cumulative_ttest.PNG)
* Comparing results from the t-test across all lots shows they are not statistically different from the population mean. With the p-value being 0.06028 we fail to reject the null hypothesis.
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot1.PNG)
* Reviewing the t-test results for just Lot 1 we see they are not statistically different from the population mean. The p-value = 1 so we fail to reject the null hypothesis.
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot2.PNG)
* Reviewing the t-test results for Lot 2, we see they are not statistically different from the population mean. The p-value = 0.6072, we fail to reject the null hypothesis.
![alt text](https://github.com/amarks5/MechaCar_Statistical_Analysis/blob/main/images/suspension_coil_lot3.PNG)
* Reviewing the t-test results for Lot 3, we observe it is slightly statistically different from the population mean. The p-value = 0.0417, so we can reject the null hypothesis. (We should take a closer look at this lot)

## Study Design: MechaCar vs Competition
Consumers have many factors in play when deciding on purchasing a car. One that seems to stand out most would be fuel efficiency. 
### Metric to Test
City and highway fuel efficiencies
### Null and Alternative Hypothesis
* Null Hypothesis: Cars in the same vehicle class have the same fuel efficiency.
* Alternative Hypothesis: Cars in the same vehicle class do not have the same fuel efficiency.
### Statistical Test
Using an ANOVA test for an analysis of the types of fuel efficiencies. In addition, I would use a boxplot to see the potential spread between different cars.

### Data Needed for Statistical Test
We would need a sample size of 50 cars with the fuel efficiency data for each car in the class type.

