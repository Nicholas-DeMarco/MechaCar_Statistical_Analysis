# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Screenshot (154)](https://user-images.githubusercontent.com/114521887/217589834-b6905906-e316-439f-b40e-3638d35f7ad8.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  The vehicle length and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the mpg values in the dataset. This means that they will each have a large impact on miles per gallon on the MechaCar prototype. Also looking at our above output, we can see that the vehicle weight, spoiler angle, and AWD have p-values that indicate a random amount of variance with the dataset.

Is the slope of the linear model considered to be zero? Why or why not?

  Our p-Value comes out to be 5.35e-11. This value is much smaller than the assumed significance level of 0.05%. This is showing that we have enough evidence to reject our null hypothesis, which also shows that the slope of this linear model is not zero.
  
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  Our linear model came out with an r-squared value of 0.7149, which is stating that about 71% of all mpg predictions will be determined by this model. The multiple regression model does predict mpg of MechaCar prototypes effectively.
