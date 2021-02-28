# pbp-data

Raw play-by-play jsons from various sources

## Data Sources

### College Football (15k+ games)

```data/cfb/{year (range 2002-2021)}```
Play-by-play JSON files files from ESPN's college football endpoints (`cdn.../playbyplay` and `api/v2/../summary`), in addition to the other box score data, game information, standings, etc.

- drives `dict`
- plays `df` (created by script)
- boxscore `dict`
- header `dict`
- standings `dict`
- timeouts `dict` (created by script)
- scoringPlays `arr`
- winprobability `arr`
- homeTeamSpread `float`
- broadcasts `df`
- videos `arr`
- pickcenter `arr`
- espnWP `df`
- gameInfo `dict`
- season `dict`

```data/cfb_games_info_2002_2020.csv```
  A CSV containing gameId and other game information for college football games from 2002-2020.

### Men's College Basketball (104k+ games)

```data/cbb/{year (range 2002-2021)}```
Play-by-play JSON files from ESPN's men's college basketball endpoints, (`cdn.../playbyplay` and `api/v2/../summary`), in addition to the other box score data, game information, standings, etc.

- gameId `int`
- plays `df` (created by script)
- boxscore `dict`
- header `dict`
- standings `dict`
- timeouts `dict` (created by script)
- scoringPlays `arr`
- winprobability `arr`
- homeTeamSpread `float`
- broadcasts `df`
- videos `arr`
- pickcenter `arr`
- espnWP `df`
- gameInfo `dict`
- season `dict`

```data/cbb_games_info_2002_2021.csv```
  A CSV containing gameId and other game information for men's college basketball games from 2002-2021.

### Women's College Basketball (98k+ games)

```data/wbb/{year (range 2002-2021)}```
Play-by-play JSON files from ESPN's women's college basketball endpoints, (`cdn.../playbyplay` and `api/v2/../summary`), in addition to the other box score data, game information, standings, etc.

- gameId `int`
- plays `df` (created by script)
- boxscore `dict`
- header `dict`
- standings `dict`
- timeouts `dict` (created by script)
- scoringPlays `arr`
- winprobability `arr`
- homeTeamSpread `float`
- broadcasts `df`
- videos `arr`
- pickcenter `arr`
- espnWP `df`
- gameInfo `dict`
- season `dict`

```data/wbb_games_info_2002_2021.csv```
  A CSV containing gameId and other game information for women's college basketball games from 2002-2021.

### WNBA (4k+ games)

```data/wnba/{year (range 2002-2021)}```
Play-by-play JSON files from ESPN's WNBA endpoints, (`cdn.../playbyplay` and `api/v2/../summary`), in addition to the other box score data, game information, standings, etc.

- gameId `int`
- plays `df` (created by script)
- boxscore `dict`
- header `dict`
- standings `dict`
- timeouts `dict` (created by script)
- scoringPlays `arr`
- winprobability `arr`
- homeTeamSpread `float`
- broadcasts `df`
- videos `arr`
- pickcenter `arr`
- espnWP `df`
- gameInfo `dict`
- season `dict`

```data/wnba_games_info_2002_2021.csv```
  A CSV containing gameId and other game information for WNBA games from 2002-2021.

### NBA

```data/nba/{year (range 2002-2021)}```
Play-by-play JSON files from ESPN's NBA endpoints, (`cdn.../playbyplay` and `api/v2/../summary`), in addition to the other box score data, game information, standings, etc.

- gameId `int`
- plays `df` (created by script)
- boxscore `dict`
- header `dict`
- standings `dict`
- timeouts `dict` (created by script)
- scoringPlays `arr`
- winprobability `arr`
- homeTeamSpread `float`
- broadcasts `df`
- videos `arr`
- pickcenter `arr`
- espnWP `df`
- gameInfo `dict`
- season `dict`

```data/nba_games_info_2002_2021.csv```
  A CSV containing gameId and other game information for NBA games from 2002-2021.

### NFL (4.9k+ games)

```data/nfl/{year (range 2005-2021)}```
Play-by-play JSON files from ESPN's NFL endpoints, (`cdn.../playbyplay` and `api/v2/../summary`), in addition to the other box score data, game information, standings, etc.

- gameId `int`
- drives `dict`
- plays `df` (created by script)
- boxscore `dict`
- header `dict`
- standings `dict`
- timeouts `dict` (created by script)
- scoringPlays `arr`
- winprobability `arr`
- homeTeamSpread `float`
- broadcasts `df`
- videos `arr`
- pickcenter `arr`
- espnWP `df`
- gameInfo `dict`
- season `dict`

```data/nfl_games_info_2002_2021.csv```
  A CSV containing gameId and other game information for NFL games from 2002-2021. I am still actively working on the seasons 2005 and prior, but they don't contain play text, which, huh, who knew.
