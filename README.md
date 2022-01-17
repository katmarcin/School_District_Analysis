# School_District_Analysis

## Overview of the School District Analysis

Maria, a schoolboard stakeholder, has asked us to prepare her a code using Jupyter Notebook for a presentation to district officials that analyzes data from 15 high schools and their key metrics such as sums, averages, and percentages related to math and reading test scores. The purpose of this project is to help stakeholders, like Maria, determine how much money should be allocated to and spent on each school and to determine the budget for the next school year. From our code, we were tasked with producing various reports: District Summary, School Summary, High and Low Performing Schools, Math and Reading Scores by Grade, Scores by School Type, Scores by Spending, and Scores by School Size.

The original dataset used to develop our code is schools_complete.csv and students_complete.csv. The data was inspected and cleaned before our analysis to minimize any discrepancies and make any necessary corrections to malformed data. Specifically, in our cleaning data process we were asked to remove math and reading scores from 9th grade students at Thomas High School in the second run of our analysis due to possible academic dishonesty. The programming language we used was Python. Specifically, the PythonData environment was used within Jupyter Notebook coupled with Pandas library to help prepare our analysis.

## Results

Our initial data analysis included the complete student and school data. Maria had asked us to run a second analysis after removing math and reading scores from 9th grade students at Thomas High School due to possible academic dishonesty. In order to do this, these specific scores were replaced with "NaN" so that we can still perform calculations from the original dataset. We analyzed the key metrics between the two data analyses to see if any difference was made by having removed these said students from the new dataset.


* District Summary Changes:
  * Average math score across all 15 schools decreased 0.1%.
  * Average reading score remained untouched.
  * Average passing math percentage decreased 0.2%.
  * Average passing reading percentage decreased 0.1%
  * Overal combined passing math and reading percentage decreased 0.3%.

*image
 
* School Summary Changes for Thomas Edison High School:
  
  * Average math score decreased 0.07%.
  * Average reading score increased by 0.05%
  * Average passing math percentage decreased 0.09%
  * Average passing reading percentage decreased 0.3%
  * Overal combined passing math and reading percentage decreased by 0.3%

*image

* Thomas High School’s performance relative to the other schools remained unchanged after removing even after having been omitted from the second data analysis. Thomas High School is still ranked 2nd among the 15 high schools. 

*image

* Math and Reading Scores by Grade Level

From our modified dataset, we analyzed math and reading scores by Grade Level to see if one outperformed the others. We determined that Grade Level did not affected the averages for math and reading scores. There was no distinct pattern and if there had been any difference between the score averages, it was less than 1-2% difference at most.

*image

* Scores by School Spending

A significant difference was observed for Spending Ranges (per student) against math and reading averages and passing percentages. 

*image

* Scores by School Size

*image

* Scores by School Type

*image


## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
