# Kickstarter-Analysis

## Overview of Project
Analyzing a kickstarter dataset on specific crowdfunding campaigns to uncover trends.

### Purpose
The purpose of analyzing this dataset is to provide visualization to the project trends. By using charts and graphs to pinpoint and highlight the Goals based on Outcome as well as Outcomes based on Launch date.

## Analysis and Challenges
By filtering the dataset and color-coding the campaigns by outcomes of successful, failed and canceled projects. It easy to identify each category and the outcomes for the kickstarter campaign. Using the [Countif Excel Function](https://support.microsoft.com/en-us/office/countif-function-e0de10c6-f885-4e71-abb4-1f464816df34) making it convenient to determine how each project did.
 To further detail the kickstarter campaigns success, failed, and canceled categories the [Sum Excel Function](https://support.microsoft.com/en-us/office/sum-function-043e1c7d-7726-4e80-8f32-07b23e057f89) in excel was used to calculate percentages to display just how well each category did focusing on the Play/Theater projects.

The kickstarter dataset was also filtered by theater outcomes based on Launch date. *Example: 1476094907 was converted into Thursday, August 11, 2016* using the [Unix timestamp converter](https://www.epochconverter.com/).

### Analysis of Outcomes Based on Launch Date
In the chart Below the month of May is the most successful time to Launch a kickstarter Theater campaign.
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/96032255/148666659-653c8a85-edff-41e4-b4d1-b01bd9d4f835.PNG)

### Analysis of Outcomes Based on Goals
Outlined in the chart below Campaigns with goals less than $1000 and campaigns with a range of $1000 to $4999 were successful 73-75% of the time. Where kickstarter campaigns that had goals of $45000 to $49999 were not successful at all with 0%.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96032255/148667031-56971648-5893-44eb-8de1-4f4d841e228c.png)

### Challenges and Difficulties Encountered
Using a dataset this large and having to analyze its data was a bit of a challenge. Some of the formulas that were used also presented a challenge, with GitHub being the most challenging because it is not at all familiar to me.

## Results
- In conclusion of Outcomes Based on Goals overall there were more successful campaigns in Theater than there were that failed. The best time to launch a kickstarter campaign would be in May and June with May being the most successful Month having 111 successful campaigns out of 166 total. December would be the worst time to Launch a kickstarter campaign with a combined total of 75 kicksters launched and only 37 of them were successful. 

- In conclusion of Goals that were less than $1000 had a 75% success rate and golas in the range of $1000 to $4999 came in at a close second of 73% success rate. None of the 1112 kickstarter campaigns in the Theater/Play category were canceled. 

- The Limitations of this dataset is that it only highlights data for Theater/Plays and not all categories. One example being the Live category, was not included in this analysis.

- An overall chart analyzing which parent category and sub category could have been created showing it's successes and failures. As well as a Pivot table or graph that outlines all of the campaign lengths.






