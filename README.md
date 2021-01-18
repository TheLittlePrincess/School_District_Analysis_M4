# School_District_Analysis
## Overview
The objective of this project is to help the City school system to determine how, if the potential fraud occurred among 9th graders at one of the schools, affected the analysis around standardized testing and funding.
##**Analysis**

After the compromised class/school were identified, we proceeded to remove such grades from the data. 
By removing the math and reading scores of every student of 9th grade at the Thomas High School and recalculating the average scores, passing averages and other key data we were able compare that vs the original calculations and determine how those key metrics were affected by the changes on the data

**Effect on School District Metrics & Comparison**
![Key Metrics](https://github.com/TheLittlePrincess/School_District_Analysis_M4/blob/main/Key_Metrics.png)
 
-	Total number of students: We were able to determine that there were 461 of  9th graders in Thomas High School, therefore the total of 39,170 students considered within the initial analysis, was reduced to 38,709, when it came to the score analysis.
-	The total number of schools remained the same, 15.
-	Now In terms of the scores, the change for reading scores was virtually none once the scores from the 9th graders at Thomas High School were excluded, from  81.8778  to 81.8558. For math, although slightly more, still very  small, from 78.9853, to  78.9305.
-	Post exclusion, the percentage of users that passed the math test as well as the reading one was slightly reduced. Math passed percentage went from 75.0% to  74.8% and for reading was from 85.8 % - 85.7%
-	Overall passing percentage was reduced as well, going from 65.2% prior excluding the 9th graders at Thomas High School, to 64.9%
-	The total initial budget was 24’649,428, and there is no indication that such amount would change since even when the scores might have been dismissed for the effects of the ranking, there is no reasons to believe the budget for the 461 9th graders would be neither suppressed from the Thomas High School budget, nor would be redistributed among the students of the other grades for the same institution. Grades were dismissed (re: changed to NaN) from the purpose of ranking, however the students were kept. Note that at a $638 capita spending, we’re talking about less than 1% of the entire school district budget.

**Schools Ranking**

-	Given that not only the 9th graders had a good performance for the tests when it came to the Thomas High School; once those were excluded, the overall ranking of the school didn’t suffer and Thomas High School remained in the top 5 best schools, led by Cabrera High School as seen in the  Lowest_performers_Overall graph

![Highest performers Overall](https://github.com/TheLittlePrincess/School_District_Analysis_M4/blob/main/Highest_performers_Overall.png)

![Lowest performers Overall](https://github.com/TheLittlePrincess/School_District_Analysis_M4/blob/main/Lowest_performers_Overall.png)
-	As per the worse performers, Rodriguez High School was the worse among the 15 schools in the district, with an overall passing rate of 52.99%, close followed by Figueroa, Huang, Hernandez and Johnson High Schools, as seen in the graph (Lowest_performers_Overall)

 

**Summary**
Here the graph showing the updated scores and metrics post removing the Thomas High School 9th graders’ scores
![All Schools Summary with Ranges](https://github.com/TheLittlePrincess/School_District_Analysis_M4/blob/main/Per_school_summary_with_ranges.png)
