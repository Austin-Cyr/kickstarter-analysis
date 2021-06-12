# An Analysis of Kickstarter Campaigns
---
---
## Overview of Project

-  Louise created a fundraising goal on Kickstarter to help fund her play, Fever. She achieved
her fundraising goal in a short amount of time and is curious about how other campaigns compared to
her success based upon their launch dates and funding goals.. 

### Purpose
-  The purpose of my analysis was to help answer Louise’s questions regarding if there was a
correlation of a fundraising campaign’s success rate based on the launch date and funding amount
goals.

## Analysis and Challenges
-  In order to answer Louise’s questions, I was able to obtain a significant data set from Kickstarter
that contained information from over 4,000 Kickstarter campaigns over a period of 9 years. The data
contained information regarding the campaign funding goal, its funding amount, the result of the funding,
the date the campaign started and ended, whether each was successful and categories of the project. By
analyzing the data through excel formulas, pivot tables and charts, I can help answer Louise’s questions.

### Analysis of Outcomes Based on Launch Date
-  In order to determine how the Outcomes were impacted by the Launch Date, I found that I needed to 
convert a few types of data to be structured into a more usable format. I converted the Linux based dates 
to an excel style dates, separated the category/subcategory field and created a strictly “years” column. 
From here, I created a pivot table based upon the months of the year, outcomes and parent category of project 
to ascertain the count of projects that fit in each criteria. I then created a chart showing the amount of 
projects for each outcome over time. This is the chart represented by “Theater Outcomes by Launch Date.”

### Analysis of Outcomes Based on Goals
-  I’m order to determine the Outcomes based on Goals, I created buckets for the dollar amount goals.
I created buckets of $5,000 and then counted the number of campaigns in each bucket that were for a 
Play based on if they were successful, failed or canceled. From there I summed up the total and determined 
the percentage of how many campaigns in each Goal bucket were successful, failed or cancelled. I then 
visualized this data with a line graph with the Goal buckets on the X-axis and the Percentage on the Y-axis. 
This is the chart titled “Outcomes Based on Goal.”

### Challenges and Difficulties Encountered
-  Several challenges arose during this analysis because of the format of the data. The first was that 
the dates provided were in a Unix format, which I needed to convert to data that excel could easily read. 
I also needed to separate the Category and Subcategory field because they were provided in 1 field. 
## Results
Based on my analysis, I can draw a few conclusions regarding the correlation between the Outcomes and 
the Launch Data and Goals. The Outcome based on Launch data shows that there are more successful campaigns 
that have started in May, June and July. And it appears that there is about an equal number of campaigns that 
have failed through the entire year. Though, I would not state that you are more likely to be successful if 
you start your campaign in the May, June or July, but that more campaigns started during this time period. 

Another way that I reviewed the data was by comparing the Outcomes to the Goals. By reviewing the data, 
we show that Goals with smaller dollar amounts (less than $15,000) have a greater percentage of meeting 
the funding goals. And we see that Goals with greater dollar amounts (greater than $40,000) were not as 
successful. This is true for all categories but also for the “plays” category.

While these findings provide some clear results, there are some limitations to the dataset. While we know 
if some campaigns failed, we do not know why they failed. There could be some instances that lead to their 
failure that would not be based on the dollar amount requested or launch date. These campaigns would 
represent a campaign that we might not want to utilize in the results. 

In order to help develop these results further, I could also review how long each campaign took to achieve 
their goals. This would be important to know if campaigns were successful in a short amount of time or do 
the campaigns become successful because they provide enough time to collect funds. I also think it would 
be helpful to eliminate certain outlier projects to ensure that our analysis was based upon campaigns that 
occurred within our 95% confidence level. 
