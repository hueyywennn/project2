# Flight Booking and Customer Reviews
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Project Overview
Worked on a simulation demonstrating the critical role of data science in British Airways' success. The project involves scraping and analyzing customer review data to uncover key insights and building a predictive model to identify factors influencing buying behaviour.

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

## Project Objectives
1. **Data Cleaning & Preprocessing**: Handling missing values, normalizing text, and feature cleaning.
2. **Exploratory Data Analysis (EDA)**: Understanding distribution patterns, trends, and relationships.
3. **Natural Language Processing (NLP)**: Sentiment analysis using VADER and word cloud analysis.
4. **Predictive Modeling**: Implementing classification models to predict customer recommendations.
5. **Model Evaluation & Interpretation**: Assessing model accuracy and analyzing feature importance.

## Machine Learning Models Used
- **Natural Language Processing (NLP)**: VADER sentiment analysis, word cloud visualization.
- **Random Forest Classifier**: Used for predicting customer recommendations.
- **Feature Importance Analysis**: Identifying key factors that influence customer recommendations.
- **Evaluation Metrics**: Accuracy score, confusion matrix, classification report.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, regex, matplotlib
- **Visualization Tools**: plotly, seaborn

## Project Workflow
1. **Data Collection**: Gather customer reviews and flight booking data.
2. **Data Cleaning**: Process missing values, normalize text data, and clean categorical fields.
3. **Exploratory Data Analysis**: Generate summary statistics, visualizations, and sentiment insights.
4. **Feature Engineering**: Extract relevant attributes for better prediction accuracy.
5. **Model Training**: Train a Random Forest Classifier for recommendation prediction.
6. **Model Evaluation**: Analyze accuracy scores, classification reports, and confusion matrices.
7. **Results Interpretation**: Identify key insights from feature importance and sentiment analysis.
