# kickstarter-analysis
## Objective:
The objective of this project was to provide our client Louise with a detailed analysis of kistarter campaign data, so she could achieve her crowdfunding goals and start her play _Fever._ We used a variety of analytical tools to best sort and visualise the data so Louise's campaign could be successful.

## Analysis and Challenges:
### Theater outcomes versus launch date:
We started our analysis by creating pivot tables and pivot charts so we could easily filter the data that most closely matched Louise's project.  The first filters we applied allowed us to visualize the number of successful, failed, and canceled projects based on the month of the year they were launched.  The line graph [Theater Outcomes based on Launch Dates](https://github.com/kowiak89/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png) shows this data.  From this graph we can see that the number of successful campaigns increases in the summer with a Peak of 111 successful campaings in May, and decreases in the winter with a trough of 37 in December.  At first glance this might seem like the best time to launch a successful campaign would be in May, however we can also see that the number of failed campaigns also peaked in May.  Perhaps the reason May had the most successful campaigns was due to the fact it was the month in which the most campaigns were launched?  A further look into the data is required to pull out any confident conclusions.

In another attempt to uncover whether launch date affected the outcome of the campaign we compared the number of successful campaigns to the number of failed campains based on launch month.  We took the difference from each month's number of successfull and failed campaigns.  We then graphed that data in a box and whisker plot called [Difference Between Successful and Failed Campaigns](https://github.com/kowiak89/kickstarter-analysis/blob/main/Difference_between_successful_and_failed.png).  We can see that the months of May and December are both outliers.  This result may indicate that launch date is an important factor for these two months.

### Outcomes based on campaign goals:
We then continued our analysis by investigating the relationship between successful, failed, and canceled campaigns based on their campaign goal.  We consolidated the data into blocks starting at campaigns with a goal of <1000$ and ending with campaigns with a goal of >50,000$.  This data can be viewed in the Outcomes based on goals tab of the excel spreadsheet.  Once we had the total number of successful, failed, and canceled campaigns for each block we could calculate the total precentage each outcome had for that block.  We then graphed those percentages in the [Outcomes based on goals](link) line graph.  From this graph it is hard to see any conclusive evidence that the campaings goal had any influence on the outcome of that campaign.  

### Challenges:
The main challenges in this analysis was the lack of more comprehensive data.  More specific data such as who started the campaign and how much experience do they have, or where in the country were the campaigns being launched, would provide more confident analysis.  


