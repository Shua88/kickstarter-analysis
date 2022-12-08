# Kickstarting with Excel

## Overview of Project

### Purpose
In this project we wanted to help Louise understand where she is at in her fundraising efforts and compare her campaign to others based on their launch dates and funding goals.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    In this excercise we wanted to see the Outcomes of the theatre fundraising efforts, broken down by the months of the year. Whether they were successful, failed, or if they were canceled. We learned, and can see in the chart we created, that there is a spike in success rate in the late spring and summer months. If we were to advise a time for a client to fundraise, it may be best to advise fundraising efforts conincide with those months. 
### Analysis of Outcomes Based on Goals
In this analysis we wanted to drill down to the success rates and failure rates of plays, based on the funding goal amount - something Louise can certainly use as a barometer for her fundraising planning. In general, the best success rates, and also the most common fundraising goals, came from fundraising efforts that were $4999 and under. Goals of less than $1000 were successful 76% of the time and goals of more than $1000 but less than $5000 were successful 73% of the time. 

While the graph and data would show an increase in success rate for the $35,000 to $45,000 ranges, the sample size was much lower. So perhaps if Louise would like to have an ambitious goal in the future for a large play, we can point to past success at these ranges. But as advisors, we would need to share with her that it may be somewhat random, considering there were 11 total projects that had goals of $30,000 to $35,000 but only 3 of the 8 were successful. Much less successful on a percentage basis. In an advisory role I would likely try to group some of the higher goal amounts together to get a better idea of "large" scale fundraising goals for plays.

![Sample Size](Sample_Size.png)


### Challenges and Difficulties Encountered

The main challenge I had was just the Order of Operations on the Goal amounts within the COUNTIFS function. I eventually figured it out with the following order of operations, basically putting the goal amounts back to back in the beginning of the formula. Previously I had it split up, per the example. In which we were possibly supposed to put a "'" single quote to solve it. 

![COUNTIFS Solution](COUNTIFS_Solution.png)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 

One of the conclusions we came up with is that there are more theatre projects that launch in the spring and summer months than the fall and winter months. Generally, we see about a 2 to 1 success to failure rate, but in December we actually saw that it was a 1 for 1 success to failure. This means, generally, you are more likely to fail if you launch in December than if you launch in the summer.

- What can you conclude about the Outcomes based on Goals?

One of the conclusions which I mentioned above as well, is that the success rate is generally higher for any projects with goals of $4999 and less. These amounts were also the most common, had the highest toal projects in their ranges.

- What are some limitations of this dataset?

Perhaps some of the limitations would be that there may not be enough data on some of the higher ends of funding goals for example. As I noted above, there are only 6 projects asking for funding from $35,000 to $39,999, so that may not be enough to get a true sense of success rate.

- What are some other possible tables and/or graphs that we could create?

You can create stacked bar graphs to show the amount of successful / failed / canceled outcomes. Similar to what we did in the modules. You could also show a Pie chart showing successful / failed / canceled outcomes by month or by category. 
