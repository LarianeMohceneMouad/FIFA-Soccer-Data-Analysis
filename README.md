# FIFA-Soccer-Data-Analysis
Studying FIFA Soccer dataset

## Introduction
### Dataset Description
This soccer database comes from Kaggle, It contains:
- +25,000 matches
- +10,000 players
- +11 European Countries with their lead championship
- Seasons 2008 to 2016
- Players and Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates
- Betting odds from up to 10 providers
- Detailed match events (goal types, possession, corner, cross, fouls, cards etc…) for +10,000 matches

### Available Datasets
- country : Contains 11 countries, with country names their IDs
- league : Contains 11 leagues, with league names, IDs and associated country names
- match : Contains 115 column and 25979 match records
- player : Contains data of 11060 player and player features such as : player_name, birthday, weight, height
- player Attributes : Contains players characteristics from different dates
- team : Contains 299 teams, with Id, long name, short name
- team Attributes : Contains 1458 different records of game plans ( team attributes )


### Relationship between Datasets
- country & league : country_id
- league & match : league_id
- match & player : player id, player_api_id, player_fifa_api_id
- player & player Attributes : player_id, player_api_id, player_fifa_api_id
- match & team : home_team_id, away_team_id
- team & team Attributes : team_id

### Question(s) for Analysis
- What team attributes lead to the most victories
- what is the playing strategy (game plan)
- What teams improved the most/least over the time period
- What players are the best players
- Extra sub question :
  - Youngest players
  - Best youngest player
  - Oldest player
