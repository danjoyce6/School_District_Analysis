# School_District_Analysis
Anaconda, Jupyter Notebooks, Pandas, Python
## Overview of the school district analysis
The purpose of this analysis was to remove 9th graders scores from Thomas High School after it was brought to the school boards attention that there was academic dishonesty among the 9th graders.  The School analysis was completed to replace the 9th grade reading and math scores and repeat the school district analysis to give an accurate report on the school district.

## Results
The district summary was effected in the following ways.
 - The total number of students was decreased due to the 9th graders from Thomas High School that were removed from the data.  There were 39170 students and after removing them the district contained a total of 38709 students. 
 -  ![District_Summary_After](https://user-images.githubusercontent.com/88444529/134779655-5a85eac2-97bc-452d-b447-10e56833c5ed.PNG)
 - ![District_Summary_Before](https://user-images.githubusercontent.com/88444529/134779661-d7107be6-181e-4348-b1e4-880a7829345a.PNG)

 - The Average Math Score and Average Reading Score were unaffected by the change in students.
 - The % Passing Math, % Passing Reading, and % Overall Passing all decreased.  The largest decrease was in % Passing Reading that went to 0.3%.
The School Summary was effected in the following ways
![Per_School_Summary_After](https://user-images.githubusercontent.com/88444529/134779670-970edd74-9a39-44ac-aa4c-e3fbd64db0a5.PNG)
![Per_School_summay_Before](https://user-images.githubusercontent.com/88444529/134779671-c8710d93-b466-49c7-9c8a-2bb5019c4a92.PNG)

 - The only things that changed in the School Summary DF were the values for Thomas High School
  - The % Overall Passing decreased by about .3% after accouting for academic dishonesty with the 9th graders
  - The Average Reading Score actually increased after accounting for the academic dishonesty among the 9th graders by .05 points
  - The values for all of the other schools remained constant since none of that data changed
  - By replacing the 9th graders math and reading scores, Thomas High School's performance did not change a lot relative to the other schools.  Thomas High Schools performance was still one of the best in the county and remained second in the top five schools.
  - Math and reading scores by grade
    -  The reading and math scores by grade were effected for Thomas High School but that is all.  All math and reading scores for 9th graders at Thomas High School were replaced with NaN's to account for academic dishonesty.
    -  Scores by school spending
      -  The values for scores by school spending did not change following the removal of 9th graders.
      -  The scores for school spending did not change.
      -  The scores by school size did not change.
      -  the Scores by school type were not affected as well.
## Summary
After removing the 9th graders math and reading scores there were slight changes to some of the values but many remained constant.  The passing percentages all decreased for the district with the largest decrease in the % Passing Reading of 0.3%.  Overall, much of the analysis remained the same from the initial analysis and the same conclusions can be drawn from it.
