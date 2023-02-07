# NBA Shot Chart Shiny App

## This project was completed with classmate Daniel Beim for our SAL 413 class - R for Sport Analytics

### A few notes about the data:

• The data contains around 103,000 individual shots obtained from the nbastatR API (https://github.com/abresler/nbastatR)

• Only shots from Western Pacific NBA teams (Suns, Warriors, Kings, Clippers, Lakers) from the 2018 - 2020 NBA seasons were used in order to comply with Shiny's rendering capabilites

• Key Attributes include the following:  Player/Team Name, Shot Event/Action/Type (Made Shot / Jump Shot / 3-pt shot), geolocation X,Y coordinates that correspond with best practices in court visualization - i.e (locationX = 2, locationY = 10) corresponds to specific location on the court

• The final data file ("PacificShots2.csv") was too large to fit in GitHub, but can be obtained by running the "SAL 413 Project Data Scrape.Rmd file" 

### A few notes about the app:

• A link to the app is here: (https://danielbeim.shinyapps.io/SAL413FinalProject/)

• In the top left, choose a player you want to analyze 

• Upon selecting, the player's 2018 shot chart (made / missed shots) will pop up in the top right along with a plotly distribution of the player's made
shots and a ggplot2 bar graph of the shot type distribution

• All three visuals will dynamically update based on years chosen in the "Select Season" input (type in 2019 to add the player's 2019 data to the graphics)

