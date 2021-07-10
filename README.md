# PyCity Schools with Pandas

## Overview
We have been notified by the school board that the <code>students_complete.csv</code> file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. We have been asked to replace the math and reading scores for Thomas High School with **NaNs** while keeping the rest of the data intact.

With the suspicious math and reading scores removed from the district calculations, presented here is the updated school district analysis report.

### Results:
The updated School District Summary displaying average math and reading scores and percentages passing for the district as a whole:  
![District Summary](/Resources/report_details/district_summary.png "School District Summary")  

- Here are the math and reading test averages per school and per grade level:  
![Test Averages by Grade](/Resources/report_details/averages_by_grade.png "Test Averages by Grade")  

- The top 5 performing schools by overall passing percentage are:  
![Top 5 Schools](/Resources/report_details/top_schools_overall.png "Top Five Schools")

- The bottom 5 performing schools by overall passing percentage are:  
![Bottom 5 Schools](/Resources/report_details/bottom_schools_overall.png "Bottom Five Schools")  

- Score Averages by Budget per Student  
![Spending Per Student](Resources/report_details/spending_ranges_per_student.png "Score Averages by Budget Per Student")  

- Score Averages by School Size  
![School Size Results](Resources/report_details/school_size_results.png "Average Scores by School Size")  

- Score Averages by School Type  
![School Type Results](Resources/report_details/school_type_results.png "Average Scores by School Type")  

## Summary:

This data shows trends in the following areas:
* Teachers with higher budgets per student did not yeild higher overall test passing percentages.
* Large schools (of 2000-5000 students) underperformed vs. small and medium sized schools by about 50%.
* Charter schools are outperforming District schools by about 50% in overall passing percentage.
* ***Of the top 5 performing schools, all are Charter schools.***
* ***Of the bottom 5 performing schools, all are District schools***
