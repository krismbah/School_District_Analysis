# School_District_Analysis

## Overview of the School District Analysis

The purpose of this analysis is to assist Maria in creating a high-level snapshot of the district's key metrics and present them in a table format. In order to do so, the following metrics/tasks need to be completed: 

1. Top 5 and bottom 5 performing schools, based on the overall passing rate
2. The average math score received by students in each grade level at each school
3. The average reading score received by students in each grade level at each school
4. School performance based on the budget per student
5. School performance based on the school size 
6. School performance based on the type of school


## Results

- How is the district summary affected?
The distrct summary was created by first merging the student and school dataframes. New variables were created to calculate total student count, total school count, average reading score, and average math score. Student data from ninth grade students from Thomas High School (THS) was omitted. Passing rates for the new student total at THS were calculated in regards to math and reading.  Passing percentages were also calculated. The aforementioned metrics were then compiled into a new dataframe called "district_summary_df" with the following format to generate the output below:
![District_Results1](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results1.jpg)

- How is the school summary affected?
Using the school data, an index of school type was created. Metrics regarding total student count, total school budget, per capita spending, average test scores, passing scores for math and reading, number of students passing math and reading by school, percentage of students passing math and reading scores by school, total students that passed math and reading by school and their percentages. The aforementioned metrics were then compiled into a new dataframe called "per_school_summary_df" with the following format to generate the output below:
![School_Results2](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results2.jpg)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth graders' improved average math and reading scores. However, it lowered the percentage of students passing math, reading, and both subjects overall. THS didn't change from its number two ranking. Which indicates that the ninth graders' reading and math scores were indeed negligible. 

Old results:
![THS_Old_Results3](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results3.jpg)

New results:
![THS_New_Results4](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results4.jpg)

- How does replacing the ninth-grade scores affect the following:

    -Math and reading scores by grade:
     Replacing the ninth-grade scores didn't affect the math and reading scores of any other grade at THS.
    
    -Scores by school spending:
     Due to rounding, I am not certain that replacing the ninth-grade scores didn't affect math and reading scores by school spending. But it appears that way.
    
    -Scores by school size:
     Due to rounding, I am not certain that replacing the ninth-grade scores didn't affect math and reading scores by school size. But it appears that way.

    -Scores by school type:
     Replacing the ninth-grade scores improved the average reading score for "Charter" school types. However, the average math score was lowered and passing percentages were also lowered across the board.

Old results:
![Ninth_Old_Results5](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results5.jpg)

New results:
![Ninth_New_Results6](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results6.jpg)

## Summary

To summarize, the following changes to the school district analysis were made after ninth-grade reading and math scores from Thomas High School were omitted:

1. Reading and math scores were improved at THS.
2. The percentage of students passing math, reading, and both subjects overall declined.
3. Average reading scores for Charter schools improved.
4. Average math scores and passing percentages for math, reading, and overall declined for Charter schools.
