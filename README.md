# March Madness 2024 Bracket Predictive Model

This project develops a TensorFlow-based predictive model for the 2024 March Madness tournament. The model leverages historical game results and team statistics to forecast the outcomes of tournament matchups.

## Data Sets Used

- **MTeams.csv**: Identifies the different college teams present in the dataset. Each school is uniquely identified by a 4-digit ID number. There are 362 teams currently in Men's Division I.
  - Source: [Kaggle - March Machine Learning Mania 2024](https://www.kaggle.com/competitions/march-machine-learning-mania-2024/data)
- **MNCAATourneyDetailedResults.csv**: Provides team-level box scores for many NCAA® tournaments, starting with the 2003 season.
  - Source: [Kaggle - March Machine Learning Mania 2024](https://www.kaggle.com/competitions/march-machine-learning-mania-2024/data)
- **KenPom Barttorvik.csv**: Statistics for every tournament team since 2008 from https://kenpom.com/ and https://www.barttorvik.com/#. The ranks of every statistic are ranked out of all Division I College Basketball Teams.
  - Source: [March Madness Data](https://www.kaggle.com/datasets/nishaanamin/march-madness-data/data?select=KenPom+Barttorvik.csv)
