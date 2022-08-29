#  Kickstarting with Excel

## Overview of Project
A thorough analysis was performed to provide insight into comparing different Kickstarter campaigns in relation to their respective launch dates and campaign goals. Multiple variations of analysis took place in order to provide understandable data and evaluate how other Kickstarters compared to Louise’s campaign.   

### Purpose
The objective of this analysis is to deliver Louise as much possible understanding towards the arrangements of different campaigns regarding their launch dates and funding goals. Creating different visualizations provide interpretation of how other campaigns differ from Louise’s campaign regarding her play Fever. 

## Analysis and Challenge
Regarding how Kickstarter campaigns fare in relation to their launch date and how successful they will be, the analysis exhibited how few months of the year had the best outcomes, unlike failed campaigns which seemed to be more consistent throughout the year. The goals of these different campaigns give much insight on how keeping a much lower goal fared much better than arranging a very high end goal. In perspective, beginning a Kickstarter with a low goal and starting during specific periods resulted in better outcomes than otherwise. Many challenges were faced as organizing the data and ensuring the correct formats were used, became a hardship as I have little experience with Excel functions.

### Analysis of Outcomes Based on Launch Date
In order to perform this analysis, I first had to create a table regarding all successful, failed, and canceled campaigns and compare them to their dates by month and all years. Theater based Kickstarters that began in the months of May and June proved to have the highest success rate unlike the month of October. Although failed campaigns occurred consistently throughout the entire year, October fared to be amongst the worst months along with June, July, and May. Despite May being the one of the leading months of most successes, it also had the most failed campaigns with 52 failures compared to 111 successes. A trend of the most successful months also being the months with most failures amongst others is displayed on a line chart below. With this visualization, one can concur that during the first half of the year, campaigns will have the greatest possibility of being successful, although there are also multiple possibilities of failure.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111406957/187168579-3b95d4c0-af89-49bf-968e-0a05c59f5dff.png)


### Analysis of Outcomes Based on Goals
To analyze the outcomes of different campaigns and how their goal affected them, I first had to isolate the amount of successful, failed, and canceled campaigns for plays and compare them to their respective goals that were set. After gathering all data, I then compared the prospective numbers against total projects in order to calculate the percentage of all possible outcomes. This analysis showed that there were no canceled play campaigns regarding their goals. The amount of successful campaigns were much higher when the goal was set under $20,000. There are only a few successes that surpassed the previous mentioned goal ranging from 9 to 0 successful play campaigns. The goal with the highest percentages of failures occurred at the ranges of  $50,000 or more, $45,000 to $49,000, and $25,000 to $29,000. The chart below displays how the outcomes based on the goal amount of these different campaigns vary the most at the highest and lowest amount of goal.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111406957/187168653-097629ec-eefa-45e3-b6a1-6061d7facd4d.png)


### Challenges and Difficulties Encountered
Some challenges and difficulties were encountered while writing specific functions for the outcomes based on the goal of the campaign. I had multiple challenges when collecting the data for the number of successful, failed , and canceled campaigns based on their goal. Using the COUNTIFS() function proved to be difficult as I was trying to filter the outcomes, but kept obtaining the same incorrect result. After much thought on how to filter the outcomes, I ended with using the COUNTIFS() function to narrow down the criteria range and criteria. I used the Excel help page to help me better understand how to use the COUNTIFS() function. Using the [Excel Functions](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ns=excel&version=90&syslcid=1033&uilcid=1033&appver=zxl900&helpid=xlmain11.chm60529&ui=en-us&rs=en-us&ad=us) link, I was able to resolve most of the issues I faced. This made the function much longer, but it helped me obtain the best results as I was able to manipulate the criteria to successful, failed, and canceled as needed. Another difficulty I faced was when trying to convert the results into percentages. My mistake began when I attempted to write the correct function, but multiplied it by 100 which proved to make the percentage incorrect. After resolving that issue, I then was able to convert it to a percentage using the format options.

## Results
Two conclusions I can concur regarding the Theater Outcomes by Launch Date is that most successes in these Kickstarter campaigns occurred in the first half of the year, and with more successes also came a slightly higher chance of failure. In respect to Outcomes based on Goals, I conclude that one has a greater chance of failure when the goal is much higher than their prospective successful goals. The limitations of this dataset analysis include how it only reflects the outcomes of plays and not all categories that were provided, and how the amount of what was actually raised was not included in the final dataset. Other possible tables or graphs that can be used to help visualize the outcomes include a chart displaying the amounts that were pledged, and a table focused on the dates the campaigns were created and ended, in order to prove more in depth understanding to the timelines. 
