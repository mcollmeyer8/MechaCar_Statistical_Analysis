# MechaCar_Statistical_Analysis

## Overview

Jeremy has been approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Results

### Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/93055450/158878104-15f5db2e-dfa9-4c5f-ad06-e403bdcdbfc5.png)

- Variables/coefficients which provided a non-random amount of variance to the mpg values in the dataset are vehicle_length and ground_clearance.
- The p-value of our linear regression is 5.35e-11. This is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.
- This linear model does predict mpg of MechaCar prototypes effectively. Multiple R-squared is 0.7149, which indicates that the model is 71% accurate.

### Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/93055450/158883008-ef6e6b6f-b1c5-4354-8429-c6a81dd1b362.png)

![image](https://user-images.githubusercontent.com/93055450/158883143-c3dc73c1-a8b7-409a-92d8-a855991db176.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Our numbers are fine for the total_summary data: 62.29356 Variance. However, Lot3 has an issue as its variance is 170.2861224.

### T-Tests on Suspension Coils

The PSI for each manufacturing lot is not very statistically different from the population mean of 1,500 pounds per square inch. 
The p-value is not low enough for us to reject the null hypothesis for Lot 1 (p-value=1) and 2(p-value=0.6072), but it is for Lot 3 (p-value= 0.04168).

![image](https://user-images.githubusercontent.com/93055450/158884636-83b89d76-82c6-49fa-a5f3-9caea9843c86.png)
