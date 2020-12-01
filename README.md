# Scraping_Building_2_Massive_NBA_Data_Sets

The NBA is rich with team and player data. After having challenges working with NBA API, we decided to scrape directly from Basketball Reference (https://www.basketball-reference.com/), a source of NBA data and analytics used widely in the industry.

First, we'll scrape team data, including team name, conference, win-loss percentage, and unadjusted and adjusted offensive, defensive, and net ratings from 2016 through 2020. Next, we'll scrape player data for total season, per game, per 36 minute, per 100 possession, and advance analytics from 2016 through 2020. To build up our data set, we'll define and bundle together functions that scrape data, build, format, and save dataframes, and loop over each year (and stat type for player data). In scraping, we'll make us of list comprehension, which is arguably one of the most beautiful techniques in Python. We'll merge together team data for each year and player data for all stat types for each year to create massive team and player csv files, respectively.

If you'd like to explore the data, you can access and use the csv files from our Google Drive:

NBA Team Stats 2016-2020: https://drive.google.com/file/d/130BewO9dBGYjHicr_1y-1xWZB-HFWfQ3/view?usp=sharing
NBA Player Stats 2016-2020: https://drive.google.com/file/d/1t7hcd6-M7RxTn7WZsA1s4O-6njcwS4X0/view?usp=sharing
