# School_District_Analysis-

## Deliverable 1: Replace Ninth-Grade Reading and Math Scores (50 points)

Check PyCitySchools_Challenge.ipynb file

## Deliverable 2: Repeat the School District Analysis (25 points)

Check PyCitySchools_Challenge.ipynb file

## Deliverable 3: A Written Report for the School District Analysis (25 points)

The analysis should contain the following:

### Overview of the school district analysis: Explain the purpose of this analysis.

**Purpose**: The purpose of this analysis is to find the evidence of academic dishonesty in the Student and School data given to Maria. The data relevant to ninth graders in Thomas High School, especially math and reading scores seems to be distorted. To find the evidence, Maria stated the requirements 1) replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact 2) repeat the school district analysis from Module 4 project 3) state any changes.

**Results**: Using bulleted lists and images of DataFrames as support, address the following questions.

**How is the district summary affected?**

School District Summary Chart - With 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126941517-ccccc343-9197-4f0a-8dd6-bf7e51f9988c.png)

School District Summary Chart - Without 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126941679-569da48b-6819-42ba-9cb6-158f9770da88.png)

Comparing the two chart above the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.  Excluding the Thomas High Schools 9th grade students Reading and Math scores slightly affected by tenths of average scores in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading and % Overall Passing.  The overall slight decrease in averages do not change but it will affect the following summaries.


**How is the school summary affected?**

School Summaries with or without Thomas High School



In the charts above, the difference when excluding the Thomas High Schools 9th grade students Reading and Math scores is slight.  In this charts, the Thomas High School scores without the 9th, slight decrease, for example in % Overall Passing from 90.948012 to 90.630324.  Comparing Thomas High School % Overall Passing placement does not change much either.  They are still the within the 90 percentile passing.

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
Replacing ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools does not affect their % Overall Passing mark.  They are still within within the 90 percentile passing mark.


**How does replacing the ninth-grade scores affect the following:**

a) Math and reading scores by grade : Excluding the ninth graders’ math and reading scores from  Thomas High School’s only change slightly and Thomas High School still holding the 2nd Top Five Schools in the district.

b) Scores by school spending : Excluding the ninth graders’ math and reading scores from  Thomas High School’s affected their spending per student from $638.00 to $888.53.

c) Scores by school size : The scores by school size is also slightly affected by excluding the ninth graders’ math and reading scores from  Thomas High School

d) Scores by school type :  The scores by school type size is also slightly affected by excluding the ninth graders’ math and reading scores from  Thomas High School.

**Summary**: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

The four changes are reflected in the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks and the funding for each student.  The average markings were slight affected but we can see the difference in funding for each students which is ~ approximately $200.  Thomas High School 2nd stop as the top school does not change at all.
