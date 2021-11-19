
# ** PyCity Schools Analysis**

## Overview of Schools analysis

-The purpose of this project it to apply all that we learned in the module 4, in the Data analysis and visualization  Boot camp of the University of Texas at Austin.
During the this module we had the opportunity to learn the Pandas Libraries for Python. 

During the module I worked with data of  Math and reading Scores  15 schools getting very interesting insights such as averages scores and average passing % and grouping data by school, grades, Spending Type, School type, School size.

For this challenge of the module 4 ,  I was requested to run the same analysis I did during the module 4 activities but  this time I had to remove the records of the 9th graders of Thomas High School and see the differences in  insights

	
## Results

-  We can identify the changes in the final numbers after removing the 9th graders. I will show the details  below.

### How is the district summary affected?

Below you can see the changes in the numbers for the “District summary”


- <img src = "Resources/disctrict-summary.png" width= "400" >

### How is the school summary affected?

Specifically for the Thomas High School, we can see the image below that after removing the  9th graders  numbers were:

Average math Score, lower
Average reading score. Slightly higher
% Passing Math : lower
% Passing Reading: lower
% Overall Passing: lower

- <img src = "Resources/school_summary.png" width= "400" >

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Ranking wise, the data eliminated did not change the position of  Thomas High School 

-For Math score  where the average score las lower , the schools keeps its 13th position 

-For the Reading  score, where the average score was a bit higher , the schools keeps its 5thth position 

-For the overall % passing score:  where the average % was bit lower, going from %90.9 to %90.63 The school keeps its 2nd position


### How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade
Only the 9th grades data changed
- <img src = "Resources/grades_summary.png" width= "400" >

Scores by school spending
Only the $630-644 group was affected by the change in data
- <img src = "Resources/spending_ranges.png" width= "400" >

Scores by school size
The medium school size group was affected.

- <img src = "Resources/school_size.png" width= "400" >

Scores by school type
The Charters type was impacted 

- <img src = "Resources/school_type.png" width= "400" >



## PySchool Analysis Summary

Thanks to the analysis we could have with the data provided, we can see 5 metrics were impacted with the 9th graders change. Total students and Total Budget remain unchanged.

See image below


- <img src = "Resources/7_metrics.png" width= "400" >

We can also identify the 4 most important changes. See image below

- <img src = "Resources/major_changes.png" width= "400" >

	

