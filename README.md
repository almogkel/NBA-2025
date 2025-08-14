# 🏀 NBA 2025 – Player Comparison & Team Analysis

This project was built in **Tableau Public** and provides an interactive platform for comparison and analysis of player and team statistics from the **2025 NBA Regular Season**.  
The system includes **4 main dashboards** with easy cross-navigation, designed to serve **analysts, coaching staff, and fans** who want both quick insights and the ability to dive deep into advanced metrics.

[Click here to view the project on Tableau Public](https://public.tableau.com/views/NBA2025_17522526240050/NBAPlayersComparison2025Shooting?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🎯 System Purpose & Design Logic
The main goal of this project is to transform simple, tabular NBA statistics into an engaging, visual experience, enabling users to explore the data interactively and gain insights that are hard to see in long, flat tables.
By combining **key performance indicators (KPIs)**, **interactive filters**, and **intuitive visualizations**, users can:
- Quickly identify player strengths and weaknesses.
- Compare performances between players or teams.
- Understand shot distribution and efficiency within context of the league averages.
- Analyze team composition by position and player roles.

---

## 💡 Why This Is More Than Just Tables

These dashboards were built to **transform raw NBA stats into an interactive, story-driven experience**.  
Instead of staring at endless spreadsheets, users get **smart, dynamic visualizations** that combine context, comparison, and intuitive understanding — giving every audience group a clear advantage:

- **For fans:**  
  - Turns cold numbers into live visuals that show style of play, strengths, and weaknesses, letting you *feel* the player or team’s identity.  
  - Makes advanced stats accessible without requiring technical knowledge — just click, filter, and see.  
  - Settles “who’s better” arguments with visual facts, not just opinions.  

- **For analysts & coaching staff:**  
  - Cuts down the time needed to spot problems or opportunities — one heatmap or scatter plot can reveal patterns that would take hours to find manually.  
  - Puts **context alongside results** — not just shooting percentages, but where shots come from, in what volume, and how that compares to league norms.  
  - Supports tactical decisions, lineup construction, and practice planning with quick, data-driven insights.

In short — instead of an endless Excel table, this is a **visual language for basketball data** that deepens understanding, saves time, and enriches both viewing and analysis.

---

## 📊 Dashboard Structure

### 1️⃣ NBA Player Comparison 2025
A general comparison between two players based on key game statistics.
- **Filters:** Select team and player for each side.
- **Quick Navigation:** Jump to any of the 4 dashboards.
- **Data:** Age, number of games played, number of games started, stats per game (minutes, points, assists, rebounds, steals, blocks, fouls, turnovers), triple-doubles.
- **Visualization:** Side-by-side bar charts and KPIs for quick comparison.
- **Why it works better:** Instead of flipping between separate player pages, both players’ stats are side-by-side with proportional bar charts.  
  - **Coaches & scouting staff** can quickly find players who best fit their team’s style, compare current roster players with league players, and make data-driven decisions for recruitment or rotations.
  - **Fans** can visually compare players side-by-side to understand differences in style, efficiency, and contribution at a glance, and can quickly settle “who’s better” debates with clear, interactive visualizations.

---

### 2️⃣ NBA Player Comparison 2025 – Shooting
A detailed shooting comparison between two players.
- **Filters:** Select team and player for each side.
- **Quick Navigation:** Jump to any of the 4 dashboards.
- **Data:** Average shot distance, FG% for 2P and 3P, percentage of shots from 2P and 3P, FT%, average shots per game.
- **Visualization:** Side-by-side bar charts and KPIs for quick comparison, showing shooting efficiency and shot distribution.
- **Why it works better:** It’s not just percentages — volume is shown alongside efficiency.  
  - **Coaches** can see if a player’s high FG% is from selective shooting or heavy usage.  -- לא בטוח לכבי זה
   - **Fans** can appreciate a player’s true shooting style — whether they’re a paint-dominator or a perimeter sniper.

---

### 3️⃣ Player Summary
A season summary for a single player.
- **Filters:** Select team and player.
- **Quick Navigation:** Jump to any of the 4 dashboards.
- **Dynamic Team Logo** displayed.
- **Player Card:** Age, team, position.
- **Player Stats Per Game Card:** Minutes, points, assists, rebounds, steals, blocks, turnovers, fouls, FG%, 3P%, FT%.
- **KPI Card Season Achievements:** Individual awards such as All-Star appearances, All-NBA team selections etc.
- **Shot Distribution:** Field goal attempts by 5 ranges (0–3 ft, 3–10 ft, 10–16 ft, 16 ft–three-point, three-point) as a percentage of total attempts.
- **Shooting Heatmap:** FG% by court range compared to league averages. Blue = below average, red = above average. Circle size = shot volume.
- **Shooting by Type:** FG% and made shots for 2P, 3P, and free throws. Green bars show made shots, top bar shows missed attempts.
- **Why it works better:**  
  - **Coaches** can instantly visualize a player’s scoring zones to build plays that fit their comfort areas — or expose opponent weaknesses.
  - **Fans** get to “see” the player’s shooting habits, not just read percentages.
  - In addition to shooting analysis, the left side provides a complete player profile — age, team, position, per-game averages, and notable season achievements awards.
---

### 4️⃣ Team Summary
An overall season view for a selected team in 2025.
- **Filters:** Select team.
- **Quick Navigation:** Jump to any of the 4 dashboards.
- **Dynamic Team Logo** displayed.
- **Top Performers (KPI):** Team leader in points, assists, rebounds, and FG%. (Per Game)
- **Player Table:** 2P%, 3P%, FT%, % of shots from 2P and 3P for each player.
- **Position Table:** Average points, assists, rebounds, shooting percentages (2P, 3P, FT), and average field goal attempts – by position.
- **Team Shooting Heatmap:** FG% and shot distribution by range, with the same color & size logic as Player Summary.
- **Scatter Plots:**
  1. Assists vs. turnovers per game – quickly spots good playmakers vs. turnover-prone players.
  2. Shooting efficiency vs. average shot attempts per game – bubble size shows average minutes played.
- **Why it works better:**
   - The dashboard combines individual player stats (Player Table), positional analysis (Position Table), and visualizations (Heatmap, Scatter Plots) to give a holistic view of the team.

  - **Coaching staff:**
    - Use **Top Performers** to anchor scouting focus and identify who drives outcomes.  
    - The **Player Table** exposes **shot-diet extremes** (e.g., 3P-heavy wings vs. paint bigs) for targeted scheme tweaks.  
    - The **Position Table** clarifies **positional strengths/gaps** (e.g., low AST from guards or poor 3P% at forward), informing **lineup construction** and **development priorities**.  
    - The **Team Heatmap** shows where the team is taking shots and their shooting percentages from each range. By comparing these percentages to league averages, coaches can see which areas the team excels in and which need improvement, enabling informed decisions on        adjusting offensive strategies and strengthening the team’s playing style.  
    - The **Scatter Plots** quickly surface turnover issues and identify **high-usage, high-efficiency** scorers versus volume-without-return — ideal for **rotation and matchup** decisions.  
  - **Fans:** Understand the team’s **identity** (where shots come from, who creates, who finishes),*why* their team wins or struggles and why certain lineups work — far beyond a box score.



---

## 🛠 Tools & Technologies
- **Tableau Public** – For building interactive visualizations.
- **Excel** – For initial data cleaning and preparation.

---

## 📌 Intended Audience
- **Analysts:** For statistical deep-dives and performance breakdowns.
- **Coaching staff:** For scouting reports, rotation planning, and player development tracking.
- **Fans:** For exploring their favorite players' and teams' performance beyond basic box scores.
