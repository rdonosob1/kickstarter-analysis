# Kickstarting with Excel
Using MS Excel tool to organize and analyze data to further determine if some specific factors can make a crowdfunding's campaign successful.

## Overview of Project
Louise, an up-and-coming play writer who has been willing to start a crowdfunding campaign to fund her play *Fever*, was too close to reach her fundraising objectives. She's estimating a budget of $10,000 USD, and therefore, she is looking for an data analyst expert to help her analyzing how different campaigns did in relation to their launch dates and their funding goals. 

Thus, a dataset (Kickstarter spreadsheet) has been provided to examine and visualize all the campaign results based on launch dates as well as their funding goals to further generate conclusions and provide recommendations to Louise.

### Purpose
The aim of this analysis consists in helping a playwright professional (Louise), to organize, sort and interpret the data of her theatrical campaign. Therefore, she may be able to determine and mirror her campaign to other successful ones within the same category.

## Analysis and Challenges
This analysis is performed utilizing the Kickstarter data file which contains information about different crowdfunding campaigns within various categories and subcategories. Since this analysis will focus on theatrical campaigns, as detailed before, the first step will consist in filtering the information by categories and thus, selecting all the campaigns under theater category. 

In addition to that, and considering that Louise first intention was to start a crowdfunding campaign to help fund her play, *Fever*. Then, it is really important to compare all the campaigns within the same subcategory "plays". Therefore, the next step will be to filter all the theater campaigns into this subcategory, in order to compare similar campaigns. "Apples" to "apples".

Finally, the last step consists in analyzing crowdfunding data to determine whether there are specific factors that make a project's campaign successful, as well as understanding campaigns from start to finish, to set up Louise's campaign to mirror other successful ones in the same category. In this last step the information will be sorted as detailed below:

  - Outcomes vs launch date to visualize if there is any relationship between outcomes and launch month.
  
  - Outcomes based on Goals to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount

### Analysis of Outcomes Based on Launch Date
To start this analysis, it is important to convert the launch date data into a date format and after that separate the year in a new column.

After that, a pivot table needs to be created from the KickStarter worksheet, showing months on the left column and filtering the column labels to show only "successful", "failed," and "canceled" campaigns. The pivot table is shown below:

![image](https://github.com/rdonosob1/kickstarter-analysis/blob/main/Pivot%20Table%20-%20Theater_Outcomes_vs_Launch.png)

In addition to that, and in order to have a better visibility of the information, it'd be vital to create a line chart "Theater Outcomes Based on Launch Date" to visualize the relationship between the number of successful, failed, or canceled projects by month, the launch date months on the x-axis and the number of successful, failed, or canceled projects on the y-axis. (Line Chart shown below).

![image](https://github.com/rdonosob1/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

It is clear that during the months of May to June there is a peak on the number of successful theater campaigns showing higher results of 111 and 100 successful campaigns respectively, while the contrary is seen during the month of December with only 37 successful campaigns. On the other hand, it is clear that failed and cancelled campaigns fluctuate a little bit, but they tend to be steadier across the year. 
With the previous findings, Louise should focus to launch her campaign between May to June.

### Analysis of Outcomes Based on Goals
Followed the previous step, a new analysis needs to show if there would be a relationship between the goal-amount with the number of successful, failed, and canceled campaigns. Therefore, based on that, it is necessary to develop a table with a dollar-amount-range, so projects can be grouped on their goal-amount. Right after that, the table will calculate the percentage of successful, failed and canceled plays per dollar-range. (Table shown below)

![image](https://github.com/rdonosob1/kickstarter-analysis/blob/main/Pivot%20Table%202%20-%20Outcomes%20Vs%20Goals.png)

Finally, likewise it was done in the previous analysis, it'd be vital to create a line chart "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. (Line Chart shown below).

![image](https://github.com/rdonosob1/kickstarter-analysis/blob/main/Outcomes%20Vs%20Goals.png)

### Challenges and Difficulties Encountered
There wasn't any important challenge or difficulties in this assignment. However, I have never converted before the deadline and launch date data (numbers in seconds) into date formats. 
In addition to that, I can say that the information needs to be sorted out before, and follow all the different previous exercises to have it ready for this final analysis. 

## Results

1) What are two conclusions you can draw about the Outcomes based on Launch Date?
  - It is clear that during the months of May to June there is a peak on the number of successful theater campaigns showing higher results of 111 and 100 successful campaigns respectively, while the contrary is seen during the month of December with only 37 successful campaigns. On the other hand, failed and cancelled campaigns fluctuate a little bit, but they tend to be steadier across the year.
  - With the previous findings, Louise should focus to launch her campaign between May to June. 

2) What can you conclude about the Outcomes based on Goals?
  - A high goal amount may affect the campaign. The analysis shows that projects with goals over $25,000.00 USD are more likely to fail than to succeed, while on the other hand, projects with a lower goal amount are more tend to succeed, specially projects with goal amounts ranging between $1,000.00 to $5,000.00 USD.

3) What are some limitations of this dataset?
  - The data is for the theater and plays categories and subcategories is from 2014 to 2017. Current trends and also after the pandemic, trends may have changed.
  - The data is not discriminating consumers by age, genre, education, religious orientation and beliefs, cultural trends, and other factors.

4) What are some other possible tables and/or graphs that we could create?
The other tables and graphs that may be created for additional analysis are detailed below:

  - Theater Outcomes Based on Deadline, as well as a graph (line chart) titled "Theater Outcomes Based on Deadline" to visualize the relationship between the number of successful, failed, or canceled projects by month, the deadline months on the x-axis and the number of successful, failed, or canceled projects on the y-axis.
  - Outcomes Based on Goal by country to narrow down the information from country to country. Due to each country population needs and likes may respond to different factors such as: demographic, cultural, socio-economic, political, geographical, etc.
