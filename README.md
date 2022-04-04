# School_District_Analysis
Using Jupyter Notebook to analyze school district data

Overview


The purpose of this project is to help a data scientist with analyzing data collected from schools in a city district. The data collected is on student funding and standardized test scores. In this analysis, we will be reviewing performance trends and patterns based on the data collected. The goal is to report those trends to the school to board to help with decisions made about the budgets for each school. We will also specifically be reviewing data on 9th graders from Thomas High School, who have been suspected of cheating on their tests.

Results

How is the district summary affected?

When we refactor the code, there are a total of 461 9th graders whose testing scores become null data. Not much of a difference is made, as this is 461 students’ test scores of an over 39,000 student dataset. The 9th graders from Thomas High School make up just over 1% of the entire student population. The result is shown below in both the original and refactored code.

Original code-
<img width="923" alt="original 1" src="https://user-images.githubusercontent.com/100978922/161460135-98274911-48cb-48c2-9420-d5e432be9c58.png">


Refactored code-
<img width="926" alt="refactored 1" src="https://user-images.githubusercontent.com/100978922/161460140-c270cce3-690c-476b-9365-4d496b49e6c9.png">


How is the school summary affected?

The school is affected very little when the 9th grade students are not taken into account, similar to how to district was. The test scores all changed by less than 1%.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The ranking is unaffected when running the refactored code. When the code is rerun, there is an impact made to the math, reading and overall test scores. However, the decrease is not enough to impact the rankings. Thomas High School ranks 2nd both times the code is run, regardless of the null data from the 9th graders.

Original code-
<img width="971" alt="original 2" src="https://user-images.githubusercontent.com/100978922/161460364-f7e9efac-7e74-4ddb-b14c-3ce5ccd4ccfc.png">

Refactored code-
<img width="978" alt="refactored 2" src="https://user-images.githubusercontent.com/100978922/161460377-10efc419-9581-4b91-86e0-75eec1315973.png">


How does replacing the ninth-grade scores affect the following:

-Math and reading scores by grade
Based on the results displayed, we can see that there is very little impact on the dataframe. The only difference is that the Thomas High School 9th graders are shown as NaN, instead of having an actual value.

-Scores by school spending
There is a slight change in the scores based on spending. In the $630-$644 spending range per student, we see a slight decrease. This is to be expected, as this is the group the Thomas High School is part of.

-Scores by school size
There scores for the medium size schools have changed slightly, less than about 1%. It is expected that this value would change as Thomas High School is considered to be a medium sized school.

-Scores by school type
There are changes made to the charter school section of the dataset, as Thomas High School is categorized as a charter school. The change is once again less than 1%. The other school types have been unaffected.

Summary

School Summary- Thomas High School test scores are affected by less than 1% when removing the 9th graders test scores.
School Ranking- there were no changes made to the school ranking when removing the Thomas High School 9th graders.
Scores by Size- the only change made was for the medium size schools, and the percentage change is less than 1%.
Scores by School Type- the only change made was for Charter Schools, and the percentage change is less than 1%.

