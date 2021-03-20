# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
![Linear_Regression](https://github.com/assaci/MechaCar_Statistical_Analysis/blob/main/Linear_Regression.PNG?raw=true)

From the finding we can see that veihicle_weight, spoiled_angle and ADW provides a non-random amount of variance to mpg valuein the dataset.Vehicle lentgh and ground_clearance are statistically unlikely to provide random amounts of variance to the linear model. 


- Is the slope of the linear model considered to be zero? Why or why not?
-
The slope of the linear model is not considered to be zero because the P-value is 5.35e-11 which is smaller than the significant level of 0.05%.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

R-squared is 0.714 which means aprroximattely 71% of variation in mpg values can be explained by our model (vehicle_lengtgh, vehicle_weight, spoiler_angle, ground_clearance and AWD).



