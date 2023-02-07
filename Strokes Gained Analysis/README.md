# Strokes Gained Analysis of Professional Golfers

## This file details most of the work I completed as part of my Senior Thesis Project "Drive For Dough? A Strokes Gained Analysis of Professional Golfers"

### A few notes about the data

• Obtained from datagolf.com, the full dataset (golfdata4.csv contains 306,000 rows of round performance data, from all players across all known tours from the years 2017-2021)

• Applicable variables to my strokes gained analysis are the following: player, event, date, round score, total score, finishing position, SG Total, and most importantly - the individual strokes gained categories that encompass SG Total (SG Putting, SG Around the Green, SG Approach, SG Off the Tee)

• I then cut it down to include only PGA Tour players in rounds that include all SG categories (some international / smaller events do not track these stats)

### Analytical Process

• Begin by cleaning data in R, before summarizing key attributes (Summary Statistics: "SumStats2.pdf")

• Perform exploratory SG analysis on individual golfers to examine strokes gained makeup over time and get to know the data even more. I chose to do this with Jon Rahm, creating relevant plots in R (ggplot2) that detail his SG performance by round / tournament throughout the time period (
