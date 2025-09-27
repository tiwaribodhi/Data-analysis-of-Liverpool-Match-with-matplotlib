# Liverpool Match Data Analysis  

This project uses **Python (NumPy, Pandas, Matplotlib)** to analyze Liverpool’s football performance across multiple dimensions such as home vs away, match outcomes, efficiency, and momentum. It provides **visual insights** to better understand the club’s strengths and weaknesses.  

---

## 📑 Table of Contents  
1. [Overview](#-overview)  
2. [Dataset](#-dataset)  
3. [Analysis & Visualizations](#-analysis--visualizations)  
   - [Home vs Away Performance Gap](#1-home-vs-away-performance-gap)  
   - [Match Outcome Breakdown](#2-match-outcome-breakdown)  
   - [Shot Efficiency vs Goals](#3-shot-efficiency-vs-goals)  
   - [Opponent Strength Effect](#4-opponent-strength-effect)  
   - [Last 5 Match Momentum](#5-last-5-match-momentum)  
4. [Results](#-results)  
5. [Tech Used](#-tech-used)  

---

## 🔎 Overview  
Football performance analysis is crucial for clubs to evaluate strategies, identify weaknesses, and optimize results. This project focuses on **Liverpool FC’s match data** and answers key performance questions such as:  

- Does playing at home give Liverpool a significant edge?  
- How are wins, draws, and losses distributed over the season?  
- Is shot efficiency a real indicator of scoring success?  
- Do strong possession-based opponents reduce Liverpool’s goal output?  
- Does momentum from recent matches correlate with results?  

Through **bar charts, pie charts, scatter plots, line plots, and box plots**, this project provides actionable insights into performance patterns.  

---

## 📂 Dataset  
The project expects a CSV file named `Liverpool.csv` with columns such as:  
- `Is_Home` → 1 if match at home, 0 if away  
- `Goals` → Goals scored by Liverpool  
- `Opponent_Goals` → Goals conceded  
- `Result` → 1 (Win), 0 (Draw), -1 (Loss)  
- `Shot_Efficiency` → Measure of shooting efficiency  
- `Opponent` → Name of opponent club  
- `Opponent_Possession` → Avg possession % of opponent  
- `Last5_Win_Rate` → Win rate in last 5 matches before this game  

---

## 📊 Analysis & Visualizations  

### 1. Home vs Away Performance Gap  
- **Question**: Does Liverpool perform significantly better at home than away?  
- **Visualization**: Side-by-side bar chart (avg goals scored & conceded at home vs away).  
- **Insight**: Highlights performance consistency across venues.  

### 2. Match Outcome Breakdown  
- **Question**: What is the distribution of Wins, Draws, and Losses?  
- **Visualization**: Pie chart with percentage breakdown.  
- **Insight**: Gives a quick overview of season performance.  

### 3. Shot Efficiency vs Goals  
- **Question**: Does higher shot efficiency lead to more goals?  
- **Visualization**: Scatter plot of `Shot_Efficiency` vs `Goals` with trend line.  
- **Insight**: Identifies whether efficiency translates into scoring.  

### 4. Opponent Strength Effect  
- **Question**: Do Liverpool struggle more against stronger possession teams?  
- **Visualization**: Line plot of opponent possession vs goals scored (highlight top 3 toughest opponents).  
- **Insight**: Helps find teams that suppress Liverpool’s attacking power.  

### 5. Last 5 Match Momentum  
- **Question**: Does recent momentum influence match outcomes?  
- **Visualization**: Boxplot of `Last5_Win_Rate` grouped by result (Win/Draw/Loss).  
- **Insight**: Shows whether form momentum predicts success.  

---

## 📊 Results  
From the analysis, some clear insights emerge:  
- **Home vs Away** → Liverpool generally scores more and concedes less at home.  
- **Match Outcomes** → The pie chart shows a higher proportion of wins compared to draws and losses.  
- **Shot Efficiency** → Positive correlation with goals scored, indicating efficient shooting is key.  
- **Opponent Possession** → High-possession teams tend to suppress Liverpool’s scoring, with the toughest 3 highlighted.  
- **Momentum Effect** → Higher last 5 match win rates are associated with more frequent wins.  

---

## 🛠 Tech Used  
This project is built using the following technologies:  
- **Python 3.x** → Core programming language  
- **NumPy** → Numerical operations and array handling  
- **Pandas** → Data cleaning and manipulation  
- **Matplotlib** → Data visualization and charting  
