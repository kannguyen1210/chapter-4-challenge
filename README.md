# chapter-4-challenge

## Challenge Overview
After completing the school analysis, the school board noticed there were academic dishonesty regarding math grades for ninth grade at Thomas High School. Therefore, in order to uphold the state standards, Maria needs to eliminate the ninth grade scores of Thomas High School and run the analysis again and provide a report on any changes compare to the original analysis. There are total 7 metrics to be ran again

1. Top 5 performing schools based on Overall Passing grade
2. Bottom 5 performing schools based on Overall Passing grade
3. Average math score for each grade level from each school
4. Average reading score for each grade level from each school
5. The scores by school spending per student
6. The scores by school size
7. The scores by school types

## Resources
- Data source: schools_complete.csv, student_complete.csv
- Software/Libraries: Python 3.7.9, Jupyter Notebook, Anaconda, Pandas, Numpy

## Challenge Results
After making the changes regarding Thomas High School ninth grade, below are the updated analysis of the 7 metrics listed above

1. Top 5 performing schools based on Overall Passing grade - **NO CHANGE** - Although the Overall Passing Percentage did change slightly for Thomas High School, it is still not enough to change the rank of top 5 schools and Thomas High School remain in the top 2 schoool.
2. Bottom 5 performing schools based on Overall Passing grade - **NO CHANGE** - Since the bottom 5 school does not include Thomas High School, there are no changes in the ranking in this regard as well
3. Average math score for each grade level from each school - **CHANGED** - Since the 9th grade math scores from Thomas High School is now removed from the data Frame, the value for the 9th grade column for Thomas High School is now NaN.
4. Average reading score for each grade level from each school - **CHANGED** - Since the 9th grade reading scores from Thomas High School is now removed from the data Frame, the value for the 9th grade column for Thomas High School is now NaN.
5. The scores by school spending per student - **NO CHANGE** - again we notice a small change for the scores in the 630-644 Dollars per student range since we modify Thomas High School scores for 9th grader, however, the change was very minor and the rounded report for this metric remains the same.
6. The scores by school size - **NO CHANGE** - although there are small changes in the Medium size bucket that we can see when before we format the table and round the averages to 1 decimal place or 0 decimal place, the final table remain unchanged when we remove the 9th grade scores
7. The scores by school types - **NO CHANGE** - in the Charter bucket, which is the school type of Thomas High School, we also see small changes before rounding up the numbers but overall, once we format the metrics, we do not see any changes.

## Challenge Summary
Overall, by removing the 9th graders score of Thomas High School from the data frame, we see a few changes where as:
- When looking at average math scores by grades and by school, we are no longer seeing the scores for 9th grade at Thomas High School
- When looking at average reading scores by grades and by school, we are no longer seeing the scores for 9th grade at Thomas High School
- In other metrics, we see slightly different averages number when we group the schools into buckets for the school summary, school size, school spending, school types metrics but once we round up the number, these changes are not significant and do not affect the final analysis in any significant way.
- In the District summary, we can see that all the 9th graders at Thomas High School have their score as NaN as we removed it.