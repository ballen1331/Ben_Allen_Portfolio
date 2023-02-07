# Estimating Value in College Athletics

## Project completed for the class SAL 366 (Sport Economics II)

### Notes about the data:

• Dataset of 1073 individual college football seasons for power 5 teams (2006-2015), with attributes about recruiting, future NFL draft status, scheduling, team points, and entertainment scores, seeking to gain insight into the factors that influence financial success of a college football program

• Specifically, the goal is to isolate the recruiting and NFL draft metrics in an attempt to quantify the monetary equivalent of an elite college football player 

### Model Results and Conclusions:

• Three-level quantile regression(.25, .5, .75) revealed to varying degrees of certainty that our 'playersall' attribute, which counts the number of future drafted players on that team's roster, correlates to somewhere between $1,500,000 - $2,300,000 in future program earnings per highly drafted player. 

• A separate 2SLS model taking into account college specific effects (isolating for Alabama, Georgia, Ohio State) estimates an elite player's valuation at a top tier program like Alabama, Georgia, and Ohio State to be as high as $6,000,000 

• Without taking into account program effects, a third lagged recruiting model estimates a more modest value of $965,000 per elite player, which I would presume to be the most accurate for any given player coming out of high school

• Overall, this unique dataset provided by Dr. Jeremy Losak allowed me to analyze the types of statistical models that economists in the collegiate sports world tackle on a daily basis

