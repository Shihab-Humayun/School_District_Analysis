# School_District_Analysis

## Project Overview - Explain the purpose of this analysis.
The purpose of this school district analysis is to implement the loc method with conditional statements and comparison and logical operators to select the 9th grade reading and math scores from Thomas High School. After that, I used the Pandas NumPy module to change the reading and math scores to NaN. With the 9th grade math and reading scores changed to NANs, I recreated the metrics which are the district summary, the school summary, the top 5 and bottom 5 performing schools, based on the overall passing rate, the average math score for each grade level from each school, the average reading score for each grade level from each school, and the scores by school spending per student, by school size, and by school type.

## Results

* How is the district summary affected?

The information that has been affected in the district summary are Average Math Score, % Passing Math, % Passing Reading, and Overall Passing. This was caused by entering all the 9th grade reading and math scores from Thomas High School as NaNs. The Average Math Score went from 79.0 to 78.9. The % Passing Math went from 75.0 to 74.8. The % Passing Reading went from 85.8 to 85.7. The % Overall Passing went from 65.2 to 64.9. This is to be expected because the 9th grade students who did pass are not included anymore.

* How is the school summary affected?

There is a significant increase in the % Passing Math, % Passing Reading, and Overall Passing data. This changed Thomas High School from being one of the lowest performing school into the second best performing school. The following data shows the increase in % after updating the values.

Before
Thomas High School | Charter |	1635 |	$1,043,130.00 |	$638.00 |	83.350937 |	83.896082 |	66.911315 |	69.663609 |	65.076453

After
Thomas High School |	Charter | 1635 |	$1,043,130.00 |	$638.00 |	83.350937 |	83.896082 |	93.185690 |	97.018739 |	90.630324

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The math and reading scores have not changed. This still puts Thomas High School in the higher end in terms of performance relative to other schools.

![school](https://user-images.githubusercontent.com/49353083/111880764-b24c5480-8983-11eb-93c0-00791ed88987.png)

How does replacing the ninth-grade scores affect the following:
*   Math and reading scores by grade

The math score in the 9th grade was 83.6 and reading score was 83.7 before changing the 9th grade math and reading score to NaN. The other grade levels did not have their math and reading score values change. The tenth, eleventh, and twelth grade math scores are 83.1, 83.5, 83.5, respectively. The tenth, eleventh, and twelth grade reading scores are 84.3, 83.6, 83.8, respectively.

*   Scores by school spending


*   Scores by school size


*   Scores by school type


## Summary
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
