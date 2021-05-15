# Student Performance in Exams

## Dataset:
This is a dataset on Kaggle, link is here: https://www.kaggle.com/spscientist/students-performance-in-exams <br>
 
This dataset is about student performance, where it lists the students' grades in 3 subjects, as well as information about the student, like their gender, ethnicity and whether they had supplementary courses 

The dataset contains 8 columns:
* `gender`: a categorical variable (male or female)
* `race/ethnicity`: a categorical variable, taking one of five values: `group A, group B...group E` 
* `parental level of education`: categorical variable, which can be `high school, college, bachelor's, master's or associate degress`
* `lunch`: a categorical variable, which tells the type of lunch the students have. This reflects their financial status. It can be `standard` or `free\reduced`
* `test preparation course`: indicates whether a student completed such course. The values can be either `completed` or `none`
* The rest of the columns are numeric, indicating the studen't's score, out of 100, in `math`, `reading` and `writing`

The dataset has **1000 records**

## Summary of findings:
* Both genders display nearly similar performance
* Racial group E is the best performing group, whereas racial group B is the worst performing group
* Students that completed a preparation course tend to perform better
* Students with standard lunch meals tend to perform better than students with reduced lunch
* Students scores tend to improve with higher educational levels from their parents

I wanted to investigate further, why racial groups demonstrated different test scores, in order to see if it's inherent factors, or because it happens that some racial groups have favorable collections of the previous factors. The relations I found suggest it is the latter case, where, racial groups differ in: 
* Parent's level of education
* Whether or not students have completed a preparatory course
* Whether or not students enjoy a standard meal or a reduced meal

And the variation is consistent with the racial group's performance as well as the relation between each factor and the test score.

That is, the reason why different racial groups have different scores can be due to other factors rather than race itself. Therefore I suggest that further investigation is required, and facilities be provided for those in need, in order to offer equal opportunities to students of different racial groups.

## Key Insights for Presentation
In the presentation, I focused on
* Factors that affect student performance
* An attempt to explain why different racial groups exhibit different scores

I didn't include the univariate analysis of each feature, or exploratory attempts that were dead ends.