# MechaCar_Statistical_Analysis-
The purpose of this challenge was to assist Jeremy and the data analytics team to perfom multiple things. I first had to do a multiple linear regression analysis which helps identify which variables in the dataset predict the mpg of MechaCar prototypes. Then, I obtained a summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
The final aspect of this challenge included running t-tests to determine if the manufacturing lots are statistically different from the mean population, as well as design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. 

In order to determine which variables in the dataset predict the mpg of Mechacar prototypes, the following linear regression was performed, which will provide us with important questions. 

<img width="842" alt="Screen Shot 2023-02-22 at 12 04 16 AM" src="https://user-images.githubusercontent.com/112040311/220530289-519024e3-560e-4ba6-87c6-e954d802e8c4.png">


Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Statistical significance on vehicle length, weight and ground clearance, also vehicle weight has some significance.

Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model has a p-value(3.35e-11) for that reason it is not considered zero. We need to consider that significance level is lower than 0.05.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes, because R-squared is near to 1 (0.715) indicating variables prediction based on: vehicle length, vehicle weight, ground clearance and the rest of the variables can predict over 71% percent of MPG performance for MechaCar prototypes.

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per inch. Does the current manufacturing data meet this design specification? Why or why not?

Looking at the descriptive statistics of the suspension coil data set we can see that the std dev is 7.89 which means that the variance will be under 100 regardless of which way we move the std dev. Mean = 1498.78 Median = 1500 Variance = 62.29 Std Dev = 7.89 
<img width="440" alt="Screen Shot 2023-02-22 at 12 11 44 AM" src="https://user-images.githubusercontent.com/112040311/220530883-55119daa-0382-45e7-ae49-e919d82a4f43.png">

The current manufactoring data meets the specifications the variance is 62.29356 and the stdev is 7.892627. This means that even if we move multiple standard deviations away from the mean the variance will still be under 100.

Suspension Coil T-test-

<img width="445" alt="Screen Shot 2023-02-22 at 12 33 55 AM" src="https://user-images.githubusercontent.com/112040311/220532053-29ee6065-95dd-4fa3-80f4-5689c29e5a37.png">

Design Study-
The areas I believe that consumers will care about is fuel efficiency. I would like to see if Mechacar has better gas millage than the competition, however, Some of the variables I would add to the analysis are: horsepower, maintenance, safety, and cost. These variables will not only help the performance of the car, but will also allow the mpg to be maintained. Additional things would increase the likelyhood of future consumers purchasing this car would be: growing variety in the automotive industry we would need modern vibrant colors for our vehicle. Also need to consider performance and tech optional addons, such as leather seats, bluetooth, surround sound speakers, lane assist etc.
