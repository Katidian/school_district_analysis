# School District Analysis

## Overview
The school board requested analysis of data for the district's 15 high schools, including school type, size and budget, as well as math and reading
scores for all high school students. Among other things, district leaders wished to see how school performance (as measured by these scores) varied based on
type of school (charter or district), approximate size and per-student budget. 

After completion of our analysis, district leaders discovered irregularities in test scores for ninth graders at Thomas High School. Pending resolution of these 
issues, we removed the scores in question from our analysis of average math and reading scores. However, we kept the THS ninth graders in the analysis for 
purposes of calculating school sizes and per-student budgets.

## Results


Using bulleted lists and images of DataFrames as support, address the following questions.
Before:

![Screenshot of previous district summary](Resources/district_dataframe_before.png)

After: 

![Screenshot of updated district summary](Resources/district_dataframe.png)

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type



## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

For future reports, analysts should consider another method of calculating average test scores by spending range. This analysis calculated averages of 
per-school averages. This could mislead stakeholders by assigning equal weight to each school's average scores, regardless of how many students' scores were 
included in the average for each school. It would be better to assign a spending range category to each row of student data in the complete school data 
dataframe (school_data_complete_df), and then calculate the average of scores within each spending range bin.
