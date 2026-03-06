# Daily-Climate-Data-Collector-Agent

# Daily Climate Data Collector Agent

An automated Python pipeline that collects daily climate data from
public APIs, validates it, stores it, and logs the process.

## Features

- Automatic daily climate data collection
- API integration (Open-Meteo / NASA POWER)
- Missing value validation
- SQLite storage
- Logging system
- Cron scheduling

## Tech Stack

Python
Pandas
Requests
SQLite
Cron

## Workflow

Fetch → Validate → Store → Log

## Data Source

Open-Meteo API
NASA POWER API

## Example Output

Date | Temperature | Precipitation
2026-03-05 | 32.4 | 5.2

## Future Improvements

- Multi-location support
- Anomaly detection
- Streamlit dashboard
- Climate trend analysis
