# Kickstarter Outcomes by Launch Date and Funding Goal

# Project Overview
The purpose of this project is to provide an analysis of theater Kickstarter campaigns by launch date and by funding goal. 

# Analysis and Challenges
The analysis was completed using available Kickstarter data. The raw data was manipulated for formatting conversions and moved into Pivot Tables. The Pivot Table data is discussed in more detail below.

## Theater Outcomes by Launch Date
The Kickstarter data was filtered for all theater campaigns and organized by the month the campaign was launched. Each month's launches were then categorized into Successful, Failed, and Canceled outcomes. The results are visualized below:

![image](https://raw.githubusercontent.com/CarlS2rt/kickstarter-analysis/main/Theater_Outcomes_vs_Launch.PNG)

## Outcomes Based on Goals
The Kickstarter data was analyzed across all campaigns to funds plays and organized by campaign goal amounts. Goal amounts were subdivided into $5,000 increments up to $50,0000. Counts for each successful, failed, and canceled play campaign were compiled and then divided by the total number of campaigns to ascertain the percentage of each outcome by 
subdivided goal value. The results are visualized below:

![image](https://raw.githubusercontent.com/CarlS2rt/kickstarter-analysis/main/Outcomes_vs_Goals.PNG)

## Challenges
The only challenge to overcome in the data was that the time data from Kickstarter was stored as a Unix timestamp. To utilize that data for assessing outcomes by launch date, the Unix timestamps were converted via formula to a standard data that Excel could recognize. No other challenges arose from the dataset.

# Results
* From the data on Theater Outcomes by Launch Date, there are several clear conclusions. First, the most successful time of year to launch a campaign is May, followed closely by June and July. Overall, starting in the late spring and early summer provides a much higher chance of success than starting a campaign at any other time of the year. The next conclusion is that the number of failed campaigns does not fluctuate much throughout the year, so the reason campaigns fail does not strongly correlate with time of year and must have other causes. 
* From the data on Outcomes Based on Goals, there is a negative correlation between higher campaign goals and successfully reaching that goal. Similarly, there is a positive correlation between higher campaign goals and failing to reach that goal. 
* Some limitations of this dataset are that it does not explaing why the success rate increases from $35,000-$40,000. There are likely other contributing factors not captured in this analysis. Additionally, this dataset does not analyze the average pledge in successful versus failed campaigns to determine if pledge amount greatly influences a high percentage of successful outcomes. 
* Other possible tables and graphs that could be presented here would be average pledge based on goal amount. It would also be useful to account for variations in outcomes by launch data and by goal over time, especially by year. 
