# School_District_Analysis

A math / reading test were given to all high school students in a school district; and student scores were collected.

Based on the test scores, this analysis did:  
- input all student data and all school data into panda data frame;  
- correct student names (no professional prefixes or suffixes);  
- Performed school district analysis, generated a district summary;  
- Performed per school analysis, generated a per school summary;  
- Listed out the top 5 / bottom 5 performaning schools, based on over math / reading passing percentage;  
- Generated a summery with average math scores in each grade at each school;  
- Generated a summery with average reading scores in each grade at each school;  
- Generated a school performance summery based on the spending per student;  
- Generated a school performance summery based on the size of school;  
- Generated a school performance summery based on the type of school.  

## School_District_Analysis_Challenge

School district voids all Thomas High 9th graders test scores. Repeat all analysis.

In Panda DataFrame, overwrite all Thomas High 9th graders test scores with np.nan. Repeated all analysis.

- There are minor difference in school district level, as only a small number of students scores are voided.
- As expected, other than Thomas High, no changes in per school summary. Some minor difference in Tomas High average math / reading scores; math, reading and overall passing percentage are dropped significantly, from all around 90% to 74%, 85% and 64% respectively.  
- Thomas High is dropped out the top 5 schools in this analysis, it is not in the bottom 5 schools either. The new top 5 schools are Cabrera High, Griffin High, Pena High, Wilson High and Shelton High.
- In the average math score summery per school, per grade, only Thomas High 9th graders now has a NaN, no change for all others.  
- In the average reading score summery per school, per grade, only Thomas High 9th graders now has a NaN, no change for all others.
- Based on budget per student, Thomas High is among $630-644 groups. Only this group is affected. See minor changes in average scores, significant drops in math / reading / overall passing percentages.
- Thomas High is a medium size school, this school group see minor change average scores, significant drops in math / reading / overall passing percentages. No changes in other school groups, as expected. 
- Thomas High is a charter school. Charter school group now see minor changes in average scores, significant drops in math / reading / overall passing percentages. No analysis result changes in district school group.
