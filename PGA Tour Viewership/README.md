# PGA Tour Viewership Project

## This project was completed with classmate Jackson Beers with guidance from Sport Analytics Program Director Rodney Paul, as a paper submission to the Academy of Economics and Finance Conference 

### A few notes about the data

• Includes data from 45 PGA Tour tournaments from 2018-2022 with attributes like Final Round TV rating, Leader Margin Before R4, Leader Margin After R4, Whether there was a playoff, Tiger Woods Made Cut / Top 10, and several other player effects in an attempt to quantfify the factors that influence modern PGA Tour viewership

• Average Final Round TV Rating (Nielsen) was used as a dependent variable against a variety of player effects, tournament effects, and uncertainty of outcome predictors

• Player effects (Presence of 6 distinct players in the top 10 of the leaderboard ~ Tiger, Rory, Bryson, JT, Spieth, Phil) aim to capture any sort of granular impact these players may have on final round viewership, given their innate talent and popularity

• Tournament effects (the distinct categorical tournament variable) aims to capture the impact that specific tournaments have on final round viewership. For example, majors like the Masters, PGA Championship, US Open, and Open Championship would likely have higher relative viewership no matter the players in contention or the margin of victory

• Uncertainty of Outcome Variables (Leaders margin at the beginning and end of R4) attempts to grasp the possibility that viewership will be innately higher if the tournament is closer (i.e the margin is smaller) 

• Future research will incorporate betting odds as a means to measure uncertainty of outcome more accurately 


### A few notes about the model results

• We tested several multiple linear regressions with robust standard errors for the player effect variables, the second of which we found to be signficant
for not only the tournament effect variables, but the presence of Tiger Woods on the leaderboard and the leader margin at the end of round 4 

• The player and tournament effect variables are consistent with prior research on the subject (Stephenson and Gooding 2017); however, this is one of the only academic papers that provides statistical evidence in favor of the uncertainty of outcome hypothesis in PGA Tour golf tournaments

• This type of research into the mind and preferences of PGA Tour viewers is becomming more and more valuable as tensions rise between the PGA Tour and the rival, Saudi-Backed LIV Tour
