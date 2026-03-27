# Most Wicket in Cricket Dashboard

## 1. Overview

The Most Wickets dashboard is a complete Tableau analytics tool that lets you see and analyze bowling performance data from cricket matches. This dashboard shows how well cricket teams and individual bowlers can take wickets, how efficient they are at bowling, and how they compare to other teams and bowlers.

## 2. Purpose

This dashboard helps cricket analysts, coaches, team management, and fans find the best bowlers, see how wicket-taking trends can change over time, and make decisions about team selection and strategy based on data. It is a central place to look at how well bowling works in different type of matches, at different places, against different teams.

## 3. Tech Stack<br>

The dashboard was built using the following tools and technologies:
- 📊 Tableau Public – Main data visualization platform used for report creation.
- 🧠 LOD (Level of Detail) expressions – Used for calculated field, and dynamic visuals.
- 📁 File Format – .twbx for development and .png for dashboard previews.

## 4. Data Source

Dataset - most_wickets_200 cricket project.xlsx file is available in this repository.

This dataset is based on cricket matches played by different teams from 1951 to 2025. It contains 14 columns and more than 100 records.

## 5. Visualizations

The dashboard utilizes different types of visualizations to represent data in an easily understandable format, allows for deeper insights into the most wickets in cricket.

**1. Maximum Matches Played by Top 10 Bowlers (Butterfly Chart)**<br>
The chart given in this section is a data visualization chart in a butterfly shape. At the center of this chart, a list of the top 10 players that play the highest number of matches and played the highest innings in matches is given. This chart has two bar charts, one on the left side for the number of matches played by the players and one on the right side for the number of innings played by the player.

**2. Top 10 Players by no. of 5s and 10s (Butterfly Chart)**<br>
The data visualizations in this chart are shaped like a butterfly. The top 10 players who takes most 5s (five wickets) and 10s (ten wickets) are listed in the middle of the chart. This chart has two bar charts, one on the left side displays number of highest 5s taken by a player, and on right side displays number of highest 10s taken by a player.

**3. Best Match Figures (Table)**<br>
The above table is a visualization of best bowling in a game of cricket. It includes information such as a player's name and their bowling figure. For example, M Muralidaran from Sri Lanka has taken 16 wickets and given away 220 runs, i.e., 16/220.

**4. Most Wickets taken by Players(Treemap)**<br>
This visualization is used to represent the "highest number of wickets taken by a single player in his career." This treemap is designed in a way that a player who has taken the highest number of wickets is placed in a larger container and in a darker shade. The name of the player and the total number of wickets are displayed inside the container.

**5. Balls Bowled by Top 10 Players (Bar Chart)**<br>
The top ten players who bowled the most during games are shown in this bar graph. For instance, M. Muralidaran bowled the most bowls (63,132).

## 6. Filters
On the dashboard, tools are used to provide a better experience for the user. On the dashboard, only one filter is used to filter the data, which is a treemap visualization located at the bottom center, providing control over all the visualization data. The user can use the filter by choosing a specific player to filter all the visualized data. This gives the user easy insights into the cricket matches.

## 7. Screenshots

![Dashboard Preview](https://github.com/HRSalet/Most-Wicket-Cricket-Dashboard/blob/main/Dashboard%20Snapshot%20one.png)
