# Kickstarting with Excel

## Overview of Project
The Kickstarter project is designed to help Louise evaluate how her play fever launch date and fundraising compared to other theater plays. We’ll take a deep dive into the data to show by month their success, failed and canceled rates along with breaking out fundraising goals. This will help Louise build her strategy by identifying the right time of year to launch a play and what’s the right budget targets to increase Louise’s chances of being successful and making a profit.

### Purpose
The goal is to use the data to identify what worked well, what were the opportunities for improvement, and the best timing to launch plays. These data sets will help Louise set realistic fundraising targets along with identifying the best months for launching her plays. We’ll look at both what the fundraising outcomes faired to their goals and when’s the best time of year to launch a play to increase its changes of being successful. 

## Analysis and Challenges
For the launch date analysis I took the following approach. I first created a pivot table utilizing the data set on the Kickstarter tab. Then by moving the parent category and years into he filter section I was able to drill down and show only data for the Theater parent category showing all years. Then I dropped the outcomes in the columns, Date created conversation in the rows section and last dropped the count of outcomes in the Values section. This allowed me to see only Theater fundraiser results broken out by successful, cancel and failed by month. Then I added a pivot line chart to show the data in a format that would allow me to tell the story of what months have the highest success rates and which months to avoid.

For the fundraising outcomes date analysis I took the following approach. I created a new sheet utilizing the countIf formula to create a table showing the total number of successful, failed and canceled plays based on their goals results. Then I totaled them up and broke out the percentage based on goal dollar ranges and showed it by successful, canceled and failed. This then allowed me to create a line graph showing the percentage on the Y axes, dollar amount ranges on the X axes and trend the data out. This allowed me to show what target ranges would increase the chances of creating a successful fundraiser vs an unsuccessful one. It allows helps you set your budget targets as well.

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/101777677/161442717-54777913-2477-4a4d-8121-266a2a0a7b54.png)

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/101777677/161442683-3060571d-08da-431a-986c-dbb1ee554996.png)

### Challenges and Difficulties Encountered
For me my greatest challenge was not over thinking my countIf formulas. My first approach I was trying to build a long and complicated formula. After some google searching and looking though my Excel books at home I was able to simplify my approach and finalize the formulas. Then it allowed me to cross reference what my data set produce to what was in our class Module 1 Kickstarter assignment instructions. 

Link to YouTube Video I watched - https://www.youtube.com/watch?v=if4i55JB58M

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first conclusion is that if you look by month with all years combined the data would suggest that you should launch your play mid- spring through mid-summer May, June & July. These three months have the highest success rate. While October, November & December you see the lowest success rates. This would be due to a couple factors. It being winter and there is major holiday in each month that consumes a lot of peoples time and money. 

The second conclusions is very few plays get canceled. There is also little swings by month for failed plays when you look at the trend line over the course of the year. So it would be good to plan you launch in May, June, July months and take a deep dive into which types of plays are driving the high success rate for those months.

- What can you conclude about the Outcomes based on Goals?

If your play is a low budget play your max fundraising goal should not exceed $5,000 or your success rate starts to drop off.$0 to $5,000 plays seems to have a similar success rate as those plays set between $35,000 thru $45,000. As you drill into the data you’ll see only 1% of all plays fall into the $35K thru $45K range. While 76% of all successful plays where $5K on less. Plays set $5K and below also saw 75% success rate while those $35K thru $45K saw 67% success rate.

- What are some limitations of this dataset?

A few limitations with this data set is you don’t see how many backers supported the plays at the throughout the year and at each fundraising price point. It also doesn’t break out the plays by county or geographic region. This could be important details to gauge where to focus your time promoting your play to the right audience of investors. It would also help direct you to the best countries and geographic locations that are the best fit for your play.

- What are some other possible tables and/or graphs that we could create?

It would be good to use a geographic heat map to show both where to promote your play to attract investors and where your target audience population lives. This would be two important factors when deciding what play and where to have your show. It would also be good to look at the subcategories to see how that impacts your launch date and fundraising goals.
