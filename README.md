# Scool_District_Analysis
intro to jupyter/pandas

#School District Analysis Overview
In this analysis, we are helping Maria, who works for a city school district. She had been given the task to prepare data so she can sort through it to report and present any trends and patterns to help determine funding. This data will include standardized testing scores and funding for multiple high schools. We helped her organize the data to compare the schools by test subject, scores, grades, schools, and funding itself to give the school board. 
##Results of Analysis
•	How is the district summary affected?
o	The school district is affected because the PyCitySchools_Challenge.ipynb’s code shows the school district as a whole. This happens because the code is telling Jupyter to get the individual schools and add them together to make up the district. Making it look like the following picture: 
![School_Analysis_1 png](https://user-images.githubusercontent.com/88864493/134820575-add5ee68-a9b0-4b0e-bf49-1e5b4d3064d8.jpg)

•	How is the school summary affected?
o	When running the school summary in the PyCitySchool.ipynb (first image), you have to specify a number in parentheses part of “per_school_summary_df.head()” to get each of the individual schools listed or it sets to the top 5. But in the PyCitySchools_Challenge (second image), it is written into the code to display all 15 schools individually without saying a specific number. 
![School_Analysis_2 png](https://user-images.githubusercontent.com/88864493/134820592-1e2122bd-4ca5-4091-969b-12e796094495.jpg)
![School_Analysis_3 png](https://user-images.githubusercontent.com/88864493/134820603-aeb170a0-c842-4762-904f-40d3b05b1048.jpg)

•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
o	After comparing both files, the scores for Thomas High School look the same in both files so I was not able to determine if there was a change in ranking between the files after replacing them in PyCitySchools_Challenge.ipynb.  Images are from the PyCitySchools.ipynb.
![withoutNAN_math png](https://user-images.githubusercontent.com/88864493/134820643-38adb5b9-3733-4a15-9c00-7dbea4e3baf1.jpg)
![withoutNAN_reading png](https://user-images.githubusercontent.com/88864493/134820645-e7bc78be-0db9-4deb-bf6d-9290b410b402.jpg)

•	How does replacing the ninth-grade scores affect the following:

1.	Math and reading scores by grade
o	Replacing the THS 9th grade reading and math scores with NaNs make both averages drop. The average for both math and reading dropped 5.6 with replacements. 

2.	Scores by school spending
o	When going by spending range, the different between the two percentages drops 0.079423 with the 9th grade scores. 

3.	Scores by school size
o	The overall percentage for school size drops 0.317688 when replacing 9th grade scores. 

4.	Scores by school type
o	While the numbers by school type didn’t reflect changed between the two scoore types.

##Summary of Analysis: 
To summarize, math and reading scores lowered when adding NaN to THS 9th graders. This trickled down into other areas as well. When we replaced 9th grade scores, THS’s overall scores dropped. Another change worth noting would be that the over all score for the 9th graded dropped for all schools. The spending range per student for over all percentage dropped however this did not cause them to drop out of the $630-$644 bin per student. The drops in numbers when adding the NaN to Thomas High School’s 9th graders we not significant enough to see changed in funding.  
