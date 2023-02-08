# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Screenshot (154)](https://user-images.githubusercontent.com/114521887/217589834-b6905906-e316-439f-b40e-3638d35f7ad8.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  The vehicle length and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the mpg values in the dataset. This means that they will each have a large impact on miles per gallon on the MechaCar prototype. Also looking at our above output, we can see that the vehicle weight, spoiler angle, and AWD have p-values that indicate a random amount of variance with the dataset.

Is the slope of the linear model considered to be zero? Why or why not?

  Our p-Value comes out to be 5.35e-11. This value is much smaller than the assumed significance level of 0.05%. This is showing that we have enough evidence to reject our null hypothesis, which also shows that the slope of this linear model is not zero.
  
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  Our linear model came out with an r-squared value of 0.7149, which is stating that about 71% of all mpg predictions will be determined by this model. The multiple regression model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

Total Summary

![Screenshot (156)](https://user-images.githubusercontent.com/114521887/217595699-4b1ba72b-0aec-4e6a-92a2-4e29a294f02c.png)

Lot Summary

![Screenshot (157)](https://user-images.githubusercontent.com/114521887/217595725-0332af26-03c9-45ae-bd5a-48c0caea87c0.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

  When we look at each lot as a whole, the variance of the coils is 62.29 PSI. This falls within the range of the 100 PSI variance requirement. However, as we separate each lot and look at them individually, we can see some key differences. Lot 1 has a PSI variance of 0.98 and Lot 2 has a PSI variance of 7.47. Lot 3 is showing a very large PSI variance of 170.29. Even though as a whole the PSI variance falls within range, we can see that Lot 3 is causing the disproportionate variance when we look at all 3 lots together.

## T-Tests on Suspension Coils

All manufacturing lots

![Screenshot (160)](https://user-images.githubusercontent.com/114521887/217603796-4a6fc966-8310-4cb0-9b83-75b9fbc991f0.png)

Each manufacturing lot separately

![Screenshot (161)](https://user-images.githubusercontent.com/114521887/217603887-b6fef47d-96c1-4549-a252-fb0be1060005.png)

  When we look at all of the manufacturing lots together, the true mean of the sample is 1498.78. The p-Value is 0.06. That value is higher than the common significance level of 0.05. This is telling us that there is not enough evidence to support rejecting the null hypothesis.
  
  As we look at each lot individually, we come to some other findings. Lot 1 has a true sample mean of 1500 and a p-Value of 1. This is telling us that we can accept the null hypothesis that there is no statistical difference between the presumed population mean of 1500 and the observed sample mean. Lot 2 has a sample mean of 1500.02 and a p-Value of 0.61. In accordance with Lot 1, the null hypothesis for Lot 2 can also be accepted. Lot 3 has a sample mean of 1496.14 and a p-Value of 0.04. This p-Value for Lot 3 is lower than the common significance value of 0.05. This means that we can reject the null hypothesis that this sample mean and presumed population mean are not statistically different.
  
## Study Design: MechaCar vs Competition

  A statistical study can be designed to compare the performance of MechaCar vehicles against vehicles from other manufacturers. The study will focus on the following metrics: cost, city fuel efficiency, horse power, maintenance cost, and safety rating. These metrics have been chosen as they are of interest to a consumer and can help quantify the performance of MechaCar vehicles against the competition.

The null hypothesis of this study is that there is no difference in performance between MechaCar vehicles and vehicles from other manufacturers. The alternative hypothesis is that MechaCar vehicles perform differently from vehicles from other manufacturers in at least one of the metrics tested.

To test the hypothesis, a two-sample t-test will be used. A t-test is appropriate for this study as the sample size is large and the population standard deviation is unknown. The t-test will be used to determine if there is a significant difference in the means of the two groups (MechaCar vehicles and vehicles from other manufacturers) for each metric.

The data needed to run the statistical test includes the values for each metric for a sample of MechaCar vehicles and a sample of vehicles from other manufacturers. The sample size should be large enough to ensure that the results are statistically significant. The data should be collected in a systematic and standardized manner to ensure accuracy and reliability.
