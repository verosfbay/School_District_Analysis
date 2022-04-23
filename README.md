# School District Analysis 

## Overview 
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Maria asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I’ve replaced the math and reading scores, I repeated the school district analysis that I did previously and wrote up a report to describe how these changes affected the overall analysis. 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- The district summary is affected in that the average math score is now 78.9 instead of 79.0, the percentage passing math is now 74.8 instead of 75, and the overall passing percentage is now 64.9 instead of 65.
- The school summary is affected in that the percentage of students passing math at Thomas High School is now about 66.9% instead of 93.2%. The percentage passing reading is now 69.7% instead of 97.3%. The percentage overall passing is now 65% instead of 91%. 
- Replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools by taking Thomas High School out of the top schools and putting it closer to the bottom schools. The 65% passing is not as bad as some of the other schools that have overall passing percentage in the 50s, but now Thomas High School is not considered a top performing school. 
- Replacing the ninth-grade scores affects the following: 
    - In math_scores_by_grade and reading_scores_by_garde, the math and reading score for Thomas High School are both nan. 
    - In Scores by school spending, the data change did not impact the spending ranges for average math score and average reading score
    - There aren't any differences between the formatted size_summary_df 
    - There are negligeable percentage differences in scores by school type – the % passing reading in Charter schools is now 96.55 instead of 96.59 and the % overall passing in Charter schools is now 90.39 instead of 90.43

## Summary 

There are four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. These are: Thomas High School is no longer one of the top performing schools, the average math score is now 78.9 instead of 79.0, the percentage passing math is now 74.8 instead of 75, and the overall passing percentage is now 64.9 instead of 65.

