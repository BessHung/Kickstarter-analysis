# Kickstarting Analysis with Excel

## Overview of Project
This project is requested by a playwright, Louise, who is starting her first fundraising campaigns for her play Fever. We have a dataset of kickstarter campaigns from 2010 to 2017, it contains every campaign detail such as goal, pledged, country, outcome, period, categories, etc. And now, Louise wants to know the outcomes of Theater and Plays based on their launch date and goal.

### Purpose
The objective of this project is to provide Louise relation of the campaign’s outcomes based on their launch dates and funding goals from the kickstarter dataset.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![](/Resources/Theater_Outcomes_vs_Launch.png)

This line chart is performing the outcomes of category of theater based on the launch. From this analysis of data, we can apparently know that May is the most successful month to launch, which hits 111 campaigns. From June to September, the successful campaigns are getting decreasing. Moreover, the least successful month is in December, which is 37 campaigns. On the other hand, the most failed campaigns in all months is May as well, which is 52 campaigns, but it’s little different than the other months. Overall, there are 166 campaigns (exclude canceled) launched in May which is the highest months.
### Analysis of Outcomes Based on Goals
![](/Resources/Outcomes_vs_Goals.png)

The graph shows the information about the percentage of category “Plays” outcomes in different goal ranges. It can be seen that the rate of successful is greater than the rate of unsuccessful when the goal is under $19,999. Especially the goal below $4,999 has the rate more than 70%. Besides, the successful rate between the goal of $35,000 and $44,999 is higher than unsuccessful rate as well, which is 67%. Thus, we can assume that it may have other influential factors for the successful campaigns which their goal is between $35,000 and $44,999.
### Challenges and Difficulties Encountered

From the kickstarter dataset, the format in the column of lunch date is using Unix timestamps. To make it easy to ready and analyze, I use the formula to convert the value to readable format “yyyy-mm-dd”. Besides, the category and subcategory are in the same column, in order to look into the performance of specific sub categories such as Plays, I use excel function to separate category and subcategory in different columns.
## Results
The conclusion from Analysis of Outcomes Based on Launch Date:
- The most successful launched month is happened in May for the theater fundraising campaigns.
-	The 4th quarter is less successful for the theater fundraising campaigns launched, especially in the December.

The conclusion from Analysis of Outcomes Based on Goals:
-	The high rate of successful for the Plays goal is not only happen in the lower amount (under $4,999) but from the goal $35,000 to $44,999. They both have roughly 70% successful rate.

The limitations of this dataset:
-	The kickstarter dataset only contain the data from 2010 to 2017, without the latest data that we don’t have more recent insight.
-	The goal and pledged in the dataset are concluded, we are not able to see the detail of the funding coming from. So, we can’t analyze further to find out the exact reason of the successful or failed outcome.

Recommendation for additional tables or graphs:
-	It would be better to display the distribution of the dataset and realize the correlation between outcomes and goal. Based on their outcome, we can calculate the measures of central tendency such as mode, median, mean as well as the measures of spread include range, variance, standard deviation, and quartiles. Furthermore, we create a graph, box plot, to illustrate those measures.
