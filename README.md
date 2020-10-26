# PyCity Schools District Analysis

## Project Overview
Maria, the chief data analyst for the PyCity School District has tasked us with analyzing the school and student performance data for the 15 schools in the district.  After completing the initial analysis, the team noticed some irregularities in the 9th grade class of Thomas High School.  As a result of these irregularities, it was requested that we analyze the district results excluding the 9th grade class of Thomas High School.

## Resources
- Data Sources: [students_complete.csv](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/students_complete.csv)
               [schools_complete.csv](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/schools_complete.csv)
- Software: Python 3.8.3, Jupyter Notebooks, Anaconda 3 

## Results
### District Summary
![Initial_District_summary](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/Initial_District_summary.PNG)

![Post_District_summary](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/Post_District_summary.PNG)

The district scores were not effected greatly by the drop of the Thomas High School 9th grade class.  As you can see there are only decimal point differences between the initial analysis (top) and the modified analysis (bottom).

### School Summary
![Initial_school_summary](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/Initial_school_summary.PNG)

![Post_school_summary](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/Post_school_Summary.PNG)

After the removal of the THS 9th grade class, the school still places 2nd amongst all schools in overall passing percentage.  There is a fractional change in the school summary percentages, but the overall ranking is unchanged.

### Math and Reading Scores by Grade
#### Initial Results
![pre-math-scores1](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/pre-math-scores1.PNG)

![pre-reading-scoresbygrade](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/pre-reading-scoresbygrade.PNG)
#### Results after Removal
![post-math-scores-bygrade](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/post-math-scores-bygrade.PNG)

![post-reading-scores-bygrade](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/post-reading-scores-bygrade.PNG)

Removing the 9th grade THS scores only effected the 9th grade scores for reading and math.  Each score dropped by less than a perecentage point after the change.

### Scores by School Spending
![pre-score-by-schoolspend](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/pre-score-by-schoolspend.PNG)

![post-scores-by-schoolspend](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/post-scores-by-schoolspend.PNG)

The removal of the 9th grade class at THS does not change the schools budget or the spend per student.  Therefore, it has a very minimal effect on the performance of schools based on dollar per student spend.

### Scores by School Size
![pres-score-by-schoolsize](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/pres-score-by-schoolsize.PNG)

![post-score-by-schoolsize](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/post-score-by-schoolsize.PNG)

Because the removal of the 461 9th graders at THS does not move the school into a different bracket, the performance of schools based on size is unchanged.

### Scores by School Type
![pres-score-by-schooltype](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/pres-score-by-schooltype.PNG)

![post-score-by-schooltype](https://github.com/agregorash/School_District_Analysis/blob/main/Resources/post-score-by-schooltype.PNG)

Again, the removal of the THS 9th grade class has a very minimal change on the data for math and reading scores/ passing percentages between Charters and Districts.  Districts still underperform Charters at a similar rate even with the removal of the THS 9th grade scores.

## Summary

The removal of the Thomas High School 9th grade class results did not have an overwhelming effect on the overall data set, however here are the most significant differences:
1. The average math score at THS decreased by .07 points
2. The average reading score at THS decreased by .15 points
3. The overall passing percentage at THS decreased by .31 points
4. 9th grade district scores for math decreased by .19 points, while reading decreased by only .076 points 



