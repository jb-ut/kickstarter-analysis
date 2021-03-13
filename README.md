# An Analysis of Kickstarter Campaigns

## Overview of Project
Louise's play *Fever* was just shy (86% to target) of her fundraising goal and ended her fundraiser in just under a month. Now I want to help her better understand how different campaigns fared in relation to their launch date and fundraising goals.

### Purpose

I will be looking at a Kickstarter data set that includes the results of various types of fundraisers. In order to provide Louise with relevant insight, I will be limiting my analysis to **theater** parent category and the **plays** subcategory.
 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

Based purely on launch date and limiting the parent category to only theater there is some evidence that fundraisers that launched during the summer months (May - Aug) fared better than fundraisers other periods of the year. 
    
Looking at the chart titled “Theater Outcomes Based on Launch Date” we can see a spike in success of fundraisers beginning in May where it peaked at 111 successful fundraisers. During May – Aug the average number of success fundraisers was 72 vs. 59 for all other months. Fundraisers launched during May-June also accounted for 44% of all successful fundraisers.

Interestingly, we can observe that the number of failed fundraisers was mostly flat during the entire year and exhibited less volatility than the number of successful campaigns.

Based on launch date alone it appears that while there are a higher number of success fundraisers that launched in the summer there are like other contributing factors to launching a successful kickstarter campaign.

![image](https://github.com/jb-ut/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Looking at the impact of goal size and the success rate of kickstarter campaigns we will turn our focus to specifically to plays.
We observe the following:

- Fundraisers with a goal of “Less than 1000” and “1000 to 4999” both had success rates of over 70%. 
-	We see the success rate drop closer to the 45% - 55% range when the goal increases. We can see a 50/50 success for goals within these tiers: “5000 to 9999”, “10000 to 14999”, 15000 to 19999”, and “20000 to 24999”.
-	Once the goal breaks the 25000 barrier, we see the failure rate increase dramatically. While there are a few outliers, the failure rate for higher fundraisers budgeted over 25000 reaches rates as high as 100% and is consistently over 70% for four of the six tiers above 25000. 
It is important to consider the sample size from the data. While there was some success at fundraisers with goals of over 25000, there is a much smaller pool of data to cull from. For example, when looking at the success rate for fundraisers budgeted at less than 5000 we were able to pull from a sample of 720 projects vs. just 42 total completed projects for fundraisers with a goal higher than 25000.

![image](https://github.com/jb-ut/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered 
During the analysis there were some challenges encountered. 

The analysis asked for the creation of line chart for observing the “Outcomes Based on Goals” trends. I had difficulty reading the chart and felt that a clustered column might be a better fit to analyze the data.

I created a new chart and formatted the data to show green for successful campaigns and red for failed campaigns. This helped me more easily read and interpret the chart and I am including it for reference. 

![image](https://github.com/jb-ut/kickstarter-analysis/blob/main/Outcomes_vs_Goals-supplemental-chart.png)

### Results

##What are two conclusions you can draw about the Outcomes based on Launch Date?

Looking at the Outcomes Based on Launch date we can reach two conclusions:
1.	Fundraisers in the theater parent category that launched in summers months (May – Aug) accounted for nearly half of all successful campaigns.
2.	Failed campaigns were essentially flat during the entire year.

##What can you conclude about the Outcomes based on Goals?

Looking at the Outcomes Based on Goals data we can reach the following conclusions:

-Goals with budgets of less than 5000 have a success rate of above 70%
-Goals above 5000 and less than 25000 will have a success rate in the range 45% -55%
-Going above 25000 will have high likelihood of failure likely above 70%

I recommend launching future campaigns in the summer months and with a goal under 25000.

##What are some limitations of this dataset?

The data set has a few limitations. As I mentioned, there were some outliers for the success rate of campaigns with a budget greater than 25000. Two out of the three campaigns with a goal “40000 to 44999” succeeded. Because of the small sample I would caution against setting goals in this tier. 

A data set that included the number of prior campaigns run by an individual would be interesting to see and it would be interesting the know the average goal of prior campaigns. My thought is those outliers could potentially be organized by individuals with prior experience of producing plays and maybe that experience factored into them reaching goals in this tier. 

##What are some other possible tables and/or graphs that we could create?

I am including another chart that helped me create this analysis in the *Challenges and Difficulties Encountered* section. Additionally, another chart that would be interesting to see would be the average donation of size of campaigns based on their goal target.

Another chart could look at the average number of days a success campaign ran by goal target. Louise missed her target by only 14%, but concluded her campaign in under an month. It would be interesting to see how long successful campaigns normally run. Perhaps then I could advise on extending her campaign length.
