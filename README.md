# MechaCar Statistical Analysis

## Linear Regression to Predict MPG

In this exercise we are identifying which variables (length, weight, spoiler angle, ground clearance, AAWD capabilities, MPG, PSI) are related to MechaCar prototype to predict and compare their performance across different manufacturer lots.


**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

Ground clearance, vehicle length, and the intercept provided a non-random amount of variance to the mpg values in the dataset because their p-values were below 0.05.

**Is the slope of the linear model considered to be zero? Why or why not?**

The slope of the linear model **is not** considered to be zero because the p-value is smaller than the assumed significance level of 0.05. There is significant linear relationship between variables and mpg of MechaCar prototype

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

This linear model does predict mpg of MrchaCar prototypes effectively because r-squared of 0.7149 indicates a strong positive linear correlation. 

![](Resources/Capture1.PNG)

## Summary Statistics on Suspension Coils

When looking at all lots, the variance suggests that the current manufacturing data meets the 100 pounds per square inch limitation. However, when we look at each lot individually, we can see that the third lot shows a higher variance and exceeds the 100 PSI requirement. 

![](Resources/Capture2.PNG)

![](Resources/Capture3.PNG)

## T-Tests on Suspension Coils

Since the p-value for the entire lot equals 0.06, we fail to reject the null hypothesis at a significance level of 0.05.
The same applies to lots 1 and 2; however, lot 3 had a p-value of 0.04168 meaning that we can reject the null hypothesis.

![](Resources/Capture4.PNG)
![](Resources/Capture5.PNG)
![](Resources/Capture6.PNG)
![](Resources/Capture7.PNG)

## Study Design: MechaCar vs Competition

An additional statistical study to perform is how safe is MechaCar compared to its competition. For this study we can test and analyze safety ratings based on vehicle size and weight.
The null hypothesis could be that heavier and bigger cars are no safer than smaller and lighter cars. The alternative hypothesis could state that the heavier the car, the safer it is.

For this study we can perform the ANOVA test to test the means of a single dependent variable across a single independent variable. We would need the vehicle weight, vehicle size, and safety ratings for both MechaCars and its competitors.


