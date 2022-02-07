# Kickstarting with Excel
Help Louise Visualize and Analyze Campaign Outcomes Based on Launch Dates and Funding Goals
## Overview of Project
The project aimed to look at theater outcomes based on launch dates. First, I looked at the theater outcomes by launch date or "years" and later, I filtered by "successful," "failed," and "canceled." Next, I visualized the percentage of succesful, failed and canceled plays based on the funding goal amount based on the "plays" subcategory.
### Purpose
The purpose of this projected was to help Louise visualize how different campaigns fared in relation to their launch dates and their funding goals. With the kickstarter dataset the project aimed to look at their outcomes based on their launch dates and their funding goals.By looking at two analyses -- outcomes based on goals and outcomes based on launch date -- I was able to see that theater outcomes based on launch date are more successful.
## Analysis and Challenges
Overall, the Challenge was simple enough to follow along, especially with the help of the exercises and class exercises. I went back to the other parts of the module to revisit functions that I would need to use for this Challenge.
Most of the challenges I faced was when I was doing the analysis of the "Outcomes Based on Goals". The countifs functions was the challenging part of the exercise. I compared my graph to the graph in the Module 1 Challenge example, and they do not look exactly alike.


### Analysis of Outcomes Based on Launch Date
The Analysis of Outcomes Based on Launch Date shows that this is the most successful way to go. 839 campaigns were successful, 493 failed, and 37 were canceled. 
I completed this analysis by using a pivot table, filtering by category "theater", then by years (grouping months) and finally, I created a marked line chart. 
![Theater_Outcomes_vs_Launch.png](https://github.com/c-ramos/kickstarter-analysis/blob/0208fc746373eeaafea28f2e5026facdcac05b43/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The Analysis of Outcomes Based on Goals shows that this may not be the best approach. 691 campaigns were successful, 335 failed, and none were canceled. 
I completed this analysis by creating a table with headers that looked at goals based on ranges, number successful, number canceled, total projects, percentage successful, percentage failed, and percentage canceled. I then created a pivot table, arranged the x- and y-axis as requested and created a line graph with the findings.
![Outcomes_Based_On_Goals.png](https://github.com/c-ramos/kickstarter-analysis/blob/0208fc746373eeaafea28f2e5026facdcac05b43/Outcomes_Based_On_Goals.png)

### Challenges and Difficulties Encountered
I had some difficulty with the countif's functions. I noticed that my line graph did not exactly match the graph on the module 1 challenge page.
![challenge with outcomesbased on goals.JPG](https://github.com/c-ramos/kickstarter-analysis/blob/0208fc746373eeaafea28f2e5026facdcac05b43/challenge%20with%20outcomesbased%20on%20goals.JPG)

## Results

###- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on my analysis, Outcomes Based on Launch Date shows that are more successful projects than failed, with a low number of canceled projects (37). Out of 1369, 839 projects were successful. Perhaps looking at the entirety of the project length may help Louise look at the canceled projects and explore why they were canceled.

###- What can you conclude about the Outcomes based on Goals?
First, the Number Canceled was zero which is promising. However, when I inspected Number Successful (691 total projects) and Number Failed (335) the numbers do not support that outcomes based on goals is the best way to measure success for Louise's projects.

###- What are some limitations of this dataset?
The dataset does not look at the outcomes based on the length of a project (date created - date ended). It may provide more insight into the success of each project.

###- What are some other possible tables and/or graphs that we could create?
Maybe a stacked bar chart looking at outcomes by length of project versus outcomes based on goals would be helpful.


------------



# An Analysis of Kickstarter Campaigns.
Performing analysis on kickstarter data to uncover trends
With the addition of statistics, Louise will be able to make decisions about her campaign with confidence. These visualizations and analysis will help us research projects similar in scope and type—maybe they have done something right (or wrong), and their specific data will help Louise's project find success.
------
![Outcomes based on launch date](https://user-images.githubusercontent.com/96538067/152728439-da639879-8a48-4a32-9a9d-51d9c9eb62fe.png)
![Parent category outcomes](https://user-images.githubusercontent.com/96538067/152728440-8ba7b200-2691-42aa-9d72-f2380aa8df23.png)
![Subcategory Statistics](https://user-images.githubusercontent.com/96538067/152728441-6fa5b566-a46f-416c-8b37-263c3f60e614.png)

