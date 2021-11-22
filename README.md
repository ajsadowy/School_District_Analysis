# School_District_Analysis
School District Data Analysis Pre and Post Corrections
===
## Layout

> Challenge 4 (folder)   
>  > Resources (folder)   
>  > >schools_complete.csv   
>  > >students_complete.csv
>  >
>  > PyCitySchools.ipynb   
>  >
>  > PyCitySchools_Challenge.ipynb     
>  >     
>.gitinore   
>README.md   
## Project Overview   
### Purpose   
This project's purpose was to continue analyzing school performace data from Py City School District. Upon the discovery   
of possible academic dishonesty for the Thomas High School's 9th grade class, we were asked to remove the alleged
   misrepresentative data and replace it with NaN values to avoid possible incorrect overall data analysis. From there we continued    to process the data from the schools_complete.csv and students_complete.csv using PythonData through Juypter Notebooks.
   
### Results
What is initially discovered was the 9th grade scores for both Math and Reading were extremely leaning towards the left of the distribution of scores. With that specified data removed, Thomas High School's passing rates were in the 90s instead of in the mid to high 60s. This would suggest the 9th grade data were outliers and this analysis does support the hypothesis that academic dishonesty may have been a factor to lowering student's scores.

### Summary   
Ultimately this had a minor (and possibly unnoticable) impact to analyzing the data for the whole school district. Upon comparing performances by size, student funding, and school type, the most impacting variable is the school size (based on student population). While charter schools were less funded (per student) only seemed to out perform their district counterpart due to student population size.

