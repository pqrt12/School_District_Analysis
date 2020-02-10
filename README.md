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

This is a working version, with SHA: e304063.

## School_District_Analysis_Challenge modified.
In last analysis (SHA: e304063), we used Panda df.mean() to calculate the average scores, which excludes Thomas High 9th graders (as their scores are NaN). However, when we calculated the passing percentages, those students are not excluded in total student counts, resulting significant passing percentage drops. To be consistent with Panda df.mean(), Thomas High 9th graders will be excluded from the student counts in this analysis.

Removed Thomas High 9th graders, as they all got NaN scores. Make sure per student budget and school size, etc still count Thomas High 9th graders. All other procedures are same.

- A Thomas High 9th grader summery is generated to better understand what to be excluded.
- No notice change in district summery.
- In school summery, now Thomas high's performance is represented by 10th, 11th and 12th graders. No changes in average scores from previous challenge analysis, the passing percentages are bounced back to 93%, 97% and 91%. No other schools are affected.
- Thomas high remains in the top 5 schools; no changes in bottom 5 schools list.
- The performance analysis result for each grade in each school is same as previous challenge analysis. Only Thomas high 9th graders have nan average scores in math and reading, all other grade / school see no changes.
- Comparing to previous challenge analysis, the school group with budget $630-644 per student now see the math, reading and overall passing percentages increased to 73%, 84% and 63%. This makes spending-performance analysis meaningful. No other changes.
- Comparing to previous challenge analysis, the medium size school group (where Thomas High belongs to) sees math, reading and overall passing percentages increased to 94%, 97% and 91%. No other changes.
- Chart school group see math, reading and overall passing percentages increased to 94%, 97% and 90%. No other changes.
- overall, before and after excluding Thomas high 9th graders, we have insiginicant difference in all analysis results. Of cause, Thomas high 9th graders have NaN scores.

