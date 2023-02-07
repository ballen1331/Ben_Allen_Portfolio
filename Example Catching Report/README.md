# Example Catching Report

## This project served as the initial R&D report sent to the coaching staff of VCU Baseball 

### A few notes about the data: 

• TrackMan Data includes 255 sample pitches from various catchers on the VCU baseball team, with attributes like pitch result, plate location (X,Y), pop time, and other throwing metrics

• These catching variables were used to create the strike zone plots, predicted strike characteristcs, and summary tables shown in "Group1CatchingReportUpdated.pdf"

### A walkthrough of the report

• Plot 1: Ball and Strike pitch results measured throughout the strike zone (strike zone created as geom object in R)

• Plot 2: Pitch results, shaded by our own strike probability model

• Table Page: Real vs Predicted strike zone results by catcher, along with throwing metric summaries

• Plot 3: Pop time results by catcher, shaded by catcher throwing speed

• Plots 4-9: Plot of Ball/Strike calls for each catcher, shaded by StrikesGained model predictions

• All data cleansing, model structuring / predictions, and subsequent plots can be run in the Report1Code.Rmd file for reference


