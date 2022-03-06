# MechaCar_Statistical_Analysis

## **Overview**

Fictional company AutosRUs' newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team's progress. AutosRUs' senior management enlisted assistance from the data analytics team to review the production data for insights that may help the manufacturing team overcome their production issues.

## **Linear Regression to Predict MPG**

In this porion of the analysis a multivariate linear regression model was formulated to determine which variables in a dataset predict MPG of MechaCar prototypes. The following variables provided a non-random amount of variance to the mpg values in the MechaCar_mpg dataset:

* vehicle_length
* ground_clearance

The p-value of this multiple linear regression analysis is 5.35 x 10(-11), which is much smaller than the assumed significance level of 0.05%; therefore, there is sufficient evidence to reject the null hypothesis since the slope of the linear model is not zero.

This linear model predicts that roughly 71% of MPG predictions of MechaCar prototypes will be correct when using this model. This multiple linear regression model has an R-value of 0.71, which means that the model is successful at explaining 71% of the variation in MPG values.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)


## **Summary Statistics on Suspension Coils**

Design specifications for MechaCar suspension coils dictates that the variance of the suspension coils must not exceed 100 pounds per square inch (PSI).

The variance of the suspension coils for all three lots was 62.29. This is within MechaCar design specifications.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

When examining the PSI of suspension coils in Lots 1, 2, and 3 individually, analysis indicated that the variance in Lots 1 and 2 are below 100 PSI, so suspension coils in Lots 1 and 2 are within MechaCar design specifications.

The variance for suspension coils in Lot 3 was 170.28, which exceeds MechaCar design specifications.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)


## **T-Test on Suspension Coils**
A one-sample t-test was used to determine whether or not if PSI across all manufacturing lots was statistically different from the population mean of 1500 PSI.

The distribution of the suspension coil dataset was visualized with a density plot, which showed that the suspension coil dataset was nearly normally distributed around the mean.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

For all t-tests conducted, the significance level was 0.05 percent. The t-test compared the means of the Suspension Coil dataset, which was 1498.78, against a mean of 1500. All t-tests conducted resulted in the means being statistically similar.

A t-test across all suspension coil manufacturing lots gave a p-value of 0.06 Since this is above the significance level, the two means are statistically similar.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

A t-test for Lot 1 gave a p-value of 1, which is above the significance level. The two means are statistically similar.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

The p-value for the Lot 2 t-test was 0.6072. This is above the significance level of 0.05 results in the two means being statistically similar.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

The calculated p-value from the Lot 3 t-test was 0.4168. This is above the 0.05 significance level and results in the means being statistically similar. This means that lot 3 has the most variance and lowest PSI average. This could mean that Lot 3 should not be used within the MechaCar.

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)


## **Study Design: MechaCar vs Competition**

When it comes to comparing the MechaCar to its competition, the company should consider using an ANOVA test to compare the MechaCar in various categories that customers would care about: cost, city and highway fuel efficiency, horse power, safety rating, maintenance cost. ANOVA test is able to test to see if the means from multiple different samples are significantly similar or different. This means that the averages of different cars in these categories can be compared to the average of MechaCar. If the p value is greater than 0.05, then MecaCar has the same or similar performance within these categories (the null hypothesis). If the p value is less than 0.05, then MecaCar is significantly different in those categories. If it is significant different, then looking at the average of the MecaCar is the next step. If MecaCar's average is either below or above the other averages would show how it is performing against its competitors (below = worse, above = better).