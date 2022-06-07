# School_District_Analysis
School Analysis
Overview of the school district analysis:
The purpose of the project analyzes the data of the School District, to get more insights and provide transparent result of the school performance.
Results: 
Academic dishonesty by ninth grade students at Thomas High School lead to an analysis being conducted twice. The first analysis included the full data of students while in the second analysis, Thomas High school ninth grade scores were replaced by NAN. 
Below is the data frame representing is the summary representing the district after replacing the ninth graders' scores with NaN.
![image](https://user-images.githubusercontent.com/105121697/172470811-fd892d95-9301-4ede-9ebe-b933baa8c633.png)
	
•	How is the district summary affected?
The average math and reading scores went down from 78.98 to 78.00 and 83.41 to 59.85 respectively. It has a negative impact on the overall district summary. The changes were minimal so the impact to the overall district summary is minimal.

•	How is the school summary affected?
The school summary was impacted to a large extent after removing ninth graders scores, the average math and reading scores went from 83.41 to 59.85 and 83.84 to 60.24, respectively. The overall passing % was not affected but the %Passing Math and reading scored for Thomas High School went from 93.27 to 66.9 and 93.31 to 69.66 respectively.

•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
o	Thomas High School was among the top performing schools, when the ninth-grade math and reading scores was not removed. However, after removing the average scores in math and reading from 83.41 to 59.84 and 83.84 to 60.24 respectively. Thomas High School was no more included on the top five schools on the list.
o	The overall passing percentage for the district came to 64.9%.
o	The overall passing percentage for Thomas High School came down to 65%.

•	How does replacing the ninth-grade scores affect the following: Replacing the ninth-grade scores effects are as follows.
o	Math and reading scores by grade
Ninth graders received score “0” instead of 83.6. But the other grades were not impacted, the10th, 11th & 12th in Thomas High School maintained their scores.
o	Score by school spending: The scores by school spending was impacted. See table below
![image](https://user-images.githubusercontent.com/105121697/172473403-212a1d13-dee7-41c2-bf33-c37abfd4be09.png)
	
Screen shot of score by school spending after replacing the ninth grade Math and Reading score.
![image](https://user-images.githubusercontent.com/105121697/172471732-112bc45d-9044-4d32-a0da-b9dcb444fdf3.png)

o	Scores by school size
The scores were impacted slightly.Thomas High School size bin Medium (1000-2000). 
![image](https://user-images.githubusercontent.com/105121697/172474028-b8d11a90-aefd-4811-9196-2b3b868cc0c1.png)
	
o	Scores by School Type
	School Type	Average Math	Average Reading	%Passing _Reading
Before	Charter	83.5	83.9	97
After	Charter	80.5	80.9	93
![image](https://user-images.githubusercontent.com/105121697/172474274-bcf32c73-74c2-40c2-b331-903e6a2f612d.png)

Screen shot after:![image](https://user-images.githubusercontent.com/105121697/172472260-2e9b107a-fb5e-4dc4-91c8-e1c63ec1f0e5.png)

Scores by school spending, scores by school size and scores by school type were all impacted due to the removal of ninth grade math and reading score.

•	Summary
Replacing the ninth graders' scores with NaN made Thomas High School's overall passing percentages and average scores to drop. The entire district average in math and reading as well as the entire passing percentage dropped.
Scores by school spending, scores by school size and scores by school type were all impacted due to the removal of ninth grade math and reading score.
Thomas High School lost the placement amongst the five top schools in the district. However, after some updates Thomas High School regained its high average scores and retained its position as amongst the top five school in the district.



	Scores by school spending

	Scores by school size
	Scores by school type
2.	Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District. To view the full script, please open PyCitySchools_Challenge.ipynb in Jupyter Notebook.

Replacing the ninth graders' scores with NaN made Thomas High School's overall passing percentages and average scores to drop. The entire district average in math and reading as well as the entire passing percentage dropped.
Thomas High School lost the placement amongst the five top schools in the district. However after some updates Thomas High School regained its high average scores and retained its position as amongst the top five school in the District
