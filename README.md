# Crowdfunding Analyis using Excel :chart_with_upwards_trend:

## Overview of Project

### Purpose
This document focuses on the use of organization and data analysis to examine the results of a data series throughout the main spreadsheet named "Kickstarter". Filters, pivot tables, formulas, line and bar graphs, analysis of variance, standard deviation, etc. were used to carry out the analysis of the proposed Crowdfunding dataset. See the next heading to visualize the Crowdfunding analyisis on detail.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The outcome of this analysis shows the following:
![](https://github.com/Frankdiazw/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)

*Figure 1. Outcomes Based on Launch date*

In figure 1, three lines can be seen along the horizontal and vertical axes. We can observe along the linear graph, the count of outcomes as a function of time *f(t)*(which in this case are the twelve months of the year). The graph in figure 1 can be interpreted as follows:
- **Successful Outcomes (Blue line)**
  - According to the successful outcomes of the theater subcategory during the months of January to December, the outcomes show that in January began with a count of 56 successful results, from there the graph varied a little in the months of February to April.
The graph reached its peak in the month of May with a count of 111 successful outcomes and from there began to decrease until September with a count of 59 successful results.
In the month of October, the counts slightly increased and then decreased again until December with a final count of 37 successful results.
- **Failed Outcomes (Red line)**
  - For the failed outcomes of the theater subcategory counts, a more stable graph can be observed compared to the successful outcomes.
Starting with 33 failed outcomes in the month of January you can see a small variation in counts through the month of April.
Again in the month of May it reached the highest peak with a count of 52 failed results and from that month the graph stabilizes a bit until the month of August. In the month of September, a decrease in the graph can be observed to reach a count of 34 failed results. Another gently increase is observed in the month of October and the greatest decrease of the entire graph in the month of November, dropping to 31 failed outcomes and for the month of December the count ends with 35 failed results.
- **Canceled Outcomes (Yellow line)**
  - On this outcomes we can see the lowest counts of the three results. We start with the peak of cancelations in the month of January with a count of 7, from then through the month of september we can barely see a variation of counts. On the month of october we can see that the graph decreased to the lowest point with 0 counts and slightly increased in the month of november and december with 3 canceled outcomes.

### Analysis of Outcomes Based on Goals
The outcome of this analysis shows the following:
![](https://github.com/Frankdiazw/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

*Figure 2. Outcomes Based on Goal*

In the figure 2, we can visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. We can see that the graph shows on its "y" axis the percentage rate and in the "x" axes the dollar-amount ranges of projects based on their goal amount. The graph in figure 2 can be interpreted as follows:
- **Percentage Successful (Blue line)**
  - According to the Percentage Successful trend, It can be seen in the outcomes, that in the first range of dollar amounts that is less than $ 1000 it can be seen the peak of the graph with a 74.9% success percentage. The next range from $ 1000 to $ 4999 shows a small decrease going down to 72.66%, to drop more sharply in the range of $ 5000 to $ 9999. Subsequently, the graph decreases slightly until it reaches a 45% success rate in the range of $ 20,000 to $ 24,999 and drops sharply to 20% in the next range. In the range of $ 35,000 to $ 39,000 the graph shoots up to 66.7% and holds until it falls to 0% success rates in the range of $ 45,000 to $ 49,999. To subsequently increase to 12.5% in the last range of greater than $ 500,000.
- **Percentage Failed (Orange line)**
  - In the Percentage Failed line, we can observe a good start with a lower percentage rate than the Succesful rate with a 25% in the range of less than $ 1000. The Percentage Failed almost doubles up in the range of $ 5000 to $ 9999 and slightly increasing up to 55% in the range of $ 20000 to $ 24999. We can see a rise of the percentage to 80% in the $ 25000 to $ 29999. The line decreases significantly to 33%, to remain unchanged on the range of $ 40000 to $ 44999. The line unfortunately hits the peak of 100% on the range of $ 45000 to $ 49999, to decrease to 88% on the last range.
- **Percentage Canceled (Gray line)**
  - In the Percentage Canceled line, the line didn't vary in any range, the percentage remained in 0% in all the ranges.
  
### Challenges and Difficulties Encountered
During the Crowdfunding Analysis, no challenges were presented, however some users may experience syntax and semantic errors. Therefore, it is recommended to review the following links to avoid future errors:
- :calendar: [YEAR function in Microsoft Excel](https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9)
- :information_source: [PivotTable](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576)
- :hash: [COUNTIFS function in Microsoft Excel](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842)
- :heavy_plus_sign: [SUM function in Microsoft Excel](https://support.microsoft.com/en-us/office/sum-function-043e1c7d-7726-4e80-8f32-07b23e057f89)
- :information_source: [Syntax guide for GitHub](https://guides.github.com/features/mastering-markdown/)

## Results
### Theater Outcomes by Launch Date
In this segment of the Crowdfunding Analysis, the objective was to use the knowledge acquired during the class to organize and visualize the "Successful", "Failed" and "Canceled" outcomes of the "Theater Outcomes by Launch Date" campaign.
- Two conclusions can be determined from this campaign.
1. The first, during the course of the campaign, the results of the theater category (successful, failed and canceled) were filtered by release date, and counted in order to make a graph. Using excel formulas to carry out this process, this is very useful because for a true analysis of data it is necessary to organize the data to be able to visualize it correctly and also other functions such as pivot table and the use of graphs to make it more clear for the user.
2. The next conclusion of this analysis is that the success result was greater than the error and cancellation result, especially in the month of May where it had the highest point in the graph, but also had the highest point in the failure result, this tells us that this month there is a greater movement of results than in the other months of the year. However, in the month of December we did not see good results, since it was the month with the least successful results, but a month earlier in November it was observed that it was the month with the fewest unsuccessful results. As for the canceled results, they were very few with a maximum of 7 in the month of January (the highest) and their best point was in October with 0 canceled results.

### Outcomes Based on Goals
On this Outcomes, the objective was to use the Excel skills learned in the class to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. During this analysis we were asked to use the "COUNTIFS ()" functions to be able to filter and count the "Successful", "Failed" and "Canceled" results of the "plays" category based on the goals established by the Crowdfunding analysis. It can be seen that at the beginning of the graph there are more successful outcomes than any other up to the range of $ 15000 to $ 19999 where the line intersects with that of failed outcomes. From then on, it is observed that the failed results line outweigh the successful ones up to the last range (with the exception of the ranges $ 35000 to $ 39999 and $ 40,000 to $ 44999). Thanks to this analysis, the knowledge acquired in the first module of the bootcamp could be tested and applied in a satisfactory way.
