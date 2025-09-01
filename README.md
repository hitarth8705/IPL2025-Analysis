Overview

This project provides an in-depth analysis of the Indian Premier League (IPL) using historical match, player, and team data. It uncovers insights into team performances, toss impacts, player achievements (Orange Cap & Purple Cap), and overall trends across multiple IPL seasons.

Dataset

The analysis is based on the following CSV files:

matches.csv – Match details including winners, toss results, and outcomes.

deliveries.csv – Ball-by-ball data for every IPL match.

orange_cap.csv – Top run-scorers of each IPL season.

purple_cap.csv – Top wicket-takers of each IPL season.

teams_data.csv – Information about IPL teams.

⚙ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib

 Key Features

 Match Winners Analysis – Identifies top-performing teams across seasons.

 Toss Impact – Evaluates how toss decisions influence match outcomes.

 Team Performance Trends – Compares win/loss ratios of IPL teams.

 Orange Cap Analysis – Tracks top run-scorers by season.

 Purple Cap Analysis – Tracks top wicket-takers by season.

 Visual Insights – Graphical representation of team dominance and player consistency.

 Machine Learning Prediction:
 
Preprocessed IPL datasets (matches.csv, deliveries.csv, teams_data.csv).

Engineered features such as toss winner, venue, and team performance stats.

Trained a Random Forest Classifier to predict the match_winner.

Evaluated model performance using train-test split and accuracy metrics.
