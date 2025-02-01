# NYC-Taxi-Trip-Duration-Prediction


## Project Overview
This project aims to predict the duration of taxi trips in New York City using historical trip data. By leveraging machine learning techniques, we analyze various factors such as pickup and drop-off locations, trip distance, and time of day to build predictive models.

## Business Understanding
### Stakeholders:
- Taxi service operators
- City transportation authorities
- Passengers looking for estimated ride times

### Business Problem:
Accurate trip duration prediction can help optimize taxi dispatching, improve passenger experience, and enhance traffic planning. This project focuses on building a robust model that provides precise trip duration estimates based on historical data.

## Data Understanding
### Dataset Used:
- **2017 NYC Yellow Taxi Trip Data**
- **NYC Trip Prediction Mean Values**

### Key Features:
- Pickup and Drop-off Location Coordinates
- Passenger Count
- Trip Distance
- Timestamp Features (Date, Time, Day of Week, Month, etc.)

### Data Limitations:
- Incomplete GPS data for some trips
- Potential biases in recorded trip times due to traffic conditions
- Possible data inconsistencies in fare calculations

## Modeling and Evaluation
### Models Used:
- Linear Regression
- Decision Trees
- Random Forest
- Gradient Boosting (XGBoost, LightGBM)

### Evaluation Metrics:
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- R-Squared Score

## Conclusion
### Key Findings:
- Time of day and trip distance are significant predictors of trip duration.
- Traffic congestion leads to high variance in trip durations.
- Model performance improves significantly with feature engineering techniques.

### Recommendations:
- Implement real-time traffic data integration for improved predictions.
- Optimize taxi dispatching using predicted trip times.
- Further refine the model using deep learning approaches.

### Future Steps:
- Explore alternative data sources such as weather and event schedules.
- Deploy the model as an API for real-time trip duration estimation.
- Improve feature selection and hyperparameter tuning.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook.
4. Ensure datasets are placed in the same directory as the notebook.

## License
[Specify license, e.g., MIT License]

