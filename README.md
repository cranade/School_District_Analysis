# School District Analysis

## Overview

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for ninth graders of Thomas High School ,a Charter School,  appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I have replaced the math and reading scores, Maria would like me to repeat the school district analysis that I did in this module and write up a report to describe how these changes affected the overall analysis.

This report documents this work of my team and me.

## Findings

My team and I followed the advice of Maria and modified the code given by her to use Python, Jupyter Notebook, Panda and Numpy and completed the analysis. The average reading and average math results for the original data were, respectively, 81.9 and 78.

As per the advice of Maria, because of the suspected anomalies, We removed the 9th grade results for Thomas High School and replaced them with NaN. tables using Jupyter Notebook. for Thomas High School. The following are the findings.

* Average reading scores for reading remained the same and it was 81.9. In contrast, the average math score  and math which was 78 declined significantly to 73.9. The district summary table is as follows after the scheme of NaN was introduced.

![Chart](https://i.imgur.com/G8GNhn4.png)

* After considering only 10th, 11th and 12th grade reading and math scores, now Thomas High School is in top 5 schools as shown in the table below. In fact the top 5 schools are all Charter Schools which are performing better than the District Schools.

![Chart](https://i.imgur.com/rrqD74x.png)

* The summary statistics comparing the District and Charter schools further supports this fact (see table below). Average Math Schore in Charter Schools is 83.5 (B) against 76.9 (C) in the District Schools. Percentage of students passing Math is 94% in Charter Schools versus 87% passing Math. Same is the case with English. The overall passing percentage is 90% in Charter Schools while in District Schools it is only 54%.

![Chart](https://i.imgur.com/qw6tXzQ.png)

* Summary of Math and Reading Scores for all grades and schools is given below in the two tables.

![Chart](https://i.imgur.com/YAYv1Y8.png)

![Chart](https://i.imgur.com/GOEuMUc.png)

* The following table presents the picture by school size. Charter schools are either small of medium size and have done consistently better than the District Schools which are Large. This is an important finding for allocating budget.

![Chart](https://i.imgur.com/35wcwcc.png)

* The summary by school type further confirms that the Charters schools have performed far better than the District School.

![Chart](https://i.imgur.com/simbj2S.png)

### summary

1. After making the changes in the 9th grade, the overall average grade for Thomas School improved for Reading and Math Scores.

2. Looking at the School sizes middle and smaller size schools have performed far better than the big size school.

3. Looking at the type of schools, Charter Schools have performed far better than the District schools

4. School Board should carefully allocate more budget to Charter Schools, if possible divide District Schools into Middle size or even small size schools to improve the student performance.
