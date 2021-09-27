# mlb-data-analysis-project
## Overview:
This project analyzes how top run-producing Major League Baseball teams construct their lineups. 
I will be looking at advanced stats (listed and defined below) of the lineups and comparing them to the MLB average. 
This project used technologies such as: Pandas, Python, Matplotlib, PostgreSQL. Data was pulled from https://baseballsavant.mlb.com/ and https://www.baseball-reference.com/. 

## Process:
The highest scoring teams in the National League and American League were pulled from baseball reference, as were the most common lineups for the respective teams, and organized into tables.

After finding the most common lineups, I combined each spot in the lineup with the same spot in the lineup for each of the three seasons with one another (example: leadoff hitters from 2019-2021 were placed together) and found their averages.
Once the averages for each spot in the lineup were found, I created a table to compare them with the MLB league-wide average.

Next, I created bar graphs to visualize the traits each spot in the lineups produced and their comparisons to the MLB average, followed by an analysis of what traits top run-scoring teams look for to construct a lineup.
Finally, I connected to a database (only shows the steps in which I would do so. Actually doing so would mean displaying my local password which I have been advised not to do).

## Possible Improvements:
Creating a model that would sort each teams roster and fill each spot in the lineup as similar to the findings from this analysis and run multiple tests to see what the expected runs scored would be for a given game, and then compare them to how the team actually produces.
