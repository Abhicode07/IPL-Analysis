# 🏏 IPL Analysis Dashboard (2008–2025)  

## 📌 Project Overview  
This project delivers a comprehensive **SQL-powered IPL Analysis Dashboard** that visualizes data from the **Indian Premier League (2008–2022)**.  
The dashboard uncovers trends around **players, teams, venues, and match results**, making it valuable for fans, analysts, and cricket strategists.  

The analysis leverages:  
- **ipl_ball_by_ball_2008_2022.csv** → Ball-level details of every match.  
- **ipl_matches_2008_2022.csv** → Match-level metadata and outcomes.  

---

## 📂 Datasets  
### **1. Ball-by-Ball Data** (`ipl_ball_by_ball_2008_2022.csv`)  
Contains granular details of each delivery.  
- `id` → Match ID  
- `inning` → Inning number  
- `over`, `ball` → Delivery sequence  
- `batsman`, `bowler` → Player names  
- `total_runs` → Runs from each ball  
- `is_wicket` → Dismissal indicator  

### **2. Match Data** (`ipl_matches_2008_2022.csv`)  
Captures match-level summary.  
- `id` → Match ID  
- `season` → IPL season year  
- `city`, `venue` → Location of match  
- `team1`, `team2` → Competing sides  
- `toss_winner`, `toss_decision` → Toss details  
- `winner` → Match winner  
- `win_by_runs`, `win_by_wickets` → Victory margin  
- `player_of_match` → Match MVP  

---

## 📊 Dashboard Highlights  

### 🏆 **Season Overview**  
- IPL title winners per season.  
- Orange Cap: Top run scorers.  
- Purple Cap: Leading wicket takers.  
- Season totals for 4s & 6s.  

### ⚡ **Player Insights**  
- Batting analysis → Runs, strike rate, boundaries.  
- Bowling analysis → Wickets, economy, averages.  
- Player-level filtering options.  

### 🏟 **Match Breakdown**  
- Team win distribution (by wickets, runs, super overs).  
- Venue-based win statistics.  
- Toss decision impact on outcomes.  
- Head-to-head team performance.  

---

## 🚀 Tools & Technologies  
- **SQL** → Data querying & aggregation.  
- **Power BI** → Interactive dashboards.  
- **Python (Pandas)** → Optional data preprocessing.  
- **Datasets** → IPL Kaggle dataset (2008–2022).  

---

## 📈 Sample Insights  
- **Mumbai Indians** crowned champions in 2017.  
- **David Warner** dominated batting with 641 runs in 2017.  
- **Bhuvneshwar Kumar** topped bowling with 26 wickets in 2017.  
- Chasing teams won the majority of games.  
- Matches were more frequently decided by **wickets than runs**.  

---

## 📌 How to Use  
1. Load the datasets into SQL / Power BI.  
2. Run SQL queries for data aggregation.  
3. Connect processed data to Power BI.  
4. Explore dashboards with slicers and filters.  

---

## 📝 Example SQL Queries  

### 🔹 Top 5 Run Scorers in a Season
```sql

