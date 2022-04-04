# School_District_Analysis
Using Jupyter Notebook to analyze school district data

Overview


The purpose of this project is to help a data scientist with analyzing data collected from schools in a city district. The data collected is on student funding and standardized test scores. In this analysis, we will be reviewing performance trends and patterns based on the data collected. The goal is to report those trends to the school to board to help with decisions made about the budgets for each school. We will also specifically be reviewing data on 9th graders from Thomas High School, who have been suspected of cheating on their tests.

Results


How is the district summary affected?

When we refactor the code, there are a total of 461 9th graders whose testing scores become null data. Not much of a difference is made, as this is 461 students’ test scores of an over 39,000 student dataset. The 9th graders from Thomas High School make up just over 1% of the entire student population. The result is shown below in both the original and refactored code.

Original code-

Refactored code-

How is the school summary affected?

The school is affected very little when the 9th grade students are not taken into account, similar to how to district was. As we can see from the below results, the test scores all changed by less than 1%.

Original code-

Refactored code-

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The ranking is unaffected when running the refactored code. When the code is rerun, there is an impact made to the math, reading and overall test scores. However, the decrease is not enough to impact the rankings. Thomas High School ranks 2nd both times the code is run, regardless of the null data from the 9th graders.

Original code-

Refactored code-

How does replacing the ninth-grade scores affect the following:

-Math and reading scores by grade
Based on the results displayed, we can see that there is very little impact on the dataframe. The only difference is that the Thomas High School 9th graders are shown as NaN, instead of having an actual value.

Original code-

Refactored code-


-Scores by school spending

-Scores by school size

-Scores by school type

Summary

