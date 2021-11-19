# School_District_Analysis

## Project Overview
The purpose of this analysis is to uncover and proivide insight on trends based on data from a variety high schools. After discovering evidence of academic dishonestly, we will re-analyze the data after omiting the grades for Thomas High School. We will see how these changes in data affected the results of the analysis.

## Resources
- Data Source: schools_complete.csv and students_complete.csv
- Software: Anaconda, Jupyter Notebook

## Results
#### District Summary:
When test scores for ninth graders at Thomas High school were replaced with NaN, the district summary was significantly affected. All test scores and passing scores dropped.

![district_summary_dropped.PNG](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/district_summary_dropped.PNG)

#### School Summary:
The school summary was not significantly affected when grades from Thomas High School were omitted. Thomas High School remains second in the top performing schools.

When test scores were replaced with NaN instead of being omitted, Thomas High School would fall, and no longer be apart of the top five performing schools.

![school_summary.PNG](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/school_summary.PNG)

![top_5.PNG](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/top_5.PNG)

#### Results after replacing test scores of ninth graders from Thomas High School:
- The [math](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/math_scores.PNG) and [reading](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/reading_scores.PNG) scores by grade were not affected with respect to replacing ninth graders' scores.

- The average scores and passing percentages were not affect school spending.
![scores_by_school_spending.PNG](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/scores_by_school_spending.PNG)

- The average scores and passing percentages were affected by medium sized schools, since Thomas High School is a medium sized school. The passing percencentages for math, reading, and overall dropped 6%. 
![scores_by_school_size.PNG](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/scores_by_school_size.PNG)

- The average scores and passing percentages were affected by school type. Thomas High School is a charter school, therefore passing percentages for math, reading, and overall dropped.
![scores_by_type.PNG](https://github.com/jlynw/School_District_Analysis/blob/main/Resources/scores_by_type.PNG)

## Summary
In conclusion, replacing reading and math scores for ninth grade at Thomas High School greatly affected the district summary. The math and reading scores, and passing percentages all dropped. This is also reflected the in the school summary. Thomas High School would no longer be a part of the top five school when scores were replaced. Scores by grade and scores by spending were not affected since they were not dependent on ninth grade scores. Lastly, scores by school size and school type were affected, since Thomas was a medium sized charter school. 
