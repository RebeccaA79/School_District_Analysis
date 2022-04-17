# School_District_Analysis

## Project Overview

A data analysis was prepared over school district standardized testing scores to assist the school board in deciding how to allocate school budgeting and resources across the school district. After completing the initial analysis, it was noted that the data file used in the analysis (students_complete.csv) showed signs of academic dishonesty in math and reading scores, specifically for Thomas High School ninth graders. Since the full scale of academic dishonesty is not known, a second analysis over the data has been requested. In the second analysis, all math and reading scores for 9th grade Thomas High School students will be replaced with NaNs and the complete district analysis will be re-run. The following report shows a summary of how the changes in data affected the overall analysis of standardized test scores. The school board will can use this information to determine how significant the impact is on the results and whether further analysis is warranted. 

## Results
Using bulleted lists and images of DataFrames as support, address the following questions:

1. How is the district summary affected?

Analysis at the district level shows that the average math and reading scores changed minimally. Average reading score remained at 81.9 and the average math score dropped from 79 to 78.9. The passing math % and passing reading %, however, were noticeably impacted. Passing math % dropped from 87% to 74.8% and Passing reading % dropped from 100% to 85.7%.

2. How is the school summary affected?

The passing math, reading, and overall percentages for Thomas High School declined (approximately 25%) once the ninth-grade math and reading scores were replaced. In the updated School Summary, Thomas High School’s performance is significantly lower in comparison to the other schools. 

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
4. How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  - Scores by school spending
  - Scores by school size
  - Scores by school type

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

