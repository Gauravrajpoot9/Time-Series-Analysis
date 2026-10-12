# Time Series Analysis using Python

## 📌 Project Overview
This project focuses on **Time Series Analysis and Energy Consumption Forecasting** using Python. It analyzes historical PJME hourly energy consumption data to identify trends, seasonal patterns, and changes in electricity usage over time.

The project applies time series visualization, resampling, decomposition, moving averages, and SARIMAX forecasting to predict future energy consumption.

## 🎯 Objectives
- Analyze historical energy consumption data.
- Identify trends and seasonal patterns.
- Convert hourly data into daily and monthly summaries.
- Smooth fluctuations using moving averages.
- Build a time series forecasting model.
- Evaluate forecasting performance using RMSE.

## 📂 Dataset
**Dataset Name:** `PJME_hourly.csv`

The dataset contains historical PJME electricity consumption records.

- `Datetime`: Date and time of the observation.
- `PJME_MW`: Electricity consumption measured in megawatts.

## 🛠️ Technologies Used
- **Python** – Programming language
- **Pandas** – Data manipulation and resampling
- **NumPy** – Numerical calculations
- **Matplotlib** – Data visualization
- **Statsmodels** – Time series decomposition and SARIMAX forecasting
- **Scikit-learn** – Model evaluation using Mean Squared Error

## 📊 Project Workflow

1. Import the required Python libraries.
2. Load the energy consumption dataset.
3. Inspect dataset information and missing values.
4. Convert the datetime column and set it as the index.
5. Visualize original energy consumption data.
6. Resample hourly data into daily and monthly averages.
7. Decompose the daily time series into trend, seasonal, and residual components.
8. Calculate 7-day and 30-day moving averages.
9. Split the data into training and testing sets.
10. Train a SARIMAX forecasting model.
11. Forecast energy consumption for the next 30 days.
12. Evaluate the forecast using Root Mean Squared Error (RMSE).
13. Visualize actual and forecasted energy consumption.

## 📈 Key Techniques
- Time Series Visualization
- Datetime Indexing
- Daily and Monthly Resampling
- Seasonal Decomposition
- Moving Average Smoothing
- SARIMAX Forecasting
- Train-Test Split
- RMSE Evaluation

## 🚀 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/Gauravrajpoot9/Time-Series-Analysis.git
```

**Step 2: Navigate to the project folder**

```bash
cd Time-Series-Analysis
```

**Step 3: Install the required libraries**

```bash
pip install pandas numpy matplotlib statsmodels scikit-learn jupyter
```

**Step 4: Start Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5:** Open `task3.ipynb` and run the notebook cells in order. Make sure `PJME_hourly.csv` is in the same directory as the notebook.

## 📉 Model Evaluation
The model's forecasting performance is evaluated using **Root Mean Squared Error (RMSE)**.

A lower RMSE generally indicates that the predicted values are closer to the actual values. The notebook calculates the RMSE by comparing the final 30 days of actual observations with the model's 30-day forecast.

## 💡 Applications
- Electricity demand forecasting
- Energy consumption planning
- Identifying consumption trends
- Supporting resource allocation
- Understanding seasonal electricity usage

## 🔮 Future Improvements
- Compare SARIMAX with other forecasting models.
- Experiment with different model parameters.
- Evaluate additional forecasting metrics such as MAE and MAPE.
- Improve forecasting accuracy through parameter tuning.
- Build an interactive dashboard for energy consumption analysis.

## 👨‍💻 Author
**Gaurav Rajpoot**

GitHub: [Gauravrajpoot9](https://github.com/Gauravrajpoot9)

---

⭐ If you find this project useful, consider giving the repository a star!
