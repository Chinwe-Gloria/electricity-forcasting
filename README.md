# Electricity Consumption Forecasting with Facebook Prophet

## Project Overview

This project is part of my **30-Day DeepTech Building Challenge** (Day 19).
I applied **Time Series Analysis and Forecasting** techniques to the **Electricity Consumption Dataset** to predict future energy usage patterns.

The main focus was to:

* Understand time series concepts (trend, seasonality, noise)
* Explore electricity consumption patterns
* Forecast future consumption using **Meta’s Facebook Prophet** library


## Dataset

**Source:** https://www.kaggle.com/datasets/thedevastator/240000-household-electricity-consumption-records


## Tools & Libraries

* Python (Google Colab)
* pandas
* matplotlib
* prophet (Facebook Prophet)


## Key Steps

1. **Data Cleaning & Preparation**

   * Converted date and time columns to datetime format
   * Handled missing values
   * Filtered dataset to focus on `Global_active_power`

2. **Forecasting**

   * Modeled the dataset using **Facebook Prophet**
   * Forecasted energy consumption for the next 30 half-hour intervals

3. **Visualization**

   * Displayed actual vs predicted consumption
   * Decomposed trend and seasonality components


## Results

The model successfully captured:

* Long-term **trend**
* Strong **seasonal daily and weekly patterns**
* Noise and variability in electricity usage

The forecast gives actionable insights into expected energy demand.


## Key Learnings

* Time series data has structure: **Trend + Seasonality + Noise**
* Facebook Prophet is powerful for fast and interpretable forecasting
* Data cleaning and feature engineering are critical for model accuracy


## Conclusion

This project demonstrates a real-world application of data science and machine learning in energy management.
It serves as a foundation for more advanced energy forecasting and optimization projects.

If you want, I can also help you **customize it with your actual file names and image** from your Colab.
👉 Just say **"yes, help me customize it too."**
