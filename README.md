FBI Crime Forecasting – Time Series Model
Project Overview

This project implements a time series forecasting model to predict monthly crime counts using historical data. The model is built using Meta's Prophet algorithm, a powerful tool designed for analyzing and forecasting time series data.

The goal of this project is to demonstrate how machine learning techniques can be applied to crime trend analysis, allowing users to estimate future crime counts based on past patterns.

The project was developed in Google Colab using Python and focuses on simplicity, making it a useful learning resource for beginners interested in time series forecasting and predictive analytics.
Key Features

Forecasts monthly crime counts using historical data

Uses Prophet (by Meta/Facebook) for time series regression

Handles trend and seasonality in crime patterns

Built and executed in Google Colab

Beginner-friendly implementation for learning forecasting models

Technologies Used

Python

Prophet (Meta/Facebook)

Pandas

Matplotlib

Google Colab
Dataset

The model uses historical crime data from the FBI crime statistics dataset, which contains records of crime occurrences over time.

The dataset is processed to:

clean missing values

structure timestamps for time series analysis

aggregate crime counts by month

Model Workflow

Data preprocessing and cleaning

Formatting data for Prophet (ds and y columns)

Training the Prophet forecasting model

Generating future predictions

Visualizing trends and forecast results

Example Output

The model generates:

Forecasted monthly crime counts

Trend analysis

Seasonality visualization

Confidence intervals for predictions

These results help illustrate how crime patterns may evolve over time.

How to Run the Project

Open the project notebook in Google Colab

Install Prophet:

pip install prophet

Run the notebook cells sequentially

View the generated forecasts and plots

Future Improvements

Add support for multiple crime categories

Build a real-time dashboard

Integrate interactive visualizations

Expand dataset coverage for higher accuracy

Learning Outcomes

Through this project, I gained practical experience in:

Time series forecasting

Data preprocessing

Model training and evaluation

Visualization of predictive analytics results

Author

Mehek Pathan
Aspiring AI and Data Science student interested in applying machine learning to real-world problems.
