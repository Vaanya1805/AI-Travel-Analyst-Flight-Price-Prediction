# AI Travel Analyst – Flight Price Prediction

## About the Project

This is a beginner machine learning project focused on analyzing flight prices and predicting the price of a flight.

I worked with flight data and used Python, data analysis, visualization, and a Random Forest Regression model.

## What I Did

- Cleaned and prepared the flight dataset
- Converted flight duration into hours
- Analyzed flight prices by airline and travel class
- Compared flight distance with flight price
- Checked correlations between numerical features and price
- Built a Random Forest Regression model
- Evaluated the model using MAE, RMSE, and R²

## Dataset

- Original rows: 100,000
- Cleaned rows: 64,071
- Target variable: `Price`

The dataset contains information such as airline, source, destination, travel class, flight distance, stops, passengers, and duration.

## Model

I used a Random Forest Regressor to predict flight prices.

The model uses different flight details such as airline, travel class,
distance, stops, passengers, and duration to make a price prediction.

I used an 80/20 train-test split to train and evaluate the model.
## Results

- MAE: 15,718.65
- RMSE: 49,995.45
- R² Score: 0.5894

## Example Prediction

For a sample flight from **Hyderabad to Mumbai**, the model predicted a price of approximately **7,205.26**.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## What I Learned

Through this project, I practiced the basic machine learning workflow, including data cleaning, visualization, feature preparation, model training, and evaluation.
