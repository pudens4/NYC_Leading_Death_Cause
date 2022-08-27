# New York City Leading Causes of Death

# Overview
The data on [NYC Leading Cause of Death](https://data.cityofnewyork.us/Health/New-York-City-Leading-Causes-of-Death/jb7j-dtam) provide information on the different reasons someone is dead. 

# Process 
The first step in my data analysis process was to clean the data and get it ready for analysis. I used Jupyter Notebook for faster processing and the 
pandas module to get the data ready.
<br>
The following are some challenges encoutered in the process of cleaning the data. 
* for the sex column, some were F and some were Female this had to be fixed.
* the deaths, deaths rate and age adjusted death rate had some empty cells. with periods and NaN. in all those cells, I replace them with a 0
* the race ethnicity had to be fixed because some cells were black non hispanic while others were non hispanic black. and the other ones we don't know were replace to Unknown
* and for the leading cause column, some disease where the same but reported as different because of an empty space, or variable change

# Findings

I have visualize my findings on Tableau and add the links below. 

[Leading cause of death by gender and ethnicity](https://public.tableau.com/views/NYC_Death_Leading_Cause_Gender_Ethnicity/Story2?:language=en-US&:display_count=n&:origin=viz_share_link) 

[Death over time by gender and ethnicity](https://public.tableau.com/views/NYC_Death_Gender_Ethnicity/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)
