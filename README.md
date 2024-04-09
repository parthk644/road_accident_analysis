**Data Overview:**
The given dataset consists of data of over 3,50,000 Road Accidents in the UK in the year 2021-22 with fields such as Accident Date, Light Conditions, Vehicle Types, Road, Types, Whether Condition, Casualties, etc.

**Important KPIs:**
1. Total Casualties and Total Accident values for Current Year and Year on Year growth.
2. Total Casualties by Accident Severity for Current Year and Year on Year growth.
3. Total Casualties with respect to Vehicle Type for Current year.
4. Monthly Trend showing number of casualties for Current year.
5. Casualties By Road type for Current year.
6. Casualties by Road Surface for Current year.
7. Casualties by Location (Urban/Rural) for Current year.
8. Casualties by Light Conditions for the Current year.

**Data Cleaning and Transformation:**
+ The dataset does not contain any NULL values. 
+ In the field ‘Accident Severity’, there were a few spelling errors which could lead to incorrect visualizations which were fixed. The same was done for some other fields like ‘Junction Control’.
+ New groups were created for ‘Vehicle Type’, ‘Whether Condition’ and ‘Light condition’ to group together similar observations so that the visualizations are concise yet deliver accurate insights.
+ A new table was created named Calendar to separate out the year and month for the calculation of further measures.
+ New Measures had to be created for calculating year on year growths for casualties and accidents, current/previous year casualties and current/previous year accidents.

**Derived Insights from the visualizations:**
+ From 2021 to 2022 the total number of road accidents have gone down by 11.7%
+ Similarly, from 2021 to 2022 the total number of casualties have gone down by 11.89%
+ Fatal Accidents have seen the greatest reduction amongst all severities of 33.29%.
+ For both the years, November observes the most road accidents followed by October and July
+ February, January and December are the months with the least accidents.
+ Cars are the most common vehicle type which are involved in accidents in the UK.
+ Most of the accidents occur in Urban environments (61.2%) in the Day time (72.9%).
+ Majority of the accidents take place under normal weather conditions and on dry roads.
+ Single Carriageways are the most accident-prone road type
 

