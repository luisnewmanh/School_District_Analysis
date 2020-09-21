# Election Analysis
## Overview of Project
Analyze testing and budgeting data from a City School District to understand school.
### Purpose
The purpose of this analysis is to deliver key indicators for the City School District: 

1. A high-level snapshot of the district's key metrics
2. An overview of the key metrics for each school
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school

Additionally, after evidence of academic dishonesty surfaced from Thomas High School, specifically 9th graders. Repeat the analysis to show its impact.

## Results
### District Summary
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/SnapshotT.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/Snapshot.JPG">
#### Not Considering Thomas High School 9th grade students
### Top 5
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/top5T.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/top5.JPG">
#### Not Considering Thomas High School 9th grade students
### Bottom 5
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/bottom5T.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/bottom5.JPG">
#### Not Considering Thomas High School 9th grade students
### Average math score per grade
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/mathT.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/math.JPG">
#### Not Considering Thomas High School 9th grade students
### Average reading score per grade
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/readingT.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/reading.JPG"> 
#### Not Considering Thomas High School 9th grade students
### School performance based on the budget per student
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/budgetT.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/budget.JPG"> 
#### Not Considering Thomas High School 9th grade students
### School performance based on the school size
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/sizeT.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/size.JPG"> 
#### Not Considering Thomas High School 9th grade students
### School performance based on the type of school
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/typeT.JPG">
#### Considering Thomas High School 9th grade students
<img src="https://github.com/luisnewmanh/School_District_Analysis/blob/master/Resources/type.JPG">
#### Not Considering Thomas High School 9th grade students

## Summary
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

The script to perform the election audit can be used for any other election as long as the provided data set (election_results.csv) has the same format. The sript only open the results file in reading mode assuring that the file will be modified, thus changing the results. One of change to the script that can be done is to analyze the votes per county for each candidate, this can lead to understand the preferences for a particular candidate in a given county. It could be possible to verify if there is a duplicated ballot as an extra layer of security for the election.
