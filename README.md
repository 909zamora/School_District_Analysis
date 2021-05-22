# School_District_Analysis

##Project Overview

In this challenge, we were tasked with calculating the passing math & reading grades of students both in charter & district schools and to see if there was a correlation between the grades and the amount of budget allocated to the school to better budget in the upcoming years. However, we needed to remove the 9th grade scores with NaNs for Thomas high school becaus they were fraudulent. From there, we ran the analysis again to see how it impacted the overall scores & % passing. 


## How is the district summary affected?
In the district summary, we saw no change in the district schools because the data being affected was coming from the charter school Thomas High School. After we removed the 9th grade reading & math scores, their average math scores went down & average reading scores went up. Their average math scores went from 83.473 to 83.465 & their average reading score went from 83.896 to 83.902. This indicated the the reading section improved Charter schools and the math sections fell after removing the 9th grade scores. This same data translated into the % passing math for charters & % passing reading for charters. The overall passing percentage went down after removing the fraudulent scores. 


##How is the school summary affected?
In the school summary, we see that the same trend is followed as the district summary. When we focus on Thomas High School the overall passing percentage went from 90.948% to 90.63%. While math passing % is lower & reading passing % is higher, it is very minimal and does not create a significant change in the data % overall. 

##How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Although their overall passing % decreased, it was not enough to knock them out of the 2nd best rating. The next school was Griffin High school and they were at 90.599%, so they still kept the same ranking, but their gap to the top school was further and the gap to the 3rd best school was a lot closer. 

##How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade - It does not affect the grades 10-12th since their overall grades stayed the same. 
Scores by school spending - With a lower % of overall passing for Thomas High School. It means that their $ allocated per student passing is higher now since they have a lower passing percentage. However, Thomas high school still has a very good overall passing percentage and is using its $638/per student very efficiently compared to other schools who have higher budgets and overall passing % in the 50s such as Hernandez High School, who has a passing percentage of 53.5% & a budget of $645-$675 per student. 
Scores by school size - Thomas High school has a very low population so their scores by school size would be affected negatively. The lower the population, the higher the overall passing %. In this case it hurts Thomas high school because they are a small school and their new lower passing % will indicate that even with a lower population, their overall passing % went down. 
Scores by school type - Charter schools now have a lower passing percentage, although it is very minimal but it still hinders their overall passing % if just by a bit, (less than 1%)

##Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
The four changes are that the reading passing percentage went up for thomas high school, the math passing percentage went down for thomas high school & the overall passing percentage for thomas high school, went down as well. The 4th change is that charter schools now have a lower passing percentage as well. This is due to the fact that we removed the 9th grade scores and only accounted for 10-12th graders. It highlights that they 10t -12th graders have slightly stronger reading abilities and slightly lower math abilities. 
## Resources
-clean_students_complete.csv
-missing_grades.csv
school_complete.csv
students_complete.csv
