# Kickstarting with Excel

## Overview of Project

### The following is an analysis on data collected from different Kickstarter campaigns that have been made from 2009 until now. This analysis focus on two main points: The outcomes of the plays in the data set based on their fundraising goal and the outcomes of all the theater projects based on their launch date. The results present a close idea of what are the best dates (on average) to launch a fundraising campaign for a theater project and what is the average success rate when compared to the goal range.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date:

Looking at the graph of Outcomes vs Launch Date, is clear that the theater projects which their fundraising campaign is launched among the months of February, April, May, June or July have a better probability of reaching their fundraising goal, being May the month with the largest success rate (67%) and also the month with the most theater campaigns launched which makes the data representative. On the other hand, the theater projects launched on October or December have a greater possibility of failing to reach their goal (being December the worst with a rate of 47%). Even though there are not many cancelled Kickstarter campaigns for the theater projects (close to 3%) the month with the most cancellations is January with 7 campaigns (7% of the total campaigns launched on that month).

The graph of Outcomes Based on Launch Date is as follows:


![This is an image](https://github.com/HansFeddersen/Kickstarter-Analysis_HF/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

  
  
### Analysis of Outcomes Based on Goals: 

For this analysis, only the projects that were plays are considered. Looking at the data, is possible to see that the goal range that has the best success rate is the one that goes from 0 to 999 (different currencies according to country of the project) with a 76%, followed very closely by the plays that have a goal between 1,000 and 4,999 with a success rate of 73% but with 3 times the projects of the first one. Also the range 1,000 to 4,999 represents close to half of all the plays that had a Kickstarter campaign. For the plays that had a goal from 15,000 to 49,999 the success and fail rates have many differences, but that range represents less than 10% of the projects so all the conclusions that can be drawn from there are subjected to a big variability as more data becomes available. A different thing occurs in the plays which their goal was equal to or more than 50,000, because of the 16 campaigns launched only 2 were successful. At the end, is important to point out that 66% of all the plays were successful and not a single one was cancelled.

The graph of Outcomes Based on Goals is as follows:


![This is an image](https://github.com/HansFeddersen/Kickstarter-Analysis_HF/blob/main/Resources/Outcomes_vs_Goals.png)

 
### Challenges and Difficulties Encountered

**The data was completed and contained no errors, so there weren't that many difficulties on that side.**

**There is one challenge that needs to be taken into consideration:**

- When talking about the range of the fundraising goals for each campaign, it is necessary to convert everything to the same currency (if not, we are grouping data that should not be grouped together and the analysis could contain big mistakes)

## Results

**What are two conclusions you can draw about the Outcomes based on Launch Date?**
- If someone is planning on launching a Kickstarter campaign for a theater project, the recommended month to do it would be May but February, April, June and July are also options to consider. The least recommended would be December.
- The campaigns launched in October are less likely to be cancelled, but is not recommended to launch on that month due to the fail rate (which is close to that one of December).

**What can you conclude about the Outcomes based on Goals?**

- For plays, the less the goal the more probability that the Kickstarter campaign is going to be successful (reach its goal).

**What are some limitations of this dataset?**

- The Dataset does not contain information about the reason for cancelation of the projects. With a few reasons categorized, one could understand why were the projects cancelled and make some decisions for the future.
- The Dataset does not contain all the countries, so if one would want to analyze Kickstarter campaigns of countries that are not considered here, it would not be able to do it using this Dataset.
- Not up to date. The last campaigns are from 2017 and there are still a few campaigns labeled as live but should have been closed long time ago.

**What are some other possible tables and/or graphs that we could create?**

- Duration of the campaign vs Outcome
- Parent Category vs Backers Count
- Subcategory vs Backers Count
- Duration of the campaign vs Backers Count
- Outcomes vs Backers Count
- Average donation per Category
