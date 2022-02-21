# Kickstarting with Excel

## Overview of Project
This project was used to see how well students can apply the material they just learned. Students were learning viewing data, using pivot tables/charts, using filters, and applying statistics and visualization techniques.

### Purpose
The purpose of this project was to familarize students to basic excel practices:
1. Pivot Tables
2. Visualization of Data
3. Formulas / Functions

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](C:\Users\becer\Desktop\THE_classfolder\Resources)? (path/to/Theater_Outcomes_vs_Launch.png)
From the figure above we can identify that theatre fundraisers that launched in May were much more successful than any other month.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals]
From the figure above we can recognize three points where the successful and failed lines intersect. 

### Challenges and Difficulties Encountered
There was one challenege that I encountered that had me stumped for quite a while, and that was which sign to use when making a range within the COUNTIFS function. After a while of aimlessly looking at the screen, I just tried flipping '>' for '<' and I realized that I just need to read the sign in the order it is typed. Example: ">1000" --> greater than 1000 rather than "<1000" less than 1000.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	- As stated above, fundraiser goals that were launched in May were much more successful than any other month.
	- December is the month with lowest ratio of success to failure, with 50% chance of success and 50% chance of failure. Even October that has the highest failed amount of theatre fundraisers has a higher chance of succeeding.
- What can you conclude about the Outcomes based on Goals?
	-This shows varying ranges of success based on ranges of fundraising goals. According to the graph, any goal less than ~$12500 has at least a 50% chance of success; as well as, any goal between the range ~$28000 > x < ~$42000 also has at least a 50% chance of success.
- What are some limitations of this dataset?
	- The "Outcome vs Goals" graph only shows fundraising goals and outcome percentages, so it is possible that there are a variety of other reasons for failure or success.
	- Similarly with the "Outcomes Based on Launch Date" graph only takes into account the subcategory and month it was launched in. 
- What are some other possible tables and/or graphs that we could create?
	- Stacked bar graph of all theatre fundraisers to see which subcategory was the most successful.
	- Can make line graph Successful Plays vs Launch, and make the y-axis percent funded, so it could be compared across all countries. 
