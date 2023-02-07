# PGA Tour Viewership Project

## This project was completed with classmates Jackson Beers and Shane Halpin with guidance from Sport Analytics Program Director Rodney Paul, as a paper submission to the Academy of Economics and Finance Conference 

### A few notes about the data

• Includes data from 45 PGA Tour tournaments from 2018-2022 with attributes like Final Round TV rating, Lead Margin Before / End of R4, Tiger Woods Made Cut / Top 10, and others in an attempt to quantfify the factors that influence modern PGA Tour viewership

• Average Final Round TV Rating was used as a dependent variable against a variety of player effects, tournament effects, and uncertainty of outcome predictors

• Player effects (Presesce of 5 distinct players in the top 10 of the leaderboard) aim to capture any sort of granular impact that these players may have had on final round viewership, given their presence on the leaderboard

• Tournament effects (the distinct categorical tournament variable) aims to capture the impact that specific tournament have on final round viewership. For example, majors like teh Masters, PGA Championship, US Open, and Open Championship would likely have higher relative viewership no matter the players in contention or the margin of victory

• Uncertainty of Outcome Variables (Leaders margin at the beginning and end of 4) attempts to grasp the possibility that viewership will be innately higher if the tournament is closer (i.e the margin is smaller) 


### A few notes about the model results

• We tested several multiple linear regressions with robust standard errors for the player effect variables, the second of which we found to be signficant
for not only the tournament effect variables, but the presesce of Tiger Woods on the leaderboard as well as the leader margin at the end of the round

• The player and tournament effect variables are consistent with prior research on the subject (Stephenson and Gooding, 2017); however, this is one of the only academic papers that provides statistical evidence in favor of the uncertainty of outcome hypothesis in PGA Tour golf tournaments

• This type of research into the mind of PGA Tour viewers is becomming more and more valuable as the tensions rise between the PGA Tour and the rival, Saudi Backed LIV Tour
