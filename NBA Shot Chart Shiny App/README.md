# NBA Shot Chart Shiny App

## This project was completed with Daniel Beim (https://www.linkedin.com/in/danielbeim/) as a final assessment for the Syracuse University undergraduate class "R for Sport Analytics"

### A few notes about the data:

• The data contains around 103,000 individual shots obtained from the nbastatR API (https://github.com/abresler/nbastatR)

• Only shots from Western Pacific NBA teams (Suns, Warriors, Kings, Clippers, Lakers) from the 2018 - 2020 NBA seasons were used in order to comply with Shiny's renering capabilites

• Key Attributes include the following:  Player/Team Name, Shot Event/Action/Type (Made Shot / Jump Shot / 3-pt shot), geolocation X,Y coordinates that correspond with best practices in court visualization - i.e (locationX = 2, locationY = 10) corresponds to somewhere on the court

• The final data file ("PacificShots2.csv") was too large to fit in GitHub, but can be obtained by running the "SAL 413 Project Data Scrape.Rmd file" 

### A few notes about the app:

• A link to the app is here: NBA Player Shots By Season (shinyapps.io)
