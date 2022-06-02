# School_District_Analysis
## Overview of Project
## Purpose
A school district asked for a snapshot of several key metrics. The primary analysis was centered on the performance of math and reading scores preparation for a board meeting.  After the review of the Data, it was determined that the 9th grade class was suspect of cheating and the school board asked for the data to be analyzed again for better comparison.

## Overview
* A high-level snapshot of the district's key metrics, presented in a table format
* An overview of the key metrics for each school, presented in a table format
* Tables presenting each of the following metrics:
    * Top 5 and bottom 5 performing schools, based on the overall passing rate
    * The average math score received by students in each grade level at each school
    * The average reading score received by students in each grade level at each school
    * School performance based on the budget per student
    * School performance based on the school size 
    * School performance based on the type of school
Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.

## Results

### How is the district summary affected?
Adjusted Analysis:
![This is an image](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_dist_sum_2_decimals.PNG)

When comparing the two charts, removing less than 500 test scores had very little impact on the almost 40,000 student data set. 

### How is the school summary affected?

Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being too high.  After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.  

Original Analysis:
![Pic 3](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_THS_90.PNG)

Adjusted Analysis:
![Pic 4](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_THS_65.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
In the original analysis, Thomas High School ranked 2nd in the district raising suspicion wihtin the school district
Original Analysis:
![Pic 5](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_top_5_schools.PNG)

After adjustment of the 9th grade data, Thomas High School ranked in the middle

Adjusted Analysis:
![Pic 6](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_bottom_8_schools.PNG)


### Adjusted Averages using the Math and Reading Scores 

The scores have been replaced with null values and shows up in Python programming as NaN in the following charts. 

![Pic 7](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_math_by_grade_HS.PNG)
![Pic 8](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_read_by_grade_HS_correct.PNG)

### Scores by school spending

Thomas High School falls in the $630-$644/student spending range.  However, the hundredths place was needed to see the nominal changes. 

Original Analysis:
![Pic 9](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_spend_updated.PNG)

Adjusted Analysis:
![Pic 10](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_spending_updated.PNG)

There was very little  impact by changing the 9th grade scores. 

### Scores by school size
Original Analysis:
![Pic 11](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_size_updated.PNG)

Adjusted Analysis:
![Pic 12](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_size_updated.PNG)

There was very little impact by campus size due to changing the 9th grade scores. 

### Scores by school type

Original Analysis:
![Pic 13](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_type_updated.PNG)

Adjusted Analysis:
![Pic 14](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_type_updated.PNG)

There was very little impact by school type by changing the 9th grade scores. 

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed drastically

2. Thomas High School's ranking dropped from 2nd position to 8th

3. Data at the grade level will now show as "NaN" in reports for all of  the 9th grade students 

4. Campus math and reading averages and passing percentages all saw substantial shifts 

