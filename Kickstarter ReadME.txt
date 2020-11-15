# Kickstarting with Excel

## Overview of Project

### Purpose

#### The purpose of this project is to provide an anlayis of Kickstarter Campaign data to Louise. Louise has completed her fundraising campaign for her play, *Fever*. She came close to her fundraising goal thanks to the previously provided analysis and recommendations.  She would now like an analysis on how well different campaigns did based on their launch date and their funding goal.

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date

#### To perform this analysis, I created a pivot table and chart using the Kickstarter data. I filtered the data by the parent category, theater. I then placed the outcomes in the columns and the launch date in the rows. 
![Launch](/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

#### To perform this analysis, I started by creating a chart with goal amounts for the rows and the Number of Successful, Failed, and Cancelled campaigns as well as percentage of each of those in the columns. To find this data, I created COUNTIFS staments to pull data from the Kickstarter data tab. I then created a line chart with the goals on the x-axis and percentages on the y-axis. The chart gives a great visual representation of the data.
![Goals](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

#### 
* A potential challenge with completing this analysis is how to get the months to display correc tlyin the Outcomes Based on Launch Date Pivot Table. This data did not automatically appear as needed, I had to use the grouping function in Pivot Table Analyze menu to resolve the issue.
* Another potential challenge was completing the COUNTIFS statements in the Outcomes Based on Goals Analysis. If unfamiliar with this formula, it is challenging to make sure to include all of the variables, especially to include the correct goal amounts in the formula.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 

The first conclusion that I draw from the Outcomes based on Launch Date Analysis is that May is the best month to initiate a campaign, followed by June and July. The second conclusion is that December and January are the worst months to launch a Kickstarter campaign.

- What can you conclude about the Outcomes based on Goals?
The first conclusion that I draw from the Outcomes based on Goals analysis is that campaigns up to $5000 are the most successful. The second conclusion from this analysis is that campaigns of $45,000 and up are very unsuccessful.

- What are some limitations of this dataset?

One limatation of the dataset is that it includes campaigns in all countries, it would be more valuable to drill down to a specific location. I believe another limation of the data is that for the Outcomes based on Luanch Date Analysis we only filtered by parent category, we could have drilled down further to plays only.

- What are some other possible tables and/or graphs that we could create?

One usefull table and graph that we could create would be Outcomes based on lenght of campaign. We would first have to add a new column and use the formula to determine lenght from the launch to the end of the campaign.  Then we would make a chart similar to the one used for goal amount, but change the goal amounts to ranges of lenght of campaign. Another possible chart and graph could be Outcome based on number of backers.  This would be set up similar to the Outcomes Based on Goal Analysis.
