# pbp-data
 Raw play-by-play jsons from various sources

 # Data Sources

 ## College Football
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

## College Basketball
```data/cbb/{year (range 2003-2021)}```
Play-by-play JSON files from ESPN's men's college basketball endpoints, in addition to the other box score data, game information, standings, etc.