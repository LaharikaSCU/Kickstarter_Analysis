# **Kickstarting with Excel**

## **Overview of Project**

 Analyze Kickstarter dataset to help Louise with launching her fundraising event 'Fever' successfully. 

## **Purpose**

 The Kickstarter dataset was used to analyze the launch dates & funding goals of different campaigns and help Louise understand how different campaigns fared in relation to launch dates and goal amount. Further, this would help Louise decide on the best launch date and an optimal goal amount for her fund raising event to be successful.The analysis combines launch dates, funding goals of different campaigns and uses charts to visualize the outcome.

## **Analysis and Challenges**

### Analysis

 'Launch dates' and 'Goal Amount' were utilized as the main attributes to drive the analysis. Further 'theatre' specific data was filtered, to extract outcome trends for all years in the dataset, thus establishing most successful months for the launch of different campaigns. To determine outcome based on goal amount, project goals were grouped in the dollar amount ranges, calculated number of projects in each category of success, failed and cancelled respectively, their percentages were used to chart and determine the goal amount range with most successful projects.
 
### Challenges 

 Few columns in dataset needed conversion and extraction. For example, launch dates in the dataset had to be converted from UNIX timestamp to extract year using excel YEAR() function. Also, there were few outliers in the goal amount(descriptive statistics) but weren't show stoppers as they were minimum. But, more the outliers, more difficult it would have been to analyze.

## **Results**

### Analysis of Outcomes Based on Launch Date

 The data analysis along with pivot tables and visualizations created for 'outcomes based on launch date' tells us that the events launched in the months of May and June were successful. Further, the campaigns launched in the month of December does not seem to fare well.

### Analysis of Outcomes Based on Goals.

 The outcome established that the projects were most successful with a goal amount of $5000 or less. Hence, lowering the goal amount might help Louise in launching the campaign successfully.  

### Challenges and Difficulties Encountered

 Some of the topics were new and challenging like descriptive statistics application, CountIfs() & their application in our analysis. But, with the detailed explanation of each application I could master it and successfully complete the challenge-1. 

### limitations of dataset

 It would have been nice to have more data to reason the outcomes. For example, what additional factors favored the projects to be successful in particular months of a year like location, weather, number of people attended and their demographics, etc. 

