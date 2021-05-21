# **Problem Statement**

Many headlines were made saying that in 2019 there was a decrease in percentage of students who gave SAT compared to ACT which led to people suggesting to stop conducting SAT altogether and focus on ACT which resulted in college board forming a committee to check the same.\
This analysis seeks to explore if the headlines made were true , if so what are those states and possible  reasons behind that.\
This analysis also aims  to make recommendations to the College Board for strategies to improve participation rate

# **Summary**

## SAT 2019 Data Import and Cleaning 
Errors such as missing values were fixed \
Percentage symbol was removed and converted the datatype to float \
Two rows containing missing values were deleted \
Created New Column called "sat_score_percentage" \
Renamed column names

## ACT 2019 Data Import and Cleaning

Percentage symbol was removed and converted the datatype to float \
Unwanted row was deleted \
Created New Column called "act_score_percentage" \
Renamed column names

## Exploratory Data Analysis

The standard deviation was calculated using two different methods. \
The highest and lowest states were identified in terms of participation rates and scores. \
States with more than 50% participation in SAT and ACT  
States with more than 50% participation and more than mean score in SAT and ACT were identified

## Data Visualization

Histograms, boxplot, heat map and scatterplots were used to analyze the data and correlation

## Outside Research

Below are few articles that I have referred :\
[**North Carolina subsidizing cost of ACT readiness exam**](https://www.dpi.nc.gov/news/press-releases/2019/09/24/north-carolina-widens-lead-nation-sat-exam![image.png](attachment:image.png))\
[**11 districts that subsidize full cost of SAT Test**](https://reports.collegeboard.org/archive/sat-suite-program-results/2019/benefits-sat-school-day#:~:text=In%202018%2D19%2C%2010%20states,than%20200%20school%20districts%20nationwide.![image-2.png](attachment:image-2.png)\))\
[**Regional Affiliations**](https://www.collegeraptor.com/getting-in/articles/act-sat/act-vs-sat-which-college-entrance-exam-is-more-popular/#:~:text=Short%20answer%3A%20there's%20no%20preference,BOTH%20the%20ACT%20and%20SAT.![image-3.png](attachment:image-3.png)\))\
[**ACT**](https://en.wikipedia.org/wiki/ACT_(test))\
[**SAT**](https://en.wikipedia.org/wiki/SAT)


# **Data Dictionary**

 Feature                      	| Type    	| Dataset  	| Description                                           	|
|------------------------------	|---------	|----------	|-------------------------------------------------------	|
| state_name                   	| object  	| SAT/ACT  	| State                                                 	|
  | sat_participation_percentage 	| float   	| sat_2019 	| Statewide SAT Participation Rate, 2019                	|
| ebrw_score                   	| integer 	| sat_2019 	| State mean score, SAT Reading/Writing (200-800), 2019 	|
| math_score                   	| integer 	| sat_2019 	| State mean score, SAT Math (200-800), 2019            	|
| sat_total_score              	| integer 	| sat_2019 	| State mean total SAT score (400-1600), 2019           	|
| act_participation_percentage 	| float   	| act_2019 	| Statewide ACT Participation Rate, 2019                	|
| act_composite_score          	| float   	| act_2019 	| State mean ACT Composite Score (1-36), 2019           	|
| sat_score_percentage         	| float   	| act_2019 	| Statewide SAT Score Percentage, 2019                  	|
| act_score_percentage         	| float   	| act_2019 	| Statewide ACT Score Percentage, 2019                  	|


# **Conclusions**

There are 8 states with SAT Participation rate of 100% whereas there are 15 states with ACT participation rate of 100%.Lowest participation rate of SAT is 2% where as in ACT lowest participation rate is 6%. \
ACT outperfromed SAT in terms of participation rate in the year 2019.\
Participation is high in the states where test is made mandate by the state department and by waiving of the test fee.
11 states (Colorado, Connecticut, Delaware, Idaho, Illinois, Maine, Michigan, New Hampshire, Rhode Island, and West Virginia and the District of Columbia) made SAT mandatory and administered at no cost to students because of which participation is above 90% in those states.\
There are strong regional affiliations associated with ACT versus SAT preference. East and west coast states tend to favor the SAT, while Midwest states  tend to favor the ACT.
Maine, New Hampshire, Massachusetts, Rhode Island, Connecticut, New York, New Jersey, Delaware, Maryland, Virginia, North Carolina, South Carolina, Georgia, and Florida states SAT participation is above 50% Whereas Kansas, Minnesota,Nebraska, North Dakota, Ohio, South Dakota, and Wisconsin states ACT participation is above 70%.\
Becasue Illinois and Michigan state departments made SAT mandatory ACT participation is low there even though midwest region tends to prefer ACT.\
ACT and SAT participation rates are inversely proportional to their respective scores.Wisconsin,for instance,despite 3% participation,ranks 2nd in SAT mean score. In the same way,Rhode Island,despite 14% participation ranks 4th in ACT mean score.

# **Recommendations**

In order to increase the participation of SAT, the College Board should collaborate with state departments of education to subsidize full costs of the test ,offer scholarships to students who take SAT and making SAT madnatory in the states with low participation.\
College board collaborating with coaching centers to offer free online pratcice tests and instructional videos on how to score more to students which will help in increasing states mean score as well.
ACT is a paper based and computer based test whereas SAT is a paper based test. So college board should make computer-based SAT tests available so that it would be flexible for students and they can receive their scores faster.








