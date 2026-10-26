# HeatWatch Nagpur 🌡️
### Heat-Health Early Warning System

HeatWatch Nagpur is an interactive web-based mini project that demonstrates how temperature, humidity, and air pollution can be analyzed alongside daily heat-related emergency room (ER) visits to support heat-health risk assessment and hospital planning.

The project showcases data cleaning, exploratory data analysis, regression modeling, time-series forecasting, and SQL-based data analysis through an interactive dashboard.

> **Note:** This is an educational demonstration using simulated data. The displayed hospital visits and model outputs are not real Nagpur health records and should not be used for medical decisions.

## ✨ Features

- **Situation Overview:** Summary statistics, temperature trends, correlation heatmap, and ER visit distribution.
- **Data Quality:** Explore missing values, temperature outliers, mean imputation, and interpolation.
- **Risk Model:** Demonstrates feature scaling, temperature binning, seasonal encoding, linear regression, and interactive scenario predictions.
- **Data Sources:** Explains the weather and air-quality data collection pipeline using the Open-Meteo APIs, with a simulated collector demonstration.
- **Data Warehouse:** Demonstrates SQL queries for monthly averages, hottest days, and most polluted days.
- **Forecast:** Visualizes moving averages, trend and seasonal decomposition, and an autoregressive temperature forecast.
- **Interactive Dashboard:** Includes navigation, charts, tooltips, adjustable parameters, and responsive styling.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- SVG-based visualizations
- Python and pandas (demonstrated in code examples)
- scikit-learn (demonstrated in regression examples)
- SQL and SQLite (demonstrated in data warehouse examples)
- Open-Meteo APIs (referenced in the data collection demonstration)
- ARIMA time-series modeling (demonstrated in code examples)


## 📊 Methodology

The dashboard demonstrates the following workflow:

1. Generate a simulated dataset containing temperature, humidity, PM2.5, and daily ER visits.
2. Introduce missing values and invalid temperature readings to demonstrate data-quality issues.
3. Clean the data using outlier handling and interpolation.
4. Explore statistical summaries and correlations.
5. Fit a linear regression model to estimate ER visits from environmental variables.
6. Demonstrate SQL queries for aggregations and high-risk observations.
7. Decompose temperature patterns and evaluate a short-term autoregressive forecast.

## 📁 Project Structure

```text
heatwatch-nagpur/
├── index.html
└── README.md
```

## ⚠️ Limitations

- The dashboard uses simulated data generated in JavaScript.
- The displayed data collector is a demonstration and does not fetch live API data.
- Python, SQL, and ARIMA snippets are educational examples; they are not executed by the HTML dashboard.
- Model performance on simulated data does not establish real-world predictive accuracy.
- The project is not a validated medical or public-health decision-support system.

## 🔮 Future Improvements

- Integrate actual historical weather and air-quality datasets.
- Incorporate verified, anonymized health statistics where available.
- Build a Python backend for model training and evaluation.
- Add a real-time data ingestion pipeline.
- Evaluate forecasting models on held-out real-world data.
- Develop location-specific heat-risk alerts for public-health planning.


