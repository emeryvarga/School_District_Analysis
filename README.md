# School_District_Analysis

## Overview
This analysis provides insights to the school board on which strategic decisions at the school and district level will be based on. More specifically, this report analyzes school and district metrics before and after the math and reading scores for Thomas High School (THS) were omitted due to academic dishonesty.

## Resources
* [schools_complete.csv](Resources/schools_complete.csv)
* [students_complete.csv](Resources/students_complete.csv)

## Development Environment
* Python 3.7.10
  * Pandas library
  * Numpy library
* Anaconda 4.10.3
* Jupyter Notebook 6.1.4

## Results

### District Summary
As seen in Figure 1 and Figure 2, taking Thomas High School ninth graders out of the equation had the following effects on the district summary metrics:

* Total Students decreased by 461
* Average Math Score decreased by <1%
* Average Reading Score remained unaffected
* % Passing Math decreased by <1%
* % Passing Reading decreased by <1%
* % Overall Passing decreased by <1%

![District_Summary](Resources/District_Summary.png)
*Figure 1: District summary before data cleanup*

![District_Summary_Clean](Resources/District_Summary_Clean.png)
*Figure 2: District summary after data cleanup*

### School Summary
Cleaning the data had the addected Thomas High School's metrics in the following ways:

* % Passing Math decreased from 93% to 67%
* % Passing Reading decreased from 97% to 70%
* % Overall Passing decreased from 91% to 65%

### School Rankings

Before the the data cleanup, THS was ranked third in the district (see Figure 3). After cleaning the data, their ranking fell to eighth place, as seen in Figure 4.

![Top_Schools](Resources/Top_Schools.png)
*Figure 3: School rankings before data cleanup*

![Top_Schools_Clean](Resources/Top_Schools_Clean.png)
*Figure 4: School rankings after data cleanup*


How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary

