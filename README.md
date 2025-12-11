# 🌦️ Weather API ETL Pipeline

## 🔹 Overview
This project is an **ETL (Extract, Transform, Load) pipeline** for weather data. It fetches live weather information from a public API, cleans and transforms it, and stores it into a structured database for analysis or visualization. This pipeline can be scheduled to run periodically to maintain an up-to-date weather dataset.

---

## 📚 Topics Covered
- 🌐 **API Integration** – Fetching live weather data using Python requests.
- 🧹 **Data Cleaning** – Handling missing values, formatting timestamps, and standardizing units.
- 🔄 **Data Transformation** – Deriving useful metrics like temperature in Celsius/Fahrenheit, humidity levels, and weather categories.
- 💾 **Data Loading** – Storing processed data into CSV files or databases like PostgreSQL/SQLite.
- 📊 **Feature Engineering** – Adding features like “Feels Like Temperature” and “Weather Severity Index”.
- 🛠️ **Automation** – Scheduling ETL runs with cron jobs or Airflow (optional).

---

# **How to Run**

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/weather-etl-pipeline.git
cd weather-etl-pipeline
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

3. **Run the ETL pipeline:**
```bash
python etl_pipeline.py
```
