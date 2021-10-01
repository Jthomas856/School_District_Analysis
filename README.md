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

### Scores by Grade

<img width="296" alt="Scores_by_grade" src="https://user-images.githubusercontent.com/89098766/135552361-20d6ad0d-8468-40eb-8ef7-102d626a6df3.png">


