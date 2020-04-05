# School-District-Analysis

## Challenge Overview
After Maria discovered the math and reading score errors of all ninth graders at Thomas High School, you are tasked with replacing those specifc data points with a NaN value, and recreating all of the summaries. Once the student data is corrected and merged with the school data, and the summary dataframes are recreated, answer the following questions:
- How is the district summary affected?
- How is the school summary affected?
- How is Thomas High School's performance relative to other schools affected?
- How are math and reading scores by grade affected?
- How are scores by school spending affected?
- How are scores by school size affected?
- How are scores by school type affected?

## Challenge Summary

### District Summary
![new_district_summary](https://github.com/evanmgoodwin/School-District-Analysis/blob/master/new_district_summary.png)

The percentages of students passing math, reading and both in the district each decreased by 1%. There was little to no change for the average math and reading scores (the average math score decresed by 0.1%).

### School Summary
![new_school_summary](https://github.com/evanmgoodwin/School-District-Analysis/blob/master/new_school_summary.png)

In the new school summary, the average scores and percentages passing at Thomas High School were all affected by the removal of the ninth grade data. The decreases to the averages were infinitesimal (0.1% for reading and 0.05% for math). The percentages passing, however, decreased significantly. Math passing dropped by 26%, reading passing dropped by 27% and overall passing dropped by 26%.

### Thomas High School's Performance
![new_top_fice_performing_summary](https://github.com/evanmgoodwin/School-District-Analysis/blob/master/new_top_five_performing_summary.png)

As can be seen by the new top performing schools summary, Thomas High School is no longer in the top five. It dropped from second place to eigth place for overall performance, and is now the lowest performing of all the charter schools.


### Math and Reading Scores by Grade

The values for math and reading scores of Thomas High School ninth graders were replaced with the NaN; all other data was unaffected.

### Scores by School Spending
![new_scores_by_school_spending_summary](https://github.com/evanmgoodwin/School-District-Analysis/blob/master/new_scores_by_school_spending_summary.png)

The percentages of students passing math, reading and both decreased in the $630-644 spending range. Math passing decreased by 6%, while reading and overall both decreased by 7%.

### Scores by School Size
![new_scores_by_school_size_summary](https://github.com/evanmgoodwin/School-District-Analysis/blob/master/new_scores_by_school_size_summary.png)

Within the Medium school size range, the percentage of students who passed math, reading and both each dropped by 6%. The average math and reading scores, however, stayed the same. 

### Scores by School Type
![new_scores_by_school_type_summary](https://github.com/evanmgoodwin/School-District-Analysis/blob/master/new_scores_by_school_type_summary.png)

As we can see from the new scores by school type summary, the percentage of students at charter schools who passed math and reading each decreased by 4%. The overall passing percentage decreased by 3%. The average scores, however, stayed the same.
