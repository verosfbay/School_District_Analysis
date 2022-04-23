# School District Analysis 

## Overview 
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Maria asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I’ve replaced the math and reading scores, I repeated the school district analysis that I did previously and wrote up a report to describe how these changes affected the overall analysis. 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- The district summary is affected in that the average math score is now 78.9 instead of 79.0, the percentage passing math is now 74.8 instead of 75, and the overall passing percentage is now 64.9 instead of 65.
<img width="1116" alt="Screen Shot 2022-04-23 at 11 50 30 AM" src="https://user-images.githubusercontent.com/95447175/164941618-3e72f1bc-6894-40eb-8a7f-bf4b87ca9dd4.png">

- The school summary is affected in that the percentage of students passing math at Thomas High School is now about 66.9% instead of 93.2%. The percentage passing reading is now 69.7% instead of 97.3%. The percentage overall passing is now 65% instead of 91%. 
<img width="1174" alt="Screen Shot 2022-04-23 at 11 51 07 AM" src="https://user-images.githubusercontent.com/95447175/164941831-62197602-e23a-4d5b-87fd-62009ea7b096.png">

- Replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools by taking Thomas High School out of the top schools and putting it closer to the bottom schools. The 65% passing is not as bad as some of the other schools that have overall passing percentage in the 50s, but now Thomas High School is not considered a top performing school. 
<img width="1263" alt="Screen Shot 2022-04-23 at 11 51 47 AM" src="https://user-images.githubusercontent.com/95447175/164942098-3ab0375e-ff4f-4a81-a001-80e6bfe2a9fc.png">

<img width="1290" alt="Screen Shot 2022-04-23 at 11 52 27 AM" src="https://user-images.githubusercontent.com/95447175/164942366-c824789a-f422-448f-9750-65cf46ae73e2.png">

- Replacing the ninth-grade scores affects the following: 
    - In math_scores_by_grade and reading_scores_by_grade, the math and reading score for Thomas High School are both nan. 
<img width="514" alt="Screen Shot 2022-04-23 at 11 53 19 AM" src="https://user-images.githubusercontent.com/95447175/164942544-aada3adb-cf9d-4322-a232-4c1b5a091e36.png">
<img width="518" alt="Screen Shot 2022-04-23 at 11 54 06 AM" src="https://user-images.githubusercontent.com/95447175/164942563-1af84cd1-fcac-4bfc-bb92-c8eda150739b.png">

    - In Scores by school spending, the data change did not impact the spending ranges for average math score and average reading score
 <img width="890" alt="Screen Shot 2022-04-23 at 11 54 48 AM" src="https://user-images.githubusercontent.com/95447175/164942583-74cba024-ea9f-463e-90bc-2818826b6dab.png">

    - There aren't any differences between the formatted size_summary_df 
 <img width="886" alt="Screen Shot 2022-04-23 at 11 55 18 AM" src="https://user-images.githubusercontent.com/95447175/164942593-d00806b3-6d5b-432b-be8b-a50290b13592.png">
    
    - There are negligeable percentage differences in scores by school type – the % passing reading in Charter schools is now 96.55 instead of 96.59 and the % overall passing in Charter schools is now 90.39 instead of 90.43
<img width="862" alt="Screen Shot 2022-04-23 at 11 55 38 AM" src="https://user-images.githubusercontent.com/95447175/164942601-cec99819-eae4-47b3-920c-7cd6db7154e5.png">

## Summary 

There are four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. These are: Thomas High School is no longer one of the top performing schools, the average math score is now 78.9 instead of 79.0, the percentage passing math is now 74.8 instead of 75, and the overall passing percentage is now 64.9 instead of 65.

