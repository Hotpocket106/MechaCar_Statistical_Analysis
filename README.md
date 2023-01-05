


## Linear Regression to Predict MPG

R script was applied to the dataset on variables to get the following coefficients.
![1](https://github.com/Hotpocket106/MechaCar_Statistical_Analysis/blob/main/image/1.png?raw=true)

### Summary of Linear Regression model
The strongest contributor of non-random variance seems to be the vehicle length with a p-value of 2.60e-12. The other strong contributor of non-random variance is the ground clearance with a p-value of 5.21e-8.

The slope of the linear model is not zero. We can see that the slope coefficients contain significant non-zero values (vehicle length, ground clearance, and AWD), and the p-values are less than the significance level of p=0.05.

Our r^2 value is 0.7149, which means the model does have good predictive power for the mpg.![2](https://github.com/Hotpocket106/MechaCar_Statistical_Analysis/blob/main/image/2.png?raw=true)

## Summary Statistics on Suspension Coils

Below is the summary statistics of all of the manufacturing lots. The mean is 1498.78 for this sample and the population mean was determined to be 1500.
![total](https://github.com/Hotpocket106/MechaCar_Statistical_Analysis/blob/main/image/total_sum.png?raw=true)
The means of the lot numbers are similar to the population mean and the sample mean.
![lots](https://github.com/Hotpocket106/MechaCar_Statistical_Analysis/blob/main/image/lot_sum.png?raw=true)

## T-Tests on Suspension Coils

All Manufacturing Lots: p-value = .6028, alpha = .05
.60 > .05, which means the total manufacturing lot is not statistically significant from the normal distribution and normality can be assumed. The mean falls within the 95% confidence interval.

Lot1 has the sample mean of 1500 with p-value of 1 we cannot reject the null hypothesis that there is no difference between the observed sample mean and the population mean. 
![t test](https://github.com/Hotpocket106/MechaCar_Statistical_Analysis/blob/main/image/lot1.png?raw=true)
Lot2 has similar results which mean equals to 1500.02, p-value of 0.61 the null hypothesis cannot be rejected.
![t test2](https://github.com/Hotpocket106/MechaCar_Statistical_Analysis/blob/main/image/lot2.png?raw=true)
Lot3 with a mean of 1496.14 and the p-value of 0.04 null hypothesis rejected.
![t test3](https://github.com/Hotpocket106/MechaCar_Statistical_Analysis/blob/main/image/lot3.png?raw=true)



## Study Design: MechaCar vs Competition

In order for us to compare our cars to the current market we need to address factors which would impact customer's interests like fuel effciency, power, safety rating and mainly the costs.

We will be testing whether or not the MechaCar has statistically significant differences in these metrics compared to competing models. The null hypothesis will be that these observables don't vary significantly from the competition, and the alternative hypothesis will be that the MechaCar does indeed vary significantly in these variables compared to the competition.

In order to run these statistical tests, we would need the cost, fuel efficiency, horsepower, safety rating, and carbon waste output data from the MechaCar as well as the MechaCar's competitors.