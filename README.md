# Premier League Predictive Analysis

## Project Aim
This project aims to develop a predictive model for analysing premier league data from a number of sources in order to predict the optimal strategy in the selection of players for [fantasy premier league](https://fantasy.premierleague.com/).

### Acronyms:
PL - Premier League, when discussing the professional players in the premier league.

FPL - Fantasy Premier League, when discussing fantasy league players.

## Status
The project is currently in development - collecting data.

## FPLLeaguePlot
This notebook extracts a given set of FPL players' total points per game week via the FPL API.

## FPLPlayerStats
This notebook extracts data on PL players and their advanced stats as calculated by FPL, through the FPL API.

## PLScrapeElos
This notebook web scrapes PL data from non-API available information, such as current table position and global elo ratings.

## PLUnsubscribed
This notebook will import data from PL/FPL paid-API services in the future.

## PLTeamPredict
This notebook will aim to predict the likelihood of PL teams winning against other teams given certain factors such as:
- Home vs Away

Items still to be implemented in this model:
- Elo difference
- Referee in charge
- Day of the week and time of day
- Rest period
- Predicted squad strength

## Future Additions
- After data has been collected, the PLTeamPredict model should implement the items still outstanding. 
- Live betting odds to be factored in
- Notebook to predict individual player contributions to be created

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
