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
  * Overall combined passing math and reading percentage decreased 0.3%.

<img src="https://github.com/katmarcin/School_District_Analysis/blob/100acb61dd0a5bdc31a08f6acda04b6e4ed43e87/Resources/updated.png">

<img src="https://github.com/katmarcin/School_District_Analysis/blob/278b967ee1c448b0df60f508e2238a8fa4e02081/Resources/original.png">
 
* School Summary Changes for Thomas Edison High School:
  
  * Average math score decreased 0.07%.
  * Average reading score increased by 0.05%
  * Average passing math percentage decreased 0.09%
  * Average passing reading percentage decreased 0.3%
  * Overall combined passing math and reading percentages decreased by 0.3%

* Thomas High School’s performance relative to the other schools remained unchanged after removing even after having been omitted from the second data analysis. Thomas High School is still ranked 2nd among the 15 high schools. 

<img src="https://github.com/katmarcin/School_District_Analysis/blob/100acb61dd0a5bdc31a08f6acda04b6e4ed43e87/Resources/top%20schools.png">

* Math and Reading Scores by Grade Level

From our modified dataset, we analyzed math and reading scores by Grade Level to see if one outperformed the others. We determined that Grade Level did not affected the averages for math and reading scores. There was no distinct pattern and if there had been any difference between the score averages, it was less than 1-2% difference at most.


* Scores by School Spending

<img src="https://github.com/katmarcin/School_District_Analysis/blob/100acb61dd0a5bdc31a08f6acda04b6e4ed43e87/Resources/spending.png">

* Scores by School Size

<img src="https://github.com/katmarcin/School_District_Analysis/blob/100acb61dd0a5bdc31a08f6acda04b6e4ed43e87/Resources/school%20size.png">

* Scores by School Type

<img src="https://github.com/katmarcin/School_District_Analysis/blob/100acb61dd0a5bdc31a08f6acda04b6e4ed43e87/Resources/school%20type.png">


## Summary

After having replaced ninth grade student grades at Thomas High School with NaNs, we came to the conclusion that were changes were made in the updated school district analysis which we can determine arose from academic dishonesty. For the districts as a whole, the most impacted key metric was the overall combined passing math and reading percentages which decreased by 0.3%. For Thomas High School itself, the overall passing math and reading percentage decreased the most of all metrics, with another decrease of 0.3%. The average passing reading percentage for the school experienced also another 0.3% decrease while the average passing math percentage 0.09%. Because of the small percentage, we can attribute both numbers to be the same here due to approximation and clearly passing reading percentage had the most impact on overall passing percentage for the combined scores. An insignificant difference was observed for Spending Ranges (per student) against math and reading averages and passing percentages. None of the values changed which indicates that our necessary changes did not affect this particular outcome. Lastly, the same outcome occured for Scores by School Size. Fortunately, our omitted changes had zero effect on either of the school size groups which shows that it was insignificant. It is important to document, analyze, and understand changes to data because it helps us understand the trends we are visualizing. And for our stakeholder, this data ultimately affects the budget and allocation of money, and precision is key. 


