# Project 1: SAT & ACT Analysis

## Problem Statement
There has been a change in several changes in the participation rates in both the SAT and ACT exams between the years 2017 and 2018. This report seeks to explore the reasons for these changes within the U.S categorized by states. 

## Executive Summary
First of all errors such as extra characters were rectified and percentages were removed to convert all numerical data in numbers with decimal points. 
Then data was found to match the fields of 2017's data. The cleaned-up data from both 2017 and 2018 were combined to a single data frame for the ease of comparison.  
After that, The standard deviation for each numerical variable was calculated using three different methods. The highest and lowest states were identified in terms of participation rates and scores.  
Histograms, boxplots, heat maps, and scatterplots were used to investigate the data and correlations further.  
Most of the statistics have close to normal distribution. Although the data points add up to more than 30. More data points would further ensure a closer to normal distribution for the numerical variables used in this report.  
Research has been undertaken from the official State Education Departments and other related articles. Some of these include the details of state policies with regards to the compulsory taking of the exams and/or the sponsoring of test fees.  
The states of West Virginia, Ohio, Rhode Island, and Illinois are examples of such policies that greatly impacted SAT participation rates. The SAT day, which happens on a regular school day also contributed to an increase in the overall SAT participation rate.
Focus on collaboration with state education departments, colleges, and high schools would likely lead to a continued increase in SAT participation rates.


## Project Files
Thes data came from this source
- [SAT](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/)
- [ACT](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|:---:|
|**state**|*object*|ACT/SAT|The state in the United States of America|
|**sat_participation or  act_participation**|*float*|ACT/SAT|The percentage converted as a float on the number of student enrolled|  
|**sat_evidence-based_reading_and_writing**|*float*|SAT|The average English reading and writing score in a maximum score of 650|  
|**sat_math**|*float*|SAT|The average Math score in a maximum score of 655|  
|**sat_total**|*float*|SAT|The combined score of sat_evidence-based_reading_and_writing and sat_math|  
|**act_english**|*float*|ACT|The average English score in a maximum score of 26|  
|**act_math**|*float*|ACT|The average Math score in a maximum score of 26|  
|**act_reading**|*float*|ACT|The average reading score in a maximum score of 27|  
|**act_science**|*float*|ACT|The average science score in a maximum score of 25|  
|**act_composite**|*float*|ACT|The average composite score in a maximum score of 25|

## Conclusions
#### Key Takeaways
In the above data, participation rates are incentive by the State Department of Education's policies. The participation rate for the rate would increase if there is a requirement for all students to take a particular test.

Between 2017 and 2018, some states (Colorado, Connecticut, Delaware, Idaho, Illinois, Maine, Michigan, New Hampshire, Rhode Island, and West Virginia) and the District of Columbia covered the cost of the SAT for all their public school students. four years ago, only three states and the District of Columbia did so. This is the implementation of the SAT School Day contributed to the overall 25% increase in SAT test-takers.

#### Recommendations

Firstly, the SAT and ACT would be in terms of a mandatory test in all schools within the state.

Success stories can also be seen in states where the education department subsidizes the full costs of the test, making them more accessible to lower-income students.

Secondly, A college's admission criteria based on either of the tests' scores would have a huge impact on the perceived value of the test. The value to colleges of a single type of test for the admissions criteria is that they have a single metric which they can rank their applicants buy, rather than having to compare their over two sets of metrics

Furthermore, information about the test centers and their usage could also shed some light on the matter. These would help to identify both tactical and strategic targets for the College Board to further improve the SAT participation.
