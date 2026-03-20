# Flight-Delays-Prediction-Model

Shea:
- Combined 10000+ global weather csv files into one U.S. weather csv
- Cleaned weather dataset by handling missing values, removing unnecessary columns
- Created preliminary weather visualization to show data spread across the U.S.
- Added cities to weather data using GeoPandas
- Conducted preliminary analysis of combined flight weather dataset
- Created visualizations to look at main correlations and delays by airline, time, and weather-feature
- Developed and trained binary classifier ML models (SGDClassifier, LogisticRegression, HistGradientBoostingClassifier)
- Attempted to use over- and under-sampling to balance classes
- Evaluated by average precision, recall, and f1-score
- Used validation score to ensure no overfitting
- Analyzed feature importances

Sahiti: 
- Web Scraped BTS website for flight departure information using Selenium
- Researched top airports and airlines
- Scraped 100 airports and 4 airlines
- Cleaned and filtered flight data
- Combined origin and destination airport locations with flight data
- Mapped airports to nearest weather stations and combined with flight data
- Cleaned combined data
- Filtered dataset to confirmed weather delayed flights with recorded weather events
- Dropped irrelevant and leakage columns
- Engineered combined origin and destination weather features
- Binned delay durations into severity tiers (Minor, Moderate, Severe)
- Developed, trained, and evaluated bin classification models (RandomForestClassifier, GradientBoostingClassifier, XGBClassifier, LGBMClassifier)
- Developed, trained, and evaluated regression models (XGBRegressor, LGBMRegressor)
- Compared model performance and analyzed feature importances
