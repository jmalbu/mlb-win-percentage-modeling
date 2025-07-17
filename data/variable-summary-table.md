# Data Dictionary – MLB Team Stats Dataset

Each row represents an MLB team’s regular-season performance in a given year (1974–2024).

| Variable | Description | Type |
|----------|-------------|------|
| Season | Year the regular season was played (e.g., 2021) | Numeric |
| Team | MLB team abbreviation (e.g., SEA, NYY) | Categorical |
| Lg | League: AL or NL | Categorical |
| W | Total wins | Numeric |
| L | Total losses | Numeric |
| GP | Games played | Numeric |
| WL% | Win percentage = W / GP | Numeric |
| Bat# | Number of batters used | Numeric |
| PA | Plate appearances | Numeric |
| AB | At-bats | Numeric |
| R | Runs scored | Numeric |
| H | Hits | Numeric |
| 1B | Singles | Numeric |
| 2B | Doubles | Numeric |
| 3B | Triples | Numeric |
| HR | Home runs | Numeric |
| RBI | Runs batted in | Numeric |
| SB | Stolen bases | Numeric |
| CS | Caught stealing | Numeric |
| BB | Walks (base on balls) | Numeric |
| SO | Strikeouts (batters) | Numeric |
| BA | Batting average = H / AB | Numeric |
| OBP | On-base percentage = (H + BB + HBP) / (AB + BB + HBP + SF) | Numeric |
| SLG | Slugging percentage = (1B + 2\*2B + 3\*3B + 4\*HR) / AB | Numeric |
| OPS | On-base + slugging | Numeric |
| OPS+ | OPS adjusted for park and league (100 = league avg) | Numeric |
| TB | Total bases | Numeric |
| GIDP | Grounded into double plays | Numeric |
| HBP | Hit by pitch | Numeric |
| SH | Sacrifice hits (bunts) | Numeric |
| SF | Sacrifice flies | Numeric |
| IBB | Intentional walks | Numeric |
| LOB | Left on base | Numeric |
| R/gm | Runs scored per game | Numeric |
| ERA | Earned run average = 9 * ER / IP | Numeric |
| CG | Complete games | Numeric |
| SHO | Shutouts | Numeric |
| SV | Saves | Numeric |
| IP | Innings pitched | Numeric |
| HA | Hits allowed | Numeric |
| RA | Runs allowed | Numeric |
| ER | Earned runs allowed | Numeric |
| HRA | Home runs allowed | Numeric |
| BBA | Walks allowed | Numeric |
| IBBA | Intentional walks allowed | Numeric |
| SOA | Strikeouts by pitchers | Numeric |
| HBPA | Hit batters by pitchers | Numeric |
| BK | Balks | Numeric |
| WP | Wild pitches | Numeric |
| BF | Batters faced | Numeric |
| ERA+ | Adjusted ERA (100 * lgERA / ERA) | Numeric |
| FIP | Fielding Independent Pitching | Numeric |
| WHIP | Walks and hits per inning pitched | Numeric |
| H9 | Hits per 9 innings | Numeric |
| HR9 | Home runs per 9 innings | Numeric |
| BB9 | Walks per 9 innings | Numeric |
| SO9 | Strikeouts per 9 innings | Numeric |
| SO/BB | Strikeouts-to-walks ratio | Numeric |

---

*Note: Some metrics (e.g., OPS+, ERA+) are normalized by league and ballpark to enable fair comparison across teams and seasons.*

See the full [Data Dictionary](./data-dictionary.md) for context, formulas, and categorized descriptions.
