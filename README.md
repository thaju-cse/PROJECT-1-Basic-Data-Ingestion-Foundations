# Basic Data Ingestion (Foundation)

This is a simple project which get JSON file from open weather api and
simple transformations in CSV file.

---

## Overview
This project demonstrates API based data extracting in JSON file format and
basic transformations like removing white spaces, upper case to lower case.

---

## Features
- Real-time weather data fetching using APIs.
- Basic transformations of CSV files.

---

## Tech Stack
```
|---------------------------------------------------------|
|Category       |Tools                                    |
|---------------|-----------------------------------------|
|Language       |Python                                   |
|Libraries      |requests, pandas, datetime, json, pathlib|
|OS             |Ubuntu(WSL)                              |
|---------------------------------------------------------|
```
---

## Project Architecture
1. Fetch weather data from API
2. Store raw data into a JSON file
3. Transform a sample CSV

---

## Installation
```bash
git clone https://github.com/thaju-cse/PROJECT-1-Basic-Data-Ingestion-Foundations
cd PROJECT-1-Basic-Data-Ingestion-Foundation
pip install -r requirements.txt
```
---

## Folder Structure
```

├── README.md
├── data
│   ├── processed
│   │   └── sample_data_cleaned.csv
│   └── raw
│       ├── sample_csv.csv
│       ├── weather_20260204_025758.json
│       └── weather_20260204_030019.json
├── md
├── requirements.txt
└── src
    ├── fetch_api_data.py
    └── process_csv.py

5 directories, 9 files
```
---

## Learning Outcomes
- Hands on experience in requests and pandas modules

---

## Future Enhancements
- Automating the fetching weather frequently using CRON jobs
- Automating the Transformations of extracted data
- visualizing using tools
## Author
**Shaik Thajuddhin**
---
**Aspiring Data Engineer**
