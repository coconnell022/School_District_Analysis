# School_District_Analysis
Using Python and Anaconda (Jupyter Notebook) to perform an analysis on school data

## Overview of the school district analysis:
The purpose of this project was to perform a comprehensive analysis on school data to provide key insights on performance trends that will inform discussions within a school district. After the initial analysis was performed, it was discovered that certain data collected from one of the schools, Thomas High School, was inaccurate for 9th graders, specifically their math and reading scores. The objective was to replace the incorrect scores with “NaNs” and re-perform the analysis, while keeping the rest of the data intact. This report will show the full extent of that analysis and how the changes in grades reflected the overall results. 

    Resources
      - Data Sources: clean_students_complete.csv, schools_complete.csv, students_complete.csv
      - Software: Python 3.7.6, Jupyter-Notebook 6.0.3, Anaconda 4.8.3, Pandas

## Results:
- How is the district summary affected?
    - After replacing Thomas High School’s 9th grade math and reading scores with “NaN”, the average and passing score decreased overall as well as for math and    reading. The 4 changes are described below:
       -	Average Math Score went from **79.0** to **78.9**
       -	% Passing Math went from **75%** to **74.8%**
       -	% Passing Reading went from **86%** to **85.7%**
       -	% Passing Overall went from **65%** to **64.9%**

- How is the school summary affected?
  - After replacing the data and updating the analysis to not include those scores, only the results for Thomas High School were affected within the school summary analysis. The passing percentages decreased as described below:
     -	% Passing Math went from **93.3%** to **93.2%**
     -	% Passing Reading went from **97.3%** to **97.0%**
     -	% Passing Overall went from **90.9%** to **90.6%**

- How does replacing the 9th graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Relative to other schools, Thomas High School is still placing at number 2 for the district of 15 schools. Before changing the 9th graders math and reading scores, Thomas High School had an overall passing percentage of **90.9%**. After replacing the scores, their overall passing percentage dropped by only .3%, which still keeps them at the number 2 spot; outperforming Griffin High School by just .04%. 

- How does replacing the 9th-grade scores affect math and reading scores by grade?
  - There is no change for math and reading scores by grade, except for Thomas High School’s 9th graders now have “nan” in place of the previous grade, which was **83.6** for math and **83.7** for reading. 

- How does replacing the 9th-grade scores affect score by school spending, size, and type?
  - There are no changes in the school spending, school size, or school type data frames after replacing the 9th grade scores. 

## Summary:
After replacing the 9th grade reading and math scores at Thomas High School with “Nan”, several changes occurred in the overall analysis. A major change is reflected within the overall district summary data frame, where the average math score, % passing math, % passing reading, and % overall passing all decreased. While it is important to note that replacing these scores decreased the stats, the amount they decreased by is minimal. In all cases it only lost a small fraction of a percent and grade, so it did not have a significant effect on the overall analysis. Another major change that occurred is on Thomas High School’s overall academic performance. After replacing 9th grader’s scores, the analysis was being performed on only Thomas High School’s 10th, 11th, and 12th graders. As a whole their percentages for passing math, passing reading, and overall passing decreased by minimal fractions. Their average reading score increased from 83.8 to 83.9. This shows that the reading scores for 9th graders at Thomas High School were underperforming compared to that of the other grades. Despite the changes affecting Thomas High School’s overall performance, they still ranked as number 2 out of 15 schools for the entire district because the changes were negligible in comparison. The image below depicts the top 3 schools of the district ranked by overall passing percentage and still showing Thomas High School as number 2. 

![alt text]( https://github.com/coconnell022/School_District_Analysis/blob/main/Images%20for%20README/Screen%20Shot%202020-10-18%20at%209.33.09%20PM.png?raw=true)

Overall, while it is always important to ensure that data being collected is accurate and not falsely reported, sometimes these minimal mistakes do not make a drastic impact on results. If this analysis were to be done on a smaller scale where they are looking at individual high schools instead of overall district reports, then the change would significantly impact Thomas High School’s academic performance. However, for this analysis specifically, changing the scores to reflect “Nan” will not influence conclusions drawn or decision making for this district. 






