# School_District_Analysis

## Purpose:

### Background
* A chief data scientist for the city school district analyzs a variety of information and needs to prepare all standardized test data for analysis, to report and to present so she can provide insights about performance trends and patterns. These trends and patterns will help with decisions about how to teach kids and more.

### Goal
* Help the chief data scientist analyze...
  * data on student funding
  * students' standardized test scores (using every students' math/reading scores and other various information) 
* Aggrate the data and showcase trends in school performance.

### Resources
* Data Sources: students_complete .csv/school_complete .csv files
* Client Requirements from School Board
* Software: Python 3.8.8, Anaconda, Jupyter Lab, git 2.32.0
* Output Files: PyCitySchools.ipynb & PyCitySchools_Challenge.ipynb (with NaN)

## Results

### How is the district summary affected?
- Average Math Scores: went from 79 to 78.9 due to taking out Thomas High School Ninth Grader scores.
- Average Reading Scores did not change.
- % Passing Math moved from 75% to 74.8%.
- % Passing Reading moved from 86% to 85.7%.
- % Overall Passing moved from 65% to 64.9%.

### With Thomas Hi. 9th Grader Scores
<img width="779" alt="Screen Shot 2021-07-19 at 9 05 41 PM" src="https://user-images.githubusercontent.com/85847344/126260538-65be1f3e-55ba-4216-ae38-bce585759b89.png">

### Without Thomas Hi. 9th Grader Scores
<img width="793" alt="Screen Shot 2021-07-19 at 9 06 23 PM" src="https://user-images.githubusercontent.com/85847344/126260552-7e829c82-d9cf-45c7-af74-2e0f40a0b67a.png">

### How is the school summary affected?
* When taking away the 9th graders at Thomas...
83.848930	83.418349	

 * The Average Math at Thomas decreased from 83.42 to 83.35.
 * Average Reading at Thomas increased from 83.84 to 83.89.
 * Average Percent Passing Math at Thomas decreased from 93.3% to 66.9%.
 * Percent Passing Reading at Thomas decreaseed from 97.3% to 69.7%.
 * Average Percent Overall passing both Math and Reading decreased from 90.9% to 65.1%.
 
<img width="482" alt="Screen Shot 2021-07-19 at 9 52 41 PM" src="https://user-images.githubusercontent.com/85847344/126263831-f4f80075-c704-4eba-9c6c-49af458b7d19.png">

<img width="810" alt="Screen Shot 2021-07-19 at 9 29 03 PM" src="https://user-images.githubusercontent.com/85847344/126263818-9f23e240-5e13-47f3-9267-c8fee90d1d36.png">

<img width="476" alt="Screen Shot 2021-07-19 at 9 30 07 PM" src="https://user-images.githubusercontent.com/85847344/126263820-8fc569c8-f657-4763-9460-ca89576e7173.png">

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

* Thomas High is no longer in the top 10 after adjusting 9th grades scores with NaNs.

* How does replacing the ninth-grade scores affect the following:
 * Math and reading scores by grade
    - Thomas High School's math scores were removed from the 9th grade and all other scores remained the same.
 * Scores by school spending
    - With removing the 9th grade scores, the overall passing percentage decreased from 62.9% to 56.4%.
 * Scores by school size
    - Thomas High School is a medium sized school. 
    - Didn't find much after adding the NaNs.
 * Scores by school type
    - For the Charter, therefore, the changes were as follows:
        *Average Math scores decreased from 83.47 to 83.46.
        *Average Reading scores barely increased: 83.89 compared to 83.9.
        *% Passing Math declined from 93.6% to 90.3%.
        *% Passing Reading ddecreased from 96.6% to 93.1%.
        *% Overall Passing decreased from 90.4% to 87.2%.

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

