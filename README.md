FIFA World Cup Business Intelligence Project (1930–2022)

This Business Intelligence project focuses on analyzing the FIFA World Cup from 1930 to 2022 in order to understand historical trends, evaluate team performance, and identify key factors influencing match outcomes. The project also includes a predictive component based on historical and recent data.

📊 Data Sources

The project is built on multiple structured datasets:

World Cups

This dataset contains historical information about each World Cup edition, including:

Host countries
Winners and runners-up
Number of participating teams
Total goals scored per tournament
General statistics per edition

The 2022 World Cup data was enriched and completed to ensure consistency and accuracy in analysis.

World Cup Matches

This table includes all matches played in FIFA World Cup history, providing:

Competing teams
Match scores
Tournament phases
Match results

It is used for detailed performance and competition analysis across editions.

International Matches

This dataset includes international matches outside the World Cup. It is used to:

Analyze team form outside the tournament
Study opponent behavior and performance
Improve predictive modeling

The variable Win Conditions was removed due to limited analytical value. The Home Stadium feature indicates whether a match was played in a country belonging to one of the participating teams.

World Cup Squads (2022)

This dataset contains the squad lists of all teams participating in the 2022 World Cup, enabling player-level and team composition analysis.

World Cup Groups (2022)

This dataset defines group-stage compositions for the 2022 World Cup.

World Cup Matches 2022

This dataset focuses specifically on the 2022 edition. Data preprocessing steps included:

Imputation of missing home/away team values
Interpretation of ranking-based variables (e.g., W63–L1, where W represents the winner’s FIFA ranking and L the loser’s ranking)

📈 Analysis Performed
1. World Cup Evolution Analysis

This section explores how the tournament has evolved over time using key performance indicators such as:

Number of participating teams
Total number of matches
Average goals per match
Goal distribution across competition phases
Evolution of tournament competitiveness
2. National Team Performance Analysis

This analysis evaluates national teams based on:

Total participations
Number of titles won
Final appearances
Historical achievements
Top 10 most successful countries
3. Performance Factors Analysis

We investigated the key determinants of match outcomes using historical and recent data:

FIFA ranking differences
Home advantage
Recent team form
Average goals scored and conceded
Win percentage
Goal difference
4. Opponent Profiling

A dedicated dashboard provides a detailed profile of each national team, including:

Key players
Player distribution across leagues
Recent performance indicators
Offensive and defensive statistics
Win rate and goal differential

This allows for in-depth comparison between teams before matches.

5. Predictive Modeling

A predictive model was built using data from 1930 to 2022 to estimate match outcomes.
The model leverages historical performance, ranking data, and recent form to predict probabilities of victory.

🛠️ Tools & Technologies
Power BI
Power Query
DAX
Data Cleaning & Preprocessing
Data Modeling
Data Visualization
Predictive Analytics
