# An Analysis of Kickstarter Campaigns with Excel

An analysis to uncover trends and budgets for future campaigns.

## Overview of Project

Louise's data was combed, filtered, and formatted to find data about Kickstarter campaign outcomes 
based on launch date as well as finding the percentage of successful campaigns. 

!.[.].(/Theater_Outcomes_vs_Launch.png)

!.[.].(/Outcomes_vs_Goals.png)

### Purpose:
The purpose of this project was to organize data and perform financial analysis.

### Analysis and Challenges
The challenge consisted of taking a Kickstarter worksheet with 4113 rows of data as a practical application exercise of week 1 module. We used filters and
conditional formatting to narrow our analysis to data most relevant to Louise.  We filtered for the subcategory of plays to analyze their success rate. 

### Analysis of Outcomes Based on Launch Date

A pivot table was required in for this analysis.  The table was filtered for the parent category as well as the year the campaign was launched.  
The rows were the launch date conversion from Unix Timestamp.  The Columns were the three possible outcomes; successful, failed, or canceled along with 
the total monthly launches. 

### Analysis of Outcomes Based on Goals

The actions required to run this analysis were to create a table and use the function =COUNTIFS to create: total projects launched as well as totals of
projects successful, failed, and canceled.  This data was used to create a line chart as a visualization of the data.

### Challenges and Difficulties Encountered

My biggest challenge is not having a lot of practice with Excel.  I found myself lost a few times and used Google to look up possible solutions
but did not find any of my results helpful.  I did use Slack and found a study group that helped clear all of my gray areas.  I do not believe I would have
found those solutions on my own. 

## Results

Two conclusions about *Outcomes based on Launch Date:*
1) More Kickstarter campaigns were successful than failed with more successful campaigns launches beginning in May.
2) Do not launch a campaign in the Winter with December and January having the lowest successful launches.

After analyzing the line chart for _Outcomes based on Goals_ it is clear the most successful outcomes were for those launches with campaign goals
less than $1,000.  As the campaign goals increase so too does the failure rate.  The optimal goal range is $25,000-$29,999 as it has the highest success
rate of any goal greater than $5,000.

As a beginner I find it difficult to know what the limitations of the data might be.
