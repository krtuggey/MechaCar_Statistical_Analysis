# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- The vehicle_weight, spoiler_angle, and AWD variables provided a non-random amount of variance to the mpg values in the dataset.
- The slope of the linear model is not considered to be zero in this situation. This is because the p-value value is less than zero.
- This linear model predicts mpg of MechaCar prototypes somewhat effectively: the R squared value is 71.49% percent, meaning that 71.49% of predictions will be correct using the linear model.

![1](https://user-images.githubusercontent.com/84139177/135758461-c067d1e5-71f0-4ee9-9774-957a7e801251.png)

## Summary Statistics on Suspension Coils

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data in total, lot 1, and 2 meets the design specification. Lot 3 does not. 

![2a](https://user-images.githubusercontent.com/84139177/135759116-d4ce9e88-7427-4ce3-834d-444f07694f79.png)
![2b](https://user-images.githubusercontent.com/84139177/135759118-25d0848d-0849-47ca-9f25-ea5dc5bd84da.png)

## T-Tests on Suspension Coils

- In these t-tests, we find that the p values for lot 1 and lot 2 are 1 and 0.6072, respectively. Lot 3's p value is 0.04168. Additionally, the data shows that lot 3 has a lower mean and the most variance. To summarize, lot 3's performance should be addressed or simply not used at all in the production of the MechaCar.

![3](https://user-images.githubusercontent.com/84139177/135759554-19760bed-6da7-4054-abdd-e226dbadb888.png)

