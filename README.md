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

Comparing the two chart above the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.  Excluding the Thomas High Schools 9th grade students Reading and Math scores slightly affected by tenths of average scores in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading and % Overall Passing. 

**How is the school summary affected?**

School Summaries - With 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126941940-e1cb7dfa-7e09-44a8-bbb4-f876b44979b7.png)

School Summaries - Without 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126942110-bd06b351-4b04-4f6c-9ed5-3d4b698a697b.png)

In the charts above, the difference when excluding the Thomas High Schools 9th grade students Reading and Math scores is slight.  In this charts, the Thomas High School scores without the 9th, slight decrease, for example in % Overall Passing from 90.948012 to 90.630324.  Comparing Thomas High School % Overall Passing placement does not change much either.  They are still the within the 90 percentile passing.

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
Replacing ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools does not affect their % Overall Passing mark.  They are still within within the 90 percentile passing mark.


**How does replacing the ninth-grade scores affect the following:**

a) Math and reading scores by grade : Excluding the ninth graders’ math and reading scores from  Thomas High School’s only change slightly and Thomas High School still holding the 2nd Top Five Schools in the district.

![image](https://user-images.githubusercontent.com/86085614/126942266-8e081975-fa01-406f-9109-5ffa10baed79.png)


b) Scores by school spending : Excluding the ninth graders’ math and reading scores from  Thomas High School’s affected their spending per student from $638.00 to $888.53.

Spendings - Without 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126942739-9487df35-37b0-4009-9a8a-dfca59336045.png)

Spendings - With 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126942665-6ef319ad-d031-455b-9120-b1b6fa078de8.png)

c) Scores by school size : The scores by school size is also slightly affected by excluding the ninth graders’ math and reading scores from  Thomas High School

Scores by school size - With 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126943159-7973504c-4e0c-4b9f-b8f3-c355005d9b7a.png)


Scores by school size - Without 9th grade student Math and Reading scores from Thomas High Schools
![image](https://user-images.githubusercontent.com/86085614/126943254-cb0a1679-1737-4ba3-aa70-cd239d6a2e44.png)


d) Scores by school type :  The scores by school type size is also slightly affected by excluding the ninth graders’ math and reading scores from  Thomas High School.

Scores by school type - With 9th grade student Math and Reading scores from Thomas High Schools

![image](https://user-images.githubusercontent.com/86085614/126943408-f754e00e-6b7a-462b-9853-8a62144120bf.png)

Scores by school type - Without 9th grade student Math and Reading scores from Thomas High Schools

![image](https://user-images.githubusercontent.com/86085614/126943328-bd2d657b-e3f0-42f5-bcde-77a78f0c8724.png)


**Summary**: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

The four changes are reflected in the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks and the funding for each student.  The average markings were slight affected but we can see the difference in funding for each students which is ~ approximately $200.  Thomas High School 2nd stop as the top school does not change at all.
