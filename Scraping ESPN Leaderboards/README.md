# Scraping ESPN Leaderboards

## This outside research project was completed to advance my web scraping skills in rvest, while also increasing my warchest of golf data

### Scraping Process

Step 1: Assign url and read in url variable, before piping it into a df using the html_nodes & html_table functions

Step 2: Grab tournament id, name, and date using regex before pulling into empty vectors

Step 3: Loop through the tournament ids to extract id, name, date in a specified format - paged_table function creates the table after extracting into a df

Step 4: Research tournaments that don't follow normal format (WGC Match play, Ryder Cup, etc.) and remove them from the ID loop using stopwords methodology

Step 5: Create final loop and series of nested if statements, in assigning and extracting the specific attributes of the leaderboard (pos, player, to_par, R1, R2, R3, R4, total, earnings)

The final scraped file of 2018-2022 eligible leaderboards are located in the "scores2018_2022.csv" file


