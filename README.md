# Kickstarting with Excel

## Overview of Project
The goal of this project is to use the Kickstarter data to assist Louise in planning her campaign. To do this, the raw data needed to be cleansed and formatted. New subcatogories needed to be created to allow for unique campaign searches. By searching for unique campaigns, I was able to provide specific data that showed which campaigns are the most successful. Finally, these campaigns insights were visualized in a series of pivot charts for ease of interpretation.
### Purpose
The purpose of this project was to provide Louise with data-driven insights to plan campaigns that will be most successful throughout the year. 
## Analysis and Challenges
The analysis began by creating a pivot table based on the outcomes for each parent category. This pivot table was filted on months to understand which months were the most successful based on the corresponding launch date. Although this is helpful for general planning. This was not very useful, as the parent categories did not have enough information to complete successful campaign planning. To resolve this, the subcategory column was created for additional depth. An additional pivot table was created using those subcategories to aid in targeted analysis. 


### Analysis of Outcomes Based on Launch Date
I then analyzed the theater outcomes based on the date in which they were launched. To complete this, I created a pivot table that included the months of the year and the corresponding outcomes. This allows Louise to plan campaigns based on the launch dates that correspond with the highest success rates. See link below for an image of the 'Theater Outcomes Based on Launch Date' chart.
![alt text](https://github.com/GrahamBSereno/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
To understand the correspondance of fundraising goals and success of projects, a table was created to display "Outcomes based on Goals." It was created using bands to classify fundraising goals in a series of ranges. These ranges were analyzed using CountIfs() functions to disect the successful, failed, and cancelled projects in each range. See link below for an image of the analysis chart. 
![alt text](https://github.com/GrahamBSereno/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
I encounted no significant challenges or difficulties were encountered during this analysis. However, one may have challenges writing the lengthly CountIfs() statements required to build out the 'Outcomes based on Goals' pivot. The series of conditionals was tedious and required a lot of accurate manual entry. Also, all conditionals placed in these functions require quotes which is easy to miss. 

Another challenge that one might encounter is adding additional elements to pivot charts in order to provide deeper analysis and additional insights for Louise. Although the project charter guides executers to a series of conclusions, there are additional conclusion that can be gleamed from the data with additional analysis. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The best time to launch a Theater project is between May and June.
2. Music campaigns are launched most successfully in January and May.

- What can you conclude about the Outcomes based on Goals?
1. Campaigns with a fundraising goal between $45,000 to $49,999 have the highest rate of success

- What are some limitations of this dataset?
1. This dataset does fundraising coordinator or person responsible for conducting the fundraising efforts. This is a variable that may contribute to success and should not be ignored. For example, if one fundraising coordinator is more effective, their campaigns may have higher success rates. 
2. The dataset years end in 2017, so the data that I am analyzing might not be representitive of 2022 predictions. 
- What are some other possible tables and/or graphs that we could create?
1. Additional table and associated bar graphs that shows relationship of years (duration of campaign - in range buckets) and campaign outcome.
2. Table that displays the currency type and campaign outcome relationship. 
