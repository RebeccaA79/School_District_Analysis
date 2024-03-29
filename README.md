# School_District_Analysis

## Project Overview

A data analysis was prepared over school district standardized testing scores to assist the school board in deciding how to allocate school budgeting and resources across the school district. After completing the initial analysis, it was noted that the data file used in the analysis (students_complete.csv) showed signs of academic dishonesty in math and reading scores, specifically for Thomas High School ninth graders. Since the full scale of academic dishonesty is not known, a second analysis over the data has been requested. In the second analysis, all math and reading scores for 9th grade Thomas High School students will be replaced with NaNs and the complete district analysis will be re-run. The following report shows a summary of how the changes in data affected the overall analysis of standardized test scores. The school board will can use this information to determine how significant the impact is on the results and whether further analysis is warranted. 

## Results
The following bullets summarize how removing Thomas High School 9th grade scores impacted the original analysis

1. District Level Impacts:

- There was minimal impacts to the average math and reading scores at the district-level. Average reading scores remained at 81.9 and the average math score dropped from 79 to 78.9. 
- The passing math % and passing reading %, however, were noticeably impacted. Passing math % dropped from 87% to 74.8% and Passing reading % dropped from 100% to 85.7%.

![Link to School District Analysis Comparison](https://github.com/RebeccaA79/School_District_Analysis/blob/main/Resources/District_Summary_Analysis_Comparison.png)
  
2. School Summary Impacts:

With the exception of Thomas High School, there were no impacts to the School Summary Analysis data for the remaining high schools See the next bullet on how Thomas High School was impacted.

3. The passing math, reading, and overall percentages for Thomas High School declined (approximately 25%) once the ninth-grade math and reading scores were replaced. In the updated School Summary, Thomas High School’s performance is significantly lower in comparison to the other schools.

4. How does replacing the ninth-grade scores affect the following:
  
    a. Math and reading scores by grade
    
    The math and reading scores for 9th grade at Thomas High School were updated to NaN. 
    Math and reading scores for all other grades and High Schools  remained unchanged.

    b. Scores by school spending, school size, and school type
    
    There were no impacts to scores categorized by school spending, school size, or school type.
 

## Summary
After the reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, the most noted impacts to the district analysis included:

 - At the district level, passing math % dropped from 87% to 74.8% and passing reading % dropped from 100% to 85.7%.
 - Thomas High School’s passing math, reading, and overall percentages decreased by approximately 25%.
