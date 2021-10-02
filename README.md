# School_District_Analysis
## Overview
A school board has found evidence of academic dishonesty at one of their high Schools. The students_complete.csv file provided shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to us for help. We have been asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we’ve replaced the math and reading scores, we need to repeat a previously completed school district analysis to determine how these changes affected the overall analysis.

The final analysis will contain the following metrics:
- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

## Resources
Data Source: students_complete.csv
Software: Python 3.8.8, Jupyter Notebook

## Results

The 9th grade math and reading scores were replaced with Nans, then the metrics for Thomas High School were recaluclated to only account for the math and reading scores for grades 10-12. The average grades and passing percentages for Thomas High School were based of scores from grades 10-12, and this data was used when performing the new analysis for the school district.

### District Summary

<img width="970" alt="District_Summary" src="https://user-images.githubusercontent.com/89098766/135550271-e10a5de2-802c-4b1a-ab26-926fea10b34a.png">

Dropping the math and reading scores for 9th graders at Thomas High School had a minimal impact on the overall district summary. 
- The average math score dropped from 79 to 78.9.
- The average reading score remained the same at 81.9.
- The percent passing math dropped from 75% to 74.8%.
- The percent passing reading dropped from 86% to 85.7%.
- The overall percent passing dropped from 65% to 64.9%.

### School Summary

<img width="1011" alt="Per_School_Summary" src="https://user-images.githubusercontent.com/89098766/135550774-663df6d8-38ee-4bfb-9b4e-1a0f9d6eb521.png">

The school summary remained largely unchanged except for the data for Thomas High School.
- The average math score dropped less than .1% from 83.41 to 83.35.
- The average reading score increased by 0.05 to 83.89.
- The percent passing math dropped from 93.27% to 93.18%
- The percent passing reading dropped from 97.3% to 97.01%.
- The overall percent passing dropped from 90.94% to 90.63%.

### Thomas High School Vs. Other Schools

<img width="1014" alt="Top_Schools" src="https://user-images.githubusercontent.com/89098766/135551906-c2d4fe9f-f2d7-42ee-8ff8-c6f341decf8f.png">

Thomas High School still remained in the top performing schools after dropping the 9th grade math and reading scores.

## Summary

The updated school district analysis was affected in the following ways:

<img width="315" alt="Math_scores by grade" src="https://user-images.githubusercontent.com/89098766/135722935-fd7db325-d054-4d42-9f9a-7533538df3b8.png">

- The only impact to the scores by grade were that 9th grade at Thomas High School showed a NAN for math and reading. All other schools and grades remained unchanged.

<img width="864" alt="Scores_by_spending" src="https://user-images.githubusercontent.com/89098766/135722969-088091cc-e861-45aa-b3f9-9948b7c05798.png">

- Scores by spending increased for the $585-629 and $630-644 categories.

<img width="792" alt="scores_by_school_size" src="https://user-images.githubusercontent.com/89098766/135723162-83a905cc-7ae3-4c67-878b-113fec599970.png">

- Scores by school size remained unchanged.

<img width="726" alt="scores_by_school_type" src="https://user-images.githubusercontent.com/89098766/135723192-2eacdb6f-6ddf-4a8f-812f-2cbca1908f02.png">

- Scores by school type remained unchaged.


 




