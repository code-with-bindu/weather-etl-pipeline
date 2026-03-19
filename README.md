
# 🌍 Automated Weather ETL Pipeline

## Project Overview
An automated data engineering pipeline that extracts real-time weather data from a REST API for 5 global cities, transforms it, stores it in a SQLite database, and generates an analysis report.

## Features
- Extracts live weather data using Open-Meteo REST API
- Transforms and structures raw API data using Python
- Loads cleaned data into SQLite database
- Generates automated analysis report using SQL queries
- Identifies hottest, most humid and windiest cities globally

## 🛠️ Technologies Used
- Python
- REST API (Open-Meteo)
- SQLite Database
- Google Colab
- SQL

## 📊 Pipeline Architecture
Extract (API) → Transform (Python) → Load (SQLite) → Analyze (SQL)

## 🌐 Cities Covered
- Tokyo, Japan
- Mumbai, India
- New York, USA
- London, UK
- Sydney, Australia

## 📈 Sample Output
- 🔥 Hottest City: Mumbai — 26.9°C
- 💧 Most Humid City: Tokyo — 90.0%
- 💨 Windiest City: London — 8.6 km/h

## ▶️ How to Run
1. Open the .ipynb file in Google Colab
2. Run all cells in order
3. Pipeline executes automatically end to end
