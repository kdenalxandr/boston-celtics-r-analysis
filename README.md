# boston-celtics-r-analysis
Exploring Boston Celtics Stats with R
# Boston Celtics Player Analysis 2024-2025 Season 
This analysis contains a project I started for the Boston Celtics current 2024-2025 season on Christmas day. Due to the conclusion of the season the data has been updated. This data set pulls from the Basketball-Reference URL. This project demonstrates my ability to data mine with R, data wrangling and exploratory visualization in the early stages of my career building skills.

## Why I Did This
I wanted to apply R programming using a real-world data set and improve my ability to
- Scrape live data from websites such as Basketball-Reference
- Clean and prepare messy datasets
- Identify Trends in player performance
- Visualize how individual players compare to team averages

# What I Did (Step-By-Step)
1. Scraped player stats from Basketball-Reference.com
2. Extracted the HTML table and previewed the data
3. Cleaned the data by:
   - Removing players with missing stats
   - Focusing on key metrics:
   - Points Per Game
   - Three Point Percentage
   - Total Rebounds
   - Assists
   - Free Throw Percentage
   - Minutes Played
   - Field Goal Percentage
4. Calculated the team averages for each category
5. Flagged underperforming players who were below the team average
6. Visualized:
   - Players performing above or below the team average in points per game
   - Relationship between minutes played per game vs points per game


## What's Included
- boston_celtics_2025_season_stats.Rmd - Full Analysis in R
- boston_celtics_2025_season_stats.html - Rendered version with visuals (download document to see visualizations)
- README.md - project summary

## Future Improvements
- Update Analysis with complete 2024-2025 season stats
