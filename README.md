# School_District_Analysis.
Overview of the school district analysis: Explain the purpose of this analysis. The overview of the school district analysis is to provide all students by name and, student ids,gender,reading and math scores. Refactoring the codes to add in schools complete. This is done by creating different DataFrames and refactoring the nans. Using the loc method helps retrieve the student count from Thomas High school.

# Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected? The district summary is affected by providing data from students name and students complete. This data shows reading and math scores over or equal to 70.

How is the school summary affected? With the data you can see all schools by School ID, Name, type size and budget. The school data is loaded from schools complete.csv. It is affected by school by making columns and showing total schools.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth grades show only the ninth passed and failed. The original charts show the students from all grades. It gives 461 rows and 7 columns of all data.

How does replacing the ninth-grade scores affect the following: Replacing the ninth grades scores changes the table to show only 9th grade scores from the nan.

Math and reading scores by grade: This shows all data of math and reading above 70 in math and reading grouped by school. The total students are 39.170, to review of all data.

Scores by school spending: The data shows the school budget and the percentage per student.

Scores by school size: The data shows the schools size and budget per student and percentage passed by school.

Scores by school type: The data provides the school type school type, budget, score, passing math, reading and overall passing.

# Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

There were several changes be replacing the school district analysis of the reading and math score. 
1. The data frames were changed from student count and school count.
2. There were columns created with total schools, total students, total budget, Average reading score, passing math, passing reading and overall passing.
3. We had to import as NumPy and pd.
4. The district summary, using the count method to provide all columns.
