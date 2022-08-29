#  ***School_District_Analysis*** 

##  Project Purpose
Analysis of student Math and Reading test results for a School District utilizing Python, Jupyter notebook, Pandas, NumPy, and OS. During the course of this project, evidence of academic dishonesty and grade alteration were noted for 9th grade student scores in reading and at Thomas High School within the district.  With this latest information, analysis was repeated and submitted for evaluation with the suspect scores removed. 

##  Project Overview 
 Fifteen highschools comprise the district and include grades 9-12 at eah of the schools.  Data for the district were submitted in 2 .csv files for the analysis and are read into python to complete the analysis.  With the reporting of compromised data for 9th graders at Thomas High School, the district has requested that all data for these students be converted to Nan so that it is not considered in the performance data for the district.  The python script is divided into sections with the first section focused on cleaning of the data set and elimination of the compromised test scores.  Once the data has been prepared, key metrics include the following:
 
  - School district summary performance by school for all 15 schools.
    - Math and reading scores by grade for the district
    - Scores by school spending levels per student
    - Scores by school size - student population
    - Scores by school type - charter versus district
    
## Results and analysis:
Final Summary of District Results is listed below:
https://github.com/KJAnalytics/School_District_Analysis/blob/main/Resources/Updated_District_summary%20.png

### Key findings:

  - Compromised test data impacts not only Thomas High School but overall district performance but mainly in limited movements in the top ranks of the district.  After reviewing the data and removing the 9th grade results from the analysis, the total students with test scores at THS is reduced to 1174 from 1635. This represents a reduction of reported scores by 461 students or 28.2% of the school's population. With this change, Math scores had no impact while reading scores had a 2% increase
  
  - A disparity exists between charter and district schools with Charter schools outperforming District schools.
      - Charter school pass rates are nearly 27% higher than district schools.
      - District schools are all considered large with populations greater than 2000 students while charter schools are all Medium or small schools.
      - While district schools have some of the highest per student spending versus Charter schools, this does not correlate to improved test scores.  
      - While a small difference of 2-3 points can be noted between district and charter schools in reading test scores, math score differences are significant with a downward shift of nearly 7 points in math test score averages at the district schools.
      https://github.com/KJAnalytics/School_District_Analysis/blob/main/Resources/Updated%20Pass%20rates%20by%20school%20type%20-%20after%20THS%209th%20grade%20changed%20to%20Nan.png
      https://github.com/KJAnalytics/School_District_Analysis/blob/main/Resources/School_performance_by_schoolsize-THS_updated.png
      https://github.com/KJAnalytics/School_District_Analysis/blob/main/Resources/School_passrates_by_spendingperstudent.png
      
      
      
      
      
  



__________________________________________________________________________________
