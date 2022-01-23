# School_District_Analysis

### Overview of the school district analysis

The purpose of this analysis was to provide detailed information for the performance of high school students on final examinations for reading and math in a given school district. After the discovery of grade tampering, a new analysis was performed to provide a new set of data to better reflect the actual performance of students. 


### Results

- Overall the district summary changes when you alter the data of Thomas High School (THS) as seen in the next two figures below:
  - The newly calculated results are shown below.
  
![distric summary new](Resources/district_summary_new.png)
  
  - The original data, shown below, when compared to that above, there is a small decrease in overall performance in all categories except the total amount of schools and budget.

![distric summary original](Resources/district_summary_orig.png)

- The school summary data was also affected by this altering of data. 
  - In the original data THS had a lower overall passing ercentage, seen below.

![school summary original](Resources/school_summary_orig.png)

  - When the data was altered to remove the 9th grade, shown below, THS increased its overall passing performance, as well as its average reading score, passing math percentage, and reading percentage.

![school summary new](Resources/school_summary_new.png)


- Replacing the ninth graders’ math and reading scores affects THS’s performance relative to the other schools in that It moves from the second ranked highest school to the highest school as seen in the following figures.
  - As you can see in the figure below, THS is ranked first in performance based on the overall passing percentage.

![top 5 new](Resources/top_5_new.png)

  - This is an increase from the original data that included the 9th grade student data as shown below.

![top 5 original](Resources/top_5_orig.png)
 
When replacing the 9th grade scores the following were affected:

  - The math scores by each grade were unaffected other than the 9th grade for THS being replaced with nan, which stands for not a number. 
    - Scores of grades after data being altered:

![math score grade new](Resources/math_score_by_grade_new.png)

  - The original data:

![math score grade original](Resources/math_score_by_grade_orig.png)

  - The reading scores by each grade were also unaffected by the altering of the data with the exception of THS' 9th grade.
    - Original data:

![reading score grade new](Resources/reading_score_by_grade_new.png)

    - Altered data:

![reading score grade original](Resources/reading_score_by_grade_orig.png)
 
  - Scores by school spending 
![score by spending new](Resources/scores_by_spending_new.png)
![score by spending original](Resources/scores_by_spending_orig.png)

  - There were no changes to the scores when looking at the data by school size: 
    - Altered data:

![score by size new](Resources/scores_by_size_new.png)

    - Original data:

![schores by sice original](Resources/scores_by_size_orig.png)

  - When analyzing the data by school type, there is a small overall passing percentage increase to charter schools when the data is altered, as seen below.

![scores by type new](Resources/scores_by_type_new.png)

    - The original data by comparison  is shown below.

![scores by type original](Resources/scores_by_type_orig.png)

### Summary

The updated school district analysis after the reading and math scores for the ninth grade at Thomas High School were replaced with NaNs is quite significant.
