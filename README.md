# 🏏 SMAT Cricket Tournament Dataset

This repository contains structured datasets related to the Smart
Cricket Tournament, covering **match statistics, player batting
performance, player bowling performance, and playoff records**.\
The data can be used for sports analytics, machine learning models, and
visualization projects.

------------------------------------------------------------------------

## 📂 Dataset Files

### 1. `smat_match_statistics.csv`

Match-level information from Smart Cricket Tournament games.

**Columns:**\
- `Date` -- Match date\
- `Team 1` -- First team\
- `Team 2` -- Second team\
- `Winner` -- Winning team\
- `Result` -- Detailed outcome (e.g., "won by 6 wickets")\
- `Venue` -- Match location

------------------------------------------------------------------------

### 2. `smat_player_statistics_batting.csv`

Player-wise batting performance statistics across multiple seasons.

**Columns:**\
- `Player` -- Player name\
- `Team` -- Represented team\
- `Span` -- Playing span (years)\
- `Mat` -- Matches played\
- `Inns` -- Innings batted\
- `NO` -- Not outs\
- `Runs` -- Runs scored\
- `HS` -- Highest score\
- `Ave` -- Batting average\
- `BF` -- Balls faced\
- `SR` -- Strike rate\
- `100` -- Centuries\
- `50` -- Half-centuries\
- `0` -- Ducks\
- `4s` -- Fours hit\
- `6s` -- Sixes hit

------------------------------------------------------------------------

### 3. `smat_playoffs_statistics.csv`

Details of playoff-stage matches (Super League, Semi-Finals, Finals).

**Columns:**\
- `Season` -- Tournament season\
- `Stage` -- Match stage (Super League / Semi-Final / Final)\
- `Date` -- Match date\
- `Team 1` -- First team\
- `Team 2` -- Second team\
- `Winner` -- Match winner\
- `Result` -- Match result description\
- `Venue` -- Match venue

------------------------------------------------------------------------

### 4. `smat_player_statistics_bowling.csv`

Player-wise bowling performance statistics across multiple seasons.

**Columns:**\
- `Player` -- Player name\
- `Team` -- Represented team\
- `Span` -- Playing span (years)\
- `Mat` -- Matches played\
- `Inns` -- Innings bowled\
- `Balls` -- Balls bowled\
- `Overs` -- Overs bowled\
- `Mdns` -- Maiden overs\
- `Runs` -- Runs conceded\
- `Wkts` -- Wickets taken\
- `BBI` -- Best Bowling in an Innings\
- `Ave` -- Bowling average\
- `Econ` -- Economy rate\
- `SR` -- Bowling strike rate\
- `4` -- Four-wicket hauls\
- `5` -- Five-wicket hauls

------------------------------------------------------------------------

## 🔍 Use Cases

-   📊 **Tournament analysis** -- Track team & player performance\
-   🏆 **Playoff insights** -- Identify consistent champions\
-   📈 **Data visualization** -- Build cricket dashboards\
-   🤖 **Machine Learning** -- Train models for outcome prediction,
    performance forecasting\
-   🎮 **Fantasy cricket** -- Support simulations and player ranking
    systems

------------------------------------------------------------------------

## 🚀 How to Use

Clone this repository:

``` bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Load the CSV files into Python (Pandas), R, or Excel.\
Start analyzing, visualizing, or building ML models!

Example in Python:

``` python
import pandas as pd

# Load bowling statistics
df_bowling = pd.read_csv("smat_player_statistics_bowling.csv")
print(df_bowling.head())
```

------------------------------------------------------------------------

## 📜 License

This dataset is provided for **educational and research purposes
only**.\
Data was sourced by scraping publicly available cricket statistics from
**ESPNcricinfo** and **BCCI** websites.
