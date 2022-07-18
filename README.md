# School_District_Analysis



# Overview

In this assignment we were tasked by the school budget committee to help analyze and present data that would help the team make more informed decisions on their upcoming yearly budget allocation.

-Step 1: Clean up the Data
- The first step in this analysis was to look at the data provided by the school district to see if there was anything that needed to be cleaned up before we began. In this phase is was discovered that the Thomas High School 9th grade data was flagged for being inaccurate. After meeting with the board it was decided to exclude the inaccurate Thomas High data from the analysis to provide a more accurate representation of the  district.
- In order to remove this data from our analysis, we used a simple "loc" function to find and replace the 9th grade data with "NaN"

-Step 2: Define the outputs
- In meeting with the board, our team helped define the Key Performance Indicators (KPIs) that would be most useful in budget allocatio0n discussions. These KPIs were defined as the following;
	- Average Math Score
	- Average Reading Score
	- % Passing Math
	- % Passing Reading
	- % Overall Passing

-Step 3: Present the Data
- In order for the board to utilize this data to its full potential, we broke down the KPIs into various groupings as follows;
	- Breakdown by School
	- Top 5 schools by "% Overall Passing"
	- Bottom 5 schools by "%Overall Passing"
	- Breakdown by grade
	- Breakdown by yearly budget spending
	- Breakdown by school student population
	- Breakdown scores by school type


# Results
How is the district summary affected?
- From the view of the entire district, the removal of the 461 THS 9th graders did not have much of an impact as it was part of a data population of 38709. Overall passing saw the biggest change, increasing from 64.9% to 65.2%.
					
How is the school summary affected?
- Removing the THS 9th grade only had an impact on THS's bucket in the school summary. "Total Students" adjusted to 1174 from 1635 resulted in the KPIs to recalculate.
	
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Removing the corrupted 9th grade Thomas High Data ended up having a small change on their KPIs. THS dropped from 90.95% overall passing to 90.63%, however this did not change their district ranking and held 2nd place.

How does replacing the ninth-grade scores affect thhe Math and reading scores by grade?
- Reading: The average reading score for THS increased from a 83.84% to 83.9%. However, the % of student passing reading decreased from 97.31% to 97.02%. This did not have an impact on the schools reading ranking and remined in 5th in the district.
- Math: The average math score dropped from 83.42 to 83.35, while the passing math overall dropped from 97.30% to 93.19%. This resulted in THS dropping from 4th to 6th rank in avg math score ranking.
							
Scores by school spending
- THS falls under the "$631-645" category in spending per student. As such, removing the THS 9th grade data only had a small impact on this bucket. % Overall Passing dropped from 62.85% down to 62.77%.

Scores by school size
- THS is categorized as Medium (1000-1999) in our analysis and also had minimal impact on the bucket. Removing the THS 9th graders dropped "% Overall Passing" from 90.62% to 90.56%.

Scores by school type
- THS is a charter school and again removing THS 9th graders only had a small impact on the Charter bucket.
			
# Summary
In the end, the analysis with Thomas High School 9th graders removed from the data has a small impact on the overall district summary, increasing overall passing % by .3 percentage points. The more significant impact this adjustment had was its impact on THS's KPIs along with any of the buckets it fell into in the various 7 breakdowns.
