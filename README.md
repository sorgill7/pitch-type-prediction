# Pitch Type Prediction

In this project, I fit a model to predict what type of pitch will be thrown next in an at-bat, using game state and historical data about the pitcher. I want to be able to predict what type of pitch will be thrown in the next at bat, using information about the pitcher, the current situation, and the previous pitch. I then scrape live MLB game data and make pitch type predictions in real-time. Note that the scraping script is now out-of-date with mlb.com.

### Data
The data were gathered and published on Kaggle at https://www.kaggle.com/pschale/mlb-pitch-data-20152018. They detail individual atbats and pitches from the 2015 to 2018 seasons.
- atbats.csv (https://www.kaggle.com/datasets/pschale/mlb-pitch-data-20152018?select=atbats.csv)
- pitches.csv (https://www.kaggle.com/datasets/pschale/mlb-pitch-data-20152018?select=pitches.csv)
- games.csv (https://www.kaggle.com/datasets/pschale/mlb-pitch-data-20152018?select=games.csv)
- player_names.csv (https://www.kaggle.com/datasets/pschale/mlb-pitch-data-20152018?select=player_names.csv)

### Files
- Pitches.ipynb: explores the data and fits several models to predict the pitch type that will be thrown in an at-bat
- Scrape3.ipynb: scrapes game data from mlb.com and predicts pitch type in real-time.
