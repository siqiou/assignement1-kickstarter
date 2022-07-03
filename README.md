# assignement1-kickstarter
# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to help Louise find out the outcomes of Crowdfunding based on launch date and funding goals, so that she could use the result to make future business devisions on setting approriate goals and reasonable launch times.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Outcomes_vs_Goals.png](/Theater_Outcomes_vs_Launch.png)
The highest number of Theatre projects were launched between May and July, the projects were mostly likely to be successful in May and June. Number of failed projects spread out evenly throughout the year, January had the most number of cancled projects.

### Analysis of Outcomes Based on Goals
![Theater_Outcomes_vs_Launch.png](/Outcomes_vs_Goals.png)
There are total 1046 projects in the palys subcategory, almost half of projects had goal between 1000 to 4999. 
By looking at the precentages, the higher the goal, the higher the percentage failed. Successful projects are mostly in the range of less than 1000 and 1000 to 4999, with 76% and 73% among all projects. There are 2 67% succesfuls in the higher range of goals, 35000 to 39999 and 40000 to 49999, but the total projects are too small, we cannot rely on this data.

### Challenges and Difficulties Encountered
The only challenge encountered was when we had 0 successful projects based on goals, the percentage calculation was showing an error. To make sure only numbers are showing in the chart, the IFERROR function was used.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. It is better to launch projects in the summer, ideally betweeen May and June.
2. Projects may fail any time of the year, but December has the lowest number of succesful projects, it is suggested to avoid launching at the end of year.

- What can you conclude about the Outcomes based on Goals?
The smaller the goal, the higher the successful rate. Setting a goal less than 5000 would have the highest chance of succes.

- What are some limitations of this dataset?
This dataset only shows relationship between launch date and goals, there could be other factors contributing to successful of projects, we can take a look at if there are backers, and what was the amount pledged.

- What are some other possible tables and/or graphs that we could create?
The projects was spread over several years, it would be great if we could create a large graph to show the trends over time, so we could connect with some external factors and better analyze the outcomes.
