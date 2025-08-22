🏏 IPL Analysis Dashboard
📌 Project Overview

This project provides an interactive Power BI dashboard for analyzing Indian Premier League (IPL) data from 2008 to 2022. The dashboard offers insights into players, teams, venues, and match outcomes.

Using two datasets:

ipl_ball_by_ball_2008_2022.csv – Ball-by-ball match details.

ipl_matches_2008_2022.csv – Match-level details.

The analysis helps cricket fans, analysts, and stakeholders explore player performance, match trends, and tournament stats with a user-friendly interface.

📂 Dataset Description
1. ipl_ball_by_ball_2008_2022.csv

Contains detailed ball-by-ball information.
Key columns:

id → Match ID

inning → Inning number

over → Over number

ball → Ball number

batsman → Name of batsman

bowler → Name of bowler

total_runs → Runs scored on the ball

is_wicket → Whether a wicket fell

2. ipl_matches_2008_2022.csv

Contains match-level details.
Key columns:

id → Match ID

season → Year of IPL

city → Venue city

team1, team2 → Competing teams

toss_winner, toss_decision → Toss details

winner → Match winner

win_by_runs, win_by_wickets → Result margin

player_of_match → Best player

📊 Dashboard Features
🏆 Tournament Summary

Title Winner (e.g., Mumbai Indians in 2017).

Orange Cap (Most Runs – e.g., DA Warner with 641 runs).

Purple Cap (Most Wickets – e.g., B Kumar with 26 wickets).

Tournament 6’s and 4’s distribution.

⚡ Player Analysis

Batting Stats (Total Runs, 4s, 6s, Strike Rate).

Bowling Stats (Wickets, Economy, Bowling Average).

Dropdown filters for selecting specific batsman/bowler.

🏟️ Match Insights

Matches won by venue (Runs, Wickets, Super Over).

Matches won by team (team-wise performance).

Matches won based on toss decision (Bat/Field).

Matches won by result type (Runs, Wickets, Super Over).

🚀 Tools & Technologies Used

Power BI → Dashboard development and visualization.

Python / Pandas (optional preprocessing).

Datasets → Kaggle IPL dataset (2008–2022).

📈 Key Insights from the Dashboard

Mumbai Indians were the title winners in 2017.

DA Warner scored the most runs (641) in 2017.

Bhuvneshwar Kumar took the most wickets (26) in 2017.

Majority of matches were won by chasing (fielding first).

Most matches were won by wickets rather than runs.
