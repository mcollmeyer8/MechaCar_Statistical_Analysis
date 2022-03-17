# MechaCar_Statistical_Analysis

## Overview

Jeremy has been approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Results

### Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/93055450/158878104-15f5db2e-dfa9-4c5f-ad06-e403bdcdbfc5.png)

- Variables/coefficients which provided a non-random amount of variance to the mpg values in the dataset are vehicle_length and ground_clearance.
- The p-value of our linear regression is 5.35e-11. This is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.
- This linear model does predict mpg of MechaCar prototypes effectively. Multiple R-squared is 0.7149, which indicates that the model is 71% accurate.
