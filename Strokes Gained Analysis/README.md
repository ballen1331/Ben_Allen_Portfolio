# Strokes Gained Analysis of Professional Golfers

## This project details most of the work I completed as part of my Senior Thesis Project "Drive For Dough? A Strokes Gained Analysis of Professional Golfers"

### A few notes about the data

• Obtained from datagolf.com, the full dataset (golfdata4.csv contains 306,000 rows of round performance data, from all players across all known tours from the years 2017-2021)

• Applicable variables to my strokes gained analysis are the following: player, event, date, round score, total score, finishing position, SG Total, and most importantly - the individual strokes gained categories that encompass SG Total (SG Putting, SG Around the Green, SG Approach, SG Off the Tee)

• I then cut it down to include only PGA Tour players in rounds that include all SG categories (some international / smaller events do not track these stats)

### Analytical Process

• Begin by cleaning data in R, before summarizing key attributes (See: "SumStats2.pdf")

• Perform exploratory SG analysis on individual golfers to examine strokes gained makeup over time and get to know the data even more. I chose to do this with world number 1 Jon Rahm, creating relevant plots in R (ggplot2) that detail his SG performance by round / tournament throughout the time period (See: Poster_Final.pdf, TrackingRahm.pdf, and Poster_Graphics.Rmd) for blog style write up and poster. 

• From there, I began modeling my dependent variable ~ Winning the Golf Tournament ~ through logistic regression with various Strokes Gained predictors (SG Total, SG Putting, SG Around the Green, SG Approach, SG Off the Tee)

• The final logistic regression provided evidence in support of Strokes Gained Off the Tee and Strokes Gained Approach as the SG categories that have the highest value as they pertain to influence on winning a golf tournament. In other words, a stroke gained driving is more valuable than a stroke gained putting or around the green.

• After that, I wanted to see if I could group or cluster the golfers in my dataset by strokes gained makeup, as to identify players by strength (i.e Bryson DeChambeau being an off the tee dominant player vs Denny McCarthy being a short game dominant player)

• Upon performing this cluster analysis, I was able to parse through any individual golfer on the Factor Map (See: cluster.pdf) and identify those who are more likely to perform better in the future based on consistent, ball-striking attributes. 

• A final poster detailing my process and conclusions in more detail is shown on "Allen_Poster.pdf" and the final research paper can be downloaded under "Thesis Honors Final.docx"

