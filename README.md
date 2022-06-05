# RUTGERS-MechaCar_Analysis

&nbsp;&nbsp;&nbsp;&nbsp; Before running the report, make sure the following packages are installed within RStudio. If they are not, certain information will not appear.
![](https://github.com/JeanPyerC/RUTGERS-MechaCar_Analysis/blob/main/Challenge/Photo/Pic01.png)


## Deliverable 1
1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    - intercept, vehicle length, and ground clearamce.

2. Is the slope of the linear model considered to be zero? Why or why not?
    - No because p-value equals to 5.35e-11.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
    - With an R2 of 0.7149 this model is effective in predicting MPG.

![](https://github.com/JeanPyerC/RUTGERS-MechaCar_Analysis/blob/main/Challenge/Photo/Pic07.png)

## Deliverable 2

4. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
    - The current manufacturing data does meet the specifications for all manufacturing lots in general (varience = 62.29), but not for each lot individually. 
            - Lot 1 has a variance of 0.98
            - Lot 2 has a variance of 7.47
            - Lot 3 has a variance of 170.29
![](https://github.com/JeanPyerC/RUTGERS-MechaCar_Analysis/blob/main/Challenge/Photo/Pic05.png)
![](https://github.com/JeanPyerC/RUTGERS-MechaCar_Analysis/blob/main/Challenge/Photo/Pic06.png)


## Deliverable 2
&nbsp;&nbsp;&nbsp;&nbsp; The t-test from Lot 1 has a p-value = 1, the t-test from Lot 2 has a p-value = .6072, and the t-test from Lot 3 has a p-value = .04168.
![](https://github.com/JeanPyerC/RUTGERS-MechaCar_Analysis/blob/main/Challenge/Photo/Pic08.png)


## Study Design: MechaCar vs. Competition
&nbsp;&nbsp;&nbsp;&nbsp; A study I would like to look into, would be to look at if fuel efficiency has an effect on safety rating. Larger cars appear to be safer than smaller cars, while smaller cars tend to get better gas mileage. This relates to today's era, where a pick-up truck will be safer, however it has the worst miles per gallon. I'd like to look at if there is a correlation between the two. 




