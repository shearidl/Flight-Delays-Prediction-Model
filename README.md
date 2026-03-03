# Flight-Delays-Prediction-Model

Shea:
- Combined 10000+ global weather csv files into one U.S. weather csv
- Cleaned weather dataset by converting missing values from numbers to NaN, removed unnecessary columns
- Created preliminary weather visualization
- Added cities by longitude and latitude using GeoPandas; created new combined csv

Sahiti: 
- Web Scraped BTS website for flight departure information using Selenium
- Researched top airports and airlines
- Scraped 100 airports and 4 airlines
- Cleaned and filtered flight data
- Combined origin and destination Airport locations (latitude and longitude) with flight data
- Created a tree to map airports to nearest weather stations, combined with flight data
- Combined weather and flight data based on nearest weather station to destination and origin
- Cleaned combined data
