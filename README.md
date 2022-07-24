# MechaCar Statistical Analysis

## Linear Regression to Predict MPG

In this excercise we are identifying which variables (lenght, weight, spoiler anglr, ground clearance, AAWD capabiities, MPG, PSI) are related to MechaCar prototype to predict and compare their performance across differentmanufacturer lots.


**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

Ground clearance, vehicle length, and thr intercept provided a non-random amount of variance to the mpg values in the datase because their p-values were below 0.05.

**Is the slope of the linear model considered to be zero? Why or why not?**

The slope of the linear model **is not** considered to be zero because the p-value is smaller than the assumed significance level of 0.05.There is significant linear relationship between variables and mpg of MechaCar prototype

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

This linear model does predict mpg of MrchaCar prototypes effectively because r-squared of 0.7149 indicates a strong positive linear correlation. 

## Summary Statistics on Suspension Coils

write a short summary using screenshots from your total_summary and lot_summary dataframes, and address the following question:

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

## T-Tests on Suspension Coils

briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
