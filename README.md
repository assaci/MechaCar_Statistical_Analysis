# MechaCar_Statistical_Analysis

The purpose of this project is to perform a retrospective analysis of vehicle data.
We will use R programming to analyze statistical information, interpret results and provide recommendations to help AutosRUS management in the decision-making process to improve the manufacturing unit.

## Linear Regression to Predict MPG

The MechaCar prototypes were manufactured using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle.
For our study to predict the mpg of MechaCar prototypes,  we used a dataset that contains mpg test results for 50 prototype MechaCars. We performed linear regression to determine the coefficient of the variable, the P-value, and the R-squared. 

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 
The statistical results shows that vehicle_weight, spoiled_angle, and ADW provide a non-random amount of variance to the mpg value in the dataset. Vehicle length and ground_clearance are statistically unlikely to provide random amounts of variance to the linear model. 

- Is the slope of the linear model considered to be zero? Why or why not?

From our findings, the P-value is 5.35e-11 which is smaller than the significant level of 0.05%. Therefore,  the slope of the linear model is not considered to be zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

R-squared is 0.714 which means aprroximattely 71% of variation in mpg values can be explained by our model (vehicle_lengtgh, vehicle_weight, spoiler_angle, ground_clearance and AWD).

![Linear_Regression](https://github.com/assaci/MechaCar_Statistical_Analysis/blob/main/Linear_Regression.PNG?raw=true)

## Summary Statistics

The MechaCar Suspension_Coil dataset included the results from multiple manufacturing lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots. 
For our analysis we created a summary statistics table to show:
- The suspension coil’s PSI continuous variable across all manufacturing lots
- The following PSI metrics for each lot: mean, median, variance, and standard deviation.

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

From statistical results, the variances for Lot 1, Lot 2, and Lot 3  are 0.979 7.469, and 170.286. The required weight capacities for suspension coils should not exceed 100 pounds.  Lot 1 and Lot 2 have variances less than 100, therefore they meet the design specifications for the MechaCar suspension coils. On the other hand, Lot 3 variance is more than 100 pounds. Consequently, it does not meet the suspension coils manufacturing requirements. 

![total_summary](https://github.com/assaci/MechaCar_Statistical_Analysis/blob/main/total_summary.PNG?raw=true)

![lot_summary](https://github.com/assaci/MechaCar_Statistical_Analysis/blob/main/lot_summary.PNG?raw=true)
