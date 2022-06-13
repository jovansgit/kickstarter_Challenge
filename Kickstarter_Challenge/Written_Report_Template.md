# Kickstarting with Excel

## Overview of Project
Kickstarter is a crowdfunding platform to help creative projects get off the ground.  In this project we will analyze kickstarter campaign data to find insights that can help launch a successful campaign.

### Purpose

The purpose of this analysis is to understand how different campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The focal point of this analysis is understanding how the outcome of a theater campaigns are affected by the launch date.  Our Kickstarter data set is comprised of 4,114 rows of raw data for campaigns that occurred between 2009 and 2017.  To start we created a pivot table and filtered the data which had a parent category of “Theater”.  After creating our pivot table, we see the following campaign totals:

- 839 successful 
- 493 failed 
- 37 canceled
 
Next, we create a line chart to help examine the relationship of outcomes and their launch month. 
![Theater_Outcomes_vs_Launch](/Kickstarter_Challenge/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

The focal point of our next analysis is understanding how the outcome of theater campaign are affected by the funding goal amount.  For this analysis we create a goal to percentage table.  

![Table](/Kickstarter_Challenge/resources/Percentage_To_Goal_Table.png)

We then create a line chart visualizing the outcome of the Kickstarter campaign based on the goal.

![Outcomes_vs_Goals](/Kickstarter_Challenge/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
One challenge that others may face when analyzing this dataset is picking the best column, row, and value fields when creating their pivot tables.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - The best month to launch a Kickstarter campaign is May.
    - The worst month to launch a Kickstarter campaign is December.
        - This leads to the question what outside influences can we attribute this to.  Is it possible that backers have higher disposable income due to tax returns in April?  Is it possible backers have less disposable income around the holiday season?
- What can you conclude about the Outcomes based on Goals?
    - Campaigns with a goal of less than 1000 were the most successful followed by campaigns with a goal from 1,000 to 5,000.  

- What are some limitations of this dataset?
    - Most campaigns in our dataset have a goal of less than 15,000 which diminishes the statistical relevance of the campaigns with higher goals
    - This dataset has a country field however we are not able to drill down further into the states, provinces, or territories.  Specifically, for plays it may be helpful to deep dive into the cities. 

- What are some other possible tables and/or graphs that we could create?
    - I would be interested in creating a table and chart to help analyze how the length of a campaign impacts the outcome.  We can perform this analysis using the date “Date Created Conversion” and “Date Ended Conversion” fields to get the campaign length. 
