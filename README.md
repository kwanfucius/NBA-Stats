# NBA Statistics
Hall of fame players and all-star players dramatically escalate the publicity, therefore the sales of teams. There are only 177 in NBA history that are inducted into the hall of fame and 431 players selected for an all-star game held every year. To put in perspective only 3.6% percent of players make the hall of fame and only 8.7% of players have made an all-star game.  So, the motivation of this analysis is to give general managers a model to best predict players that will promulgate their brand. The key variables we look at are if players are inducted into the hall of fame, if they make it to the all-star team, and their salaries. Analysis will be presented for each of these variables individually to prevent multicollinearity.  

# Tools
- R, Rstudio
- SQL 
- Statistics and Modeling
- Machine Learning(Linear Regression, GLM, Decision Trees, Predictive Modeling)

# Datasets And Resources
* [General NBA Data](https://www.kaggle.com/open-source-sports/mens-professional-basketball) – Used for data on general player background information, awards given to players, and the listing of all players that made the all-star team each year
* [NBA Salaries](https://data.world/datadavis/nba-salaries) – Data on salaries from 1985 – 2018
* [NBA Player Stats](https://www.kaggle.com/drgilermo/nba-players-stats) – NBA player game statistics for all players from 1950 - 2017
* [Basketball Statistics Glossary](https://www.basketball-reference.com/about/glossary.html) – A dictionary of all statistics acronyms

# Interesting Finds
A trend currently in the NBA is the transition from an emphasis on the two-point conversion (higher probability but less reward) to the exaggeration of the three-point shot (lower probability higher reward). Currently, it seems that the higher rated players have a high 3-point percentage and number of attempts. So, to explore this point we looked into the salary versus the 2-point and 3-point shot. A higher salary from either category would mean that overall, more revenue comes from those who shoot 3-pointers and those who shoot mainly 2-pointers

![alt text](https://github.com/kwanfucius/NBA-Stats/blob/main/Images/Salary%20and%20Shot%20Type%20Percentage.png)

The graph below shows us an interesting feature of the NBA. The higher 3-pointer percentage eventually has a lower expected salary. This is due to the fact that when players have a very high 3-point percentage they are isolated to doing that skill that they do best, thus becoming a "role player". Whereas those of all-star tendencies have a variety of skill. Those with a This brings us to another feature found in the NBA. The players that are more awarded or have a higher salary tend to have a large number of diverse skills. This is shown by the graph below. Those in red have only one specific role whereas those in blue can fill two roles on a single team. The median salary tends to be advantageous to those who can play two roles. 

![alt text](https://github.com/kwanfucius/NBA-Stats/blob/main/Images/Salary%20and%20Player%20Position.png)

The NBA due to the nature of revenue streams has put a large emphasis on offensive play specifically points. One may expect that there would be an overemphasis on points. However, this data set shows that there a large desire for diversification of skill. Each of these statistics show that there is a median where the salaries are expected to be the highest. This again supports our claim of a “role player” versus an all-star. Whereas a role player specializes in a certain statistic, all-stars tend to be had a variety of impacts on all sides of the game. 

![alt text](https://github.com/kwanfucius/NBA-Stats/blob/main/Images/Salary%20and%20Individual%20Stats.png)
