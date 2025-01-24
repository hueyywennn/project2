# Flight Booking and Customer Reviews
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Project Overview
Web scraping, analyzing customer review data regarding flight airlines, and building a predictive model to identify factors influencing success booking behaviour.

| Name                 | Description                                                                 |
|--------------------------|---------------------------------------------------------------------------------|
| `Review`                | Customers' comments on specific airlines flown                                   |
| `Rating`                | Overall rating on specific airlines flown                                       |
| `Country`               | Customers' country of origin                                                   |
| `Type Of Traveller`     | Type of customer (e.g., Business Traveler, Leisure Traveler, etc.)              |
| `Seat Type`             | Class of the seat (e.g., Economy, Business, First Class)                        |
| `Date Flown`            | Date when the customer flew with the airline                                    |
| `Recommended`           | Indicates if the customer recommends the airline (Yes/No)                      |
| `Aircraft`              | Type or model of the aircraft flown                                             |
| `Seat Comfort`          | Customer's rating of seat comfort                                               |
| `Cabin Staff Service`   | Customer's rating of the service provided by cabin staff                        |
| `Food & Beverages`      | Customer's rating of food and beverages                                         |
| `Inflight Entertainment`| Customer's rating of inflight entertainment options                             |
| `Ground Service`        | Customer's rating of ground services provided by the airline                    |
| `Wifi & Connectivity`   | Customer's rating of the onboard wifi and connectivity                          |
| `Value For Money`       | Customer's rating of the overall value for money                                |
| `Month Flown`           | Month when the flight was taken                                                 |
| `Year Flown`            | Year when the flight was taken                                                  |
| `Departures`            | Departure airport or city                                                      |
| `Arrivals`              | Arrival airport or city                                                        |
| `Layover`               | Indicates if there was a layover and its details (if applicable)                |

### Features
1. **Data Cleaning**
  -	Feature cleaning: remove symbols in the review column
  -	Handle missing values: delete the entire row if all is empty
  -	Data Normalization: normalize texts in departures, arrivals, and layovers columns using airport IATA codes
2. **Exploratory Data Analysis (EDA)**
  -	Statistical Summaries: mean, median, variance, and standard deviation
  -	Distribution Plots: pie plots, bar plots, line plots
3. **Machine Learning Models**
  - NLP: word cloud analysis, sentiment analysis
  -	Classifier Algorithms: Random Forest
  -	Model Evaluation: accuracy score, classification report, confusion matrix
  -	Predictive Modeling: Random Forest
  -	Model Interpretation: Feature Importance, Permutation Importance
4. **Interactive Visualizations**
  -	null

## Tools used
1. **Programming Language** 
  - Python
2. **Libraries**
  - pandas, numpy, scikit-learn, matplotlib, regex
3. **Visualization Tools**
  - plotly, seaborn
