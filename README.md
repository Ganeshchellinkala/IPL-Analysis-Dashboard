# IPL-Analysis-Dashboard

A comprehensive Tableau-based analytical dashboard designed to deliver powerful visual insights into Indian Premier League (IPL) team performance, player statistics, match patterns, venue behaviour, and season-wise comparisons across multiple years of the tournament.


## 1. Project Overview 

The **IPL Analysis Dashboard** is an interactive Tableau reporting solution built to explore match-level and player-level performance across all seasons of the Indian Premier League.
By integrating ball-by-ball, match, team, and player data, the dashboard highlights batting trends, bowling impact, winning probabilities, toss influence, and venue characteristics.

This dashboard is designed for cricket analysts, Tableau learners, fantasy cricket players, sports enthusiasts, and strategists who want meaningful insights from IPL data in a visually compelling format.


## 2. Purpose & Objectives

### **Business Problem**

IPL generates massive amounts of complex sports data every season. Without visualization, it becomes difficult to answer essential questions like:

* Which team performed best across seasons?
* Who are the top batsmen and bowlers?
* What is the impact of toss decision on winning?
* Which venue is more favourable for batting or bowling?
* How consistent are players across the tournament?

### **Goal of the Dashboard**

To deliver a user-friendly, highly visual Tableau dashboard that:

* Centralizes match, ball-by-ball, team, and player information
* Enables cross-season analysis with interactive filtering
* Supports strategic decision-making for player evaluation
* Simplifies complex patterns into intuitive visual stories
* Helps fans, analysts, and fantasy users make data-driven decisions


## 3. Tech Stack / Tools Used

📊 **Tableau Desktop** – Dashboard creation and insights.

🧽 **Excel** – Data cleaning & preprocessing.

🔗 **Data Blending + Joins** – For combining multiple tables.

📉 **Calculated Fields** – Strike Rate, Economy Rate, Win %, Impact Score.

🎛 **Filters, Parameters, Actions** – Interactive exploration.

##  4. Data Source
**Source:** [IPL Performance Dataset](https://www.kaggle.com/datasets/yash9439/ipl-dataset?select=deliveries.csv)

**Dataset Contains:**

* Matches dataset
* Deliveries (Ball-by-ball) dataset

## 5. Data Model & Table Structure

### **1. Matches Table**

Details every IPL match.

**Key Fields:**
Match_ID, Season, Venue, Team1, Team2, Toss Winner, Toss Decision, Match Winner, Win Margin

### **2. Deliveries (Ball-by-Ball) Table**

Contains granular information for every ball bowled.

**Key Fields:**
Match_ID, Over, Ball, Batsman, Bowler, Runs, Extras, Dismissal Type, Wicket


## 6. Dashboard Features & Highlights

### **Key Performance Indicators (KPIs)**

* Orange Cap Leader (Most Runs)
* Purple Cap Leader (Most Wickets)
* Most Valuable Player
* Team with Highest Win %
* Best Batting Strike Rate
* Best Bowling Economy
* Season Champions

### **Interactive Filters**

* Season
* Team
* Player
* Venue
* Toss Decision
* Match Result
* Batting/Bowling Role

## Dashboard Walkthrough

### **1. Season Overview**

Interactive charts showing:

* Total Matches
* Total Runs Scored
* Total Wickets
* Results by Season
* Team-wise Wins

**Visuals Used:**
Bar charts, area chart, KPI tiles, heat maps

### **2. Batting Performance Analysis**

* Top 10 run-scorers
* Strike rate comparison
* Boundary % (4s & 6s)
* Runs per over/innings
* Consistency score

**Visuals Used:**
Scatter plot, horizontal bar charts, highlight table

### **3. Bowling Performance Analytics**

* Top wicket takers
* Economy rate distribution
* Dismissal type breakdown
* Over-wise wicket patterns
* Season-wise bowling performance

**Visuals Used:**
Dot plots, bar charts, donut charts

### **4. Team Insights & Comparison**

* Team vs Team head-to-head
* Win % across seasons
* Toss decision impact
* Bat-first vs Chase performance
* Winning margin trends

**Visuals Used:**
Line charts, matrix comparisons, stacked bars

### **5. Venue Insights**

* High-scoring venues
* Best venues for bowlers
* Toss impact by venue
* Average 1st innings score
* Venue-wise win distribution

**Visuals Used:**
Geographic map, boxplots, bar charts

## 7. Business Impact & Insights

### **Sports Analytics Insights**

* Identify top-performing players and teams
* Understand momentum shifts across seasons
* Track individual player form

### **Coaching & Strategy Insights**

* Build match strategies based on venue history
* Choose playing XI based on opposition and ground
* Determine ideal toss decisions

### **Fantasy Cricket Insights**

* Pick consistent players
* Choose high-impact bowlers/batsmen
* Identify undervalued performers
## DashBoard Preview
<img width="797" height="406" alt="IPL Dashboard" src="https://github.com/user-attachments/assets/e198175f-66d3-4656-abce-d4c18edf6b8e" />
