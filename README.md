### School_District_Analysis.

In this challenge we used Anconda/Pandas/ Python

### Overview of the school district analysis
This project´s goal is to use Anaconda and Jupyer Notebook to analyze the school district. The information we are examining is derived from two sources: a csv file providing school data and a separate csv file with students information from those schools. 

The school data file includes details about the name, size and budget of the school as well as the type of school (charter or district). The document also contins information on the student´s names, schools, grandes and their results on "Math" and "Reading". In order to discover patterns, examine summaries and sort by overall performance, determine math and reading scores and school spending, we will first load the data from the two csv files and transform them into dataframes.

### How is the district summary affected?
Since the district summary Datafram already analyzes data by overall school statistics, such as schools, total students, and total budget, is not significantly impacted by the changes that result from substituting 9th grade Thoms High School Student Data with NaN. The total differences between the figures for average scores, passing scores and overall passing scores is pretty small. The minor change was a slightly fall in passing math.

#Before
![first District summarry](https://user-images.githubusercontent.com/108194577/180679511-7896f587-a9cc-4c44-a1f1-4507efa2a5be.PNG)

#After
![District summary with new student count](https://user-images.githubusercontent.com/108194577/180679536-9a2d8545-69e8-4c66-9c50-5b2d9963c0c1.PNG)

### How is the school summary affected?
According to the school report, the percentage of students passing math, passing reading, and the overall passicon scores dicrease when we take out the 9th graders. 

#Before
![School Summary 1](https://user-images.githubusercontent.com/108194577/180696727-3b1956f6-795a-4b07-92c8-07563f8b1b9b.PNG)

#After
![School summary 2](https://user-images.githubusercontent.com/108194577/180696760-3c605d83-858d-4736-8bb7-d2cf4a42609f.PNG)



###How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the 9th graders affected the math and reading scores of Thomas High School performance in comparison to the other schools. When we take out the nine graders, Tomas High School Overal passing percentage falls around 60% placing it far lower than before and the the other schools. Without the ninth graders, Thomas no longer appears on the top 5

#Before
![TOP Schools CLASSWORK ](https://user-images.githubusercontent.com/108194577/180697434-bbde2e2a-20a8-4d50-a548-60ded59963a6.PNG)

#After
![TOP SCHOOLS CHALLENGE CORRECT](https://user-images.githubusercontent.com/108194577/180697451-3f83d08f-abd1-4d6e-8b65-b985b29f712e.PNG)

###How does replacing the ninth-grade scores affect the following:
##Math and reading scores by grade
The math and reading scores were affected because we no longer have the information of the 9th graders.  In this case, only Thomas High School was affected

#Math Scores Before 
![Math Score by grade -CLASSWORK](https://user-images.githubusercontent.com/108194577/180697914-d78bed2e-f5e2-4ae4-bf40-288f85e704c6.PNG)

#Math ScoresAfter
![Math Score by grade - CHALLENGE](https://user-images.githubusercontent.com/108194577/180697937-8d8f80a2-5a84-43fe-bd24-70fbb5d4c5da.PNG)

#Reading Scores Before
![Reading scores by grade CLASSWORK](https://user-images.githubusercontent.com/108194577/180698191-c28a900d-15b8-4c2b-80d9-055a98c7f743.PNG)

#Reading Scores After
![Reading scores by grade CHALLENGE](https://user-images.githubusercontent.com/108194577/180698144-cc63304c-4f22-42c2-8610-5b0bcb500c17.PNG)

##Scores by school spending
Since we replaced the overall Thomas High School passing scores in the data freame with data for 10th - 12th graders, taking away the 9th graders didn´t affect the scores by schools spending.

#Before
![scores by school spending CLASSWORK](https://user-images.githubusercontent.com/108194577/180698617-1e7e3846-8122-4b94-8b30-1b88e99a3ec0.PNG)

#After
![scores by school spending CHALLENGE](https://user-images.githubusercontent.com/108194577/180698630-2dd80d7e-8e40-4bc8-be0d-dbb590eb61f9.PNG)

##Scores by school size
The Average passing math, passing reading and overall Passing was a little bit affected with this movement. The new score was decreased without the information of the ninth graders. Passing reading % and the overall passing were more affected.
Only the Thomas High School was affected.

#Before
![Scores by school size CLASSWORK](https://user-images.githubusercontent.com/108194577/180699714-c51f4247-fe19-402f-be25-b7df65c813e1.PNG)

#After
![SCHOOL SIZE CHALLENGE](https://user-images.githubusercontent.com/108194577/180699726-4697675b-0891-42ea-9f80-c0c7aae44ff1.PNG)

##Scores by school type
The new Charter School type was affected.  Passing Math percentage and the Passing Reading percentage decreased.
The district type stayed the same

#Before
![School type CHALLENGE](https://user-images.githubusercontent.com/108194577/180700139-46b1e546-6311-4ba4-a527-772b488d21d4.PNG)

#After
![School type CLASSWORK](https://user-images.githubusercontent.com/108194577/180700152-9a781b41-035d-481f-a003-e7499186ab75.PNG)

##Summary
The Thomas High School´s rank decreased 6 places with converting the 9th graders information with Nan. Bcause of this change total ranking position was down. The only one affected in this movement was the Thomas High School.
Taking away this 9th graders will need to be considered as this is shown to affect the Thomas High School ranking. 
Also, with this movement, we saw that the Charter School Type was the one that was more affected. 
