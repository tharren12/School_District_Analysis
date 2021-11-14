# School District Analysis

## Overview of Project

The school board has requested further analysis as there is evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. In this analysis the math and reading scores for Thomas High School have been replaced with NaNs (null variables), while keeping the rest of the data intact. The analysis results after having done this replacement are then being compared to the previous results with the math and reading scores from Thomas High School included. A full summary as to how these changes affected the overall analysis are included.

## Resources

* Data Source: schools_complete.csv, students_complete.csv

* Software: Python 3.6.8, Jupyter Notebook 6.0.0, Pandas Library 0.24.2

## School District Audit Results

### Overall School District Summary

#### *Original School District Summary*

![School District Summary - Original](https://user-images.githubusercontent.com/92001105/141684783-2baf2ab2-4057-44f2-860d-247b2db85fb8.png)

#### *Updated School District Summary*

![School District Summary - Updated](https://user-images.githubusercontent.com/92001105/141684787-3f8f9461-7135-442b-a258-f1466c7fca21.png)

* As observed above, the average reading scores remained the same and the average math scores and the passing rates for math, reading and overall have all declined slightly with the removal of the 9th grade scores from Thomas High School and from the overall school district.

### Per School Summary

#### *Original Per School Summary - Thomas High School*

![Per School Summary - Original](https://user-images.githubusercontent.com/92001105/141693654-101eb126-64da-47ff-a0de-981ea424db0a.png)

#### *Updated Per School Summary - Thomas High School*

![Per School Summary - Updated](https://user-images.githubusercontent.com/92001105/141694669-fa3f756d-12f7-4ad8-930a-b922b534f159.png)

* As observed above, the average math score remained the same and the average reading score actually improved slightly, however the passing rates for math, reading and overall have all declined slightly with the removal of the 9th grade scores

### Impact on Thomas High School's Relative Performance to Other Schools

#### *Original Top 5 School Summary*

![Top 5 Schools - Original](https://user-images.githubusercontent.com/92001105/141694982-bc6e27d7-4f30-451b-a1da-cf8d9e7c8b0b.png)

#### *Updated Top 5 School Summary*

![Top 5 Schools - Updated](https://user-images.githubusercontent.com/92001105/141694992-92aa8d36-dc03-41a7-b48d-82b26b0064c4.png)

* All of the 15 schools in the district were ranked based on the highest overall passing percentage and above the top 5 schools are shown. When including the 9th grader scores Thomas High School ranked #2 in the district, however, after excluding their scores Thomas High School's performance has now dropped to #3 overall

### Impact on Math and Reading Scores by Grade

* The only impact on the Math and Reading scores by grade was only for Thomas High School's grade 9 with the scores becoming null (NaN), but there was no other impact to the other school's grade 9s or Thomas High School's other grade levels

### Impact on Scores by School Spending Bands

* Since the overall impact is fairly insignificant for the removal of the grade 9 scores from Thomas High School, although they fell into the $630-644 range there was no observable change as the passing rates were rounded up to the closest whole number and did not change from the original analysis

### Impact on Scores by School Size

* Thomas High School falls into the Medium size range (1,000 to 2,000), however there are no visible differences with the original analysis

### Impact on Scores by School Type

* Thomas High School is a charter school, but once again no visible changes in averages or scores compared with the original analysis


## School District Analysis Summary

The following summary is the changes that were observed after the reading and math scores were replaced with NaNs for the ninth grade students at Thomas High School for the overall School District.

* Average Math Score declined from 79.0 to 78.9
* Average Reading Score remained similar at 81.9
* % Passing Math decreased from 75.0% to 74.8%
* % Passing Reading decreased from 85.8% to 85.7%
* % Overall Passing declined from 65.2% to 64.9%
