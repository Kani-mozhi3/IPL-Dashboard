# IPL-Dashboard
## IPL 2025 Performance Analytics Dashboard
## 📊 Project Overview
This project provides a comprehensive end-to-end data analytics solution for the IPL 2025 Season. It transforms raw match data into actionable insights, focusing on team performance, player statistics, and venue-based trends. The final output is an interactive Power BI dashboard designed for stakeholders to track season progress at a glance.

## 🛠️ Tech Stack

Data Source: CSV / Kaggle Dataset
Data Cleaning: Python (Pandas) / SQL
Database: Microsoft SQL Server
Visualization: Power BI

## 🚀 Workflow
### 1. Data Loading & Extraction
Imported raw dataset containing match details, toss results, and player scores.
Established a connection between the local data files and the SQL Server environment.

### 2. Data Cleaning & Transformation
Handling Nulls: Managed missing values in "Player of the Match" and "High Score" columns.
Data Consistency: Standardized team names and venue locations.
Type Casting: Ensured dates and numerical scores were correctly formatted for calculation.

### 3. Power BI Dashboarding
Built an interactive dashboard featuring:

KPI Cards: Average high score, total venues, and toss winners.
Geospatial Map: Visualization of match winners distributed across Indian cities.
Donut & Pie Charts: Breakdown of run distribution and win shares by team.
Interactive Tables: Filterable lists for Player of the Match and team-specific stats.

## 📈 Key Insights

Dominant Force: Gujarat Titans (GT) commanded a 45.4% share of total runs in the analyzed period.
Consistency: Certain players showed high scoring reliability across both "Team 1" and "Team 2" appearances.
Venue Impact: Specific venues showed a higher correlation between winning the toss and winning the match
