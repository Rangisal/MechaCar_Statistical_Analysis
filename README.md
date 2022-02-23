# MechaCar_Statistical_Analysis
  The MechaCar_mpg.csv dataset consists mpg test results for 50 prototype MechaCars and there were produced using multiple design specifications to identify ideal vehicle         performance such as  vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance collected for each vehicle. Using the knowledge of R, 
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis and write a summary interpretation of the findings.

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/93173498/155427640-de7e4267-cce5-4528-adcb-b3bba7f92048.png)


![image](https://user-images.githubusercontent.com/93173498/155427709-53bc1ac1-3fc3-496f-b88c-3007ac273159.png)


- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  According to the above outcome vehicle length and vehicle ground clearance are likely to provide non-random amount of variance to the mpg, hence they have significant impact   on mpg of the given datast. 
- Is the slope of the linear model considered to be zero? Why or why not?

  The linera model is not zero as the p-value of the above is 5.35e-11 which is lower than the significance level of 0.05% and there are sufficient evidence to reject null       hypothesis.
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  This model does predict effectively about the mpg as the r-squared 0.7149 
  
  ## Summary Statistics on Suspension Coils
  The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested   to determine if the manufacturing process is consistent across production lots. Using R,summary statistics table has been created to show,

  - The suspension coil’s PSI continuous variable across all manufacturing lots
  - The following PSI metrics for each lot: mean, median, variance, and standard deviation.
  - Briefly detail and interpret the suspension coil summary statistics.
