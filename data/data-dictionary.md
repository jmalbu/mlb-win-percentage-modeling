# Data Dictionary – MLB Team Stats Dataset ⚾

This file documents the variables used in the team-level dataset for modeling win percentage across MLB teams (1974–2024). Each row represents a team’s regular-season performance in a given year.

---

## Team & Season Info

- **Season**:  
  Year the regular season was played (e.g., `2021`).

- **Team**:  
  Standard abbreviation for the MLB team (e.g., `SEA`, `NYY`, `NYM`).

- **Lg**:  
  League affiliation — either `AL` (American League) or `NL` (National League).

---

## Win–Loss Performance

- **W** (Wins): Total wins in the regular season.  
- **L** (Losses): Total losses.  
- **GP**: Games played.  
- **WL%**: Win percentage = `W / GP`.

---

## Batting Statistics

- **Bat#**: Number of batters used.  
- **PA**: Plate appearances.  
- **AB**: At-bats.  
- **R**: Runs scored.  
- **H**: Total hits.  
- **1B**: Singles.  
- **2B**: Doubles.  
- **3B**: Triples.  
- **HR**: Home runs.  
- **RBI**: Runs batted in.  
- **SB**: Stolen bases.  
- **CS**: Caught stealing.  
- **BB**: Walks (base on balls).  
- **SO**: Strikeouts.  
- **BA**: Batting average = `H / AB`.  
- **OBP**: On-base percentage = `(H + BB + HBP) / (AB + BB + HBP + SF)`.  
- **SLG**: Slugging percentage = `(1B + 2*2B + 3*3B + 4*HR) / AB`.  
- **OPS**: On-base plus slugging = `OBP + SLG`.  
- **OPS+**: OPS adjusted for park and league (100 = league average).  
- **TB**: Total bases.  
- **GIDP**: Grounded into double plays.  
- **HBP**: Hit by pitch.  
- **SH**: Sacrifice hits (bunts).  
- **SF**: Sacrifice flies.  
- **IBB**: Intentional walks.  
- **LOB**: Left on base.  
- **R/gm**: Runs scored per game.

---

## Pitching Statistics

- **ERA**: Earned run average = `9 * ER / IP`.  
- **CG**: Complete games pitched.  
- **SHO**: Shutouts.  
- **SV**: Saves.  
- **IP**: Innings pitched.  
- **HA**: Hits allowed.  
- **RA**: Runs allowed.  
- **ER**: Earned runs allowed.  
- **HRA**: Home runs allowed.  
- **BBA**: Walks allowed.  
- **IBBA**: Intentional walks allowed.  
- **SOA**: Strikeouts (pitching).  
- **HBPA**: Hit batters (by pitchers).  
- **BK**: Balks.  
- **WP**: Wild pitches.  
- **BF**: Batters faced.  
- **ERA+**: Adjusted ERA = `100 * (lgERA / ERA)` (park- and league-adjusted).  
- **FIP**: Fielding Independent Pitching.  
- **WHIP**: Walks and hits per inning pitched = `(BB + H) / IP`.  
- **H9**: Hits per 9 innings.  
- **HR9**: Home runs per 9 innings.  
- **BB9**: Walks per 9 innings.  
- **SO9**: Strikeouts per 9 innings.  
- **SO/BB**: Strikeouts-to-walks ratio.

---

## Notes

- Some adjusted metrics (like OPS+, ERA+) normalize values across seasons and ballparks to facilitate fair comparison.
- The dataset combines offensive and defensive team-level summaries for use in regression and time series modeling.

---

For a complete table-format reference with variable types, see [`variable-summary-table.md`](./variable-summary-table.md)

