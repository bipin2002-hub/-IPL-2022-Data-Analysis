🏏 IPL 2022 Data Analysis

Exploratory Data Analysis (EDA) of the Indian Premier League 2022 season using Python. The project explores match results, toss trends, player performances, and venue statistics across all 74 matches.

📌 Table of Contents
Project Overview
Dataset
Tools & Libraries
Analysis Performed
Key Insights
Project Structure
How to Run
Future Improvements
Author
📖 Project Overview

This project analyzes IPL 2022 match-level data to uncover patterns in team success, toss decisions, individual player brilliance, and venue usage. It uses data cleaning, aggregation, and visualization techniques to turn raw match data into meaningful insights.

📂 Dataset

File: IPL.csv
Size: 74 rows × 20 columns (one row per match) 
No missing values, no duplicate rows
Column	Description
match_id	Unique match number
date	Match date
venue	Stadium where the match was played
team1, team2	Teams playing
stage	Stage of tournament (league/playoff)
toss_winner, toss_decision	Toss result and choice (bat/field)
first_ings_score, first_ings_wkts	1st innings runs and wickets
second_ings_score, second_ings_wkts	2nd innings runs and wickets
match_winner	Winning team
won_by, margin	Runs/Wickets and winning margin
player_of_the_match	Man of the Match
top_scorer, highscore	Best batter and score in the match
best_bowling, best_bowling_figure	Best bowler and figures

🛠 Tools & Libraries
Python 3
Pandas – data manipulation
NumPy – numerical operations
Matplotlib – plotting
Seaborn – statistical visualization
Jupyter Notebook / Google Colab

🔍 Analysis Performed
Data loading, inspection, null and duplicate checks
Team-wise match wins
Toss decision trends
Toss winner vs. match winner correlation
Winning pattern: by runs vs. by wickets
Most Player of the Match awards
Top run-scorers
Top bowlers (by best-bowling wickets)
Venue-wise match distribution

Record analysis: biggest win margin, highest individual score, best bowling figures
💡 Key Insights
🏆 Gujarat Titans won the most matches (12), followed by Rajasthan (10) and Bangalore / Lucknow (9 each).
🪙 Teams overwhelmingly chose to field first after winning the toss (59 vs 15 choosing to bat).
🎯 Winning the toss did not guarantee victory — only 48.65% of toss winners won the match.
⚖️ Matches were evenly split: 37 won by runs, 37 won by wickets.
🌟 Kuldeep Yadav received the most Player of the Match awards (4), followed by Jos Buttler (3).
🏏 Jos Buttler led the top-scorer chart with 651 cumulative runs in top-scorer performances.
📍 Wankhede Stadium, Mumbai hosted the most matches (21).
💥 Biggest win by runs: Chennai by 91 runs.
🔥 Highest individual score: Quinton de Kock – 140.
🎳 Best bowling figures of 5 wickets were shared by Yuzvendra Chahal (5/40), Umran Malik (5/25), Wanindu Hasaranga (5/18) and Jasprit Bumrah (5/10).
📁 Project Structure
IPL-2022-Data-Analysis/
│
├── IPL_2022_Data_Analysis.ipynb   # Main analysis notebook
├── IPL.csv                        # Dataset
├── requirements.txt               # Dependencies
└── README.md                      # Project documentation
