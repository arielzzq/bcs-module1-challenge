# An Analysis of Kickstarter Campaigns outcomes based on goals and launch date

## Overview of Project

### Purpose
The purpose of this analysis is to investigate the relationship between the campaigns outcomes and their goals and launch dates

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I created a pivot table using the Kickstarter data. I use "Year" and "Parent category" as the filter of the table and set column to "outcomes" and rows to "date created" and get the count of "outcomes" as value. In this way, I could look at numbers of different outcomes on different months. I could also use the filter to look at the result in different year or different parent category. 
![Pivot_table_1](Pivot_table_1.png)
A 2-D line chart with markers was used to visualized result. Different months was on x-axis and the the outcomes count was on Y-axis, different line represented percentage successful, failed and cancelled respectively. In this way, we can clearly figure out which month has the most percentage successful or failed.
![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)
 
### Analysis of Outcomes Based on Goals
To investigate the relationship between outcomes and goals, I created a table and stratified the goal in to different rows. On different columns, I used Countif formula to count the number of successful, failed and cancelled project for campaigns with different goals. The formula is shown below:
![Countif_formula](Countif_formula.png)
After that I calculated the percentage successful, failed and cancelled project for each goal level by divide the total project number by number of successful, failed and cancelled respectively. The table is shown below
![outcome_goals_table](outcome_goals_table.png)
A 2-D line chart was used to visualized result. Different goal level was on x-axis and the percentage was on Y-axis, different line represented percentage successful, failed and cancelled respectively. In this way, we can clearly figure out which goal level has the most percentage successful or failed.
![Outcomes_vs_Goals](Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
