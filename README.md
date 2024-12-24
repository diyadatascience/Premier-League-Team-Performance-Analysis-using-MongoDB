# Premier League Team Performance Analysis Using MongoDB

## Project Overview
This project analyzes the Premier League 2024 dataset using MongoDB to derive actionable insights into team performance, leveraging advanced aggregation queries and scalable database design. It evaluates critical metrics like offensive and defensive balance, top scorer influence, and team strategies to optimize decision-making.

## Key Features
- **Scalable and Efficient Database Design**: 
  - Collections for team_performance, players, matches, live_commentary, and team_stats for optimized queries and scalability.
  - Combination of embedding and referencing for high query locality and normalization.
- **Advanced Aggregation Queries**:
  - Filtered and analyzed offensive vs. defensive contributions to team success.
  - Dynamic integration of expected goals (xG), expected goals against (xGA), and player stats for multi-dimensional insights.
- **Insights Extraction**:
  - **Win Rate Boost**: Teams with top scorers contributing over 30% of goals had a 15% higher win rate.
  - **Impact Scores**: Metrics like Liverpool's 783, derived from key player performances (e.g., Salah’s 13 goals), highlighting player influence on outcomes.
  - **Balance Analysis**: Identified teams with a stronger offensive or defensive balance to optimize tactical strategies.
- **Real-Time Match Simulation**:
  - Simulated live commentary with dynamic data capture for strategic match insights.
  - Highlighted key events such as goals, substitutions, and tactical shifts.

## Dataset
The dataset includes key metrics for 20 teams across 380 matches:
- **Basic Metrics**: Wins, losses, goals scored (GF), and goals conceded (GA).
- **Advanced Metrics**: Expected Goals (xG), Expected Goals Against (xGA), Goal Difference (GD), and Points per Match (Pts/MP).
- **Player and Team Data**: Top scorers, goalkeepers, and attendance records.

## Insights
1. **Top Scorer Impact**: Teams with consistent top scorer performance (e.g., Salah’s 13 goals for Liverpool) had a measurable impact on win rates.
2. **Fan Engagement**: "Impact Scores" quantified the synergy between top players and team success.
3. **Offensive vs. Defensive Strength**:
   - High-performing teams showed balanced xG and xGA metrics, contributing to consistent outcomes.
4. **Key Match Analysis**:
   - Salah's critical role in Liverpool's wins demonstrated the value of top players in pivotal moments.
   - Teams with weaker defensive records showed lower xGA metrics, highlighting areas for improvement.

## Technologies Used
- **MongoDB**: For efficient data storage and advanced querying.
- **Python**: 
  - Data scraping: Beautiful Soup.
  - Data cleaning: Pandas.
  - Database integration: PyMongo.


