# Enterprise Automated Data-Cleaning Pipeline

A production-ready, object-oriented Python pipeline built with **Pandas** and **NumPy** designed to programmatically ingest, validate, clean, and standardize chaotic corporate data assets in milliseconds.

## 💼 Business Value Proposition
Manual data cleaning drains administrative employee hours and introduces devastating human analytical errors. This data-cleaning architecture completely eliminates manual intervention:
* **Zero Manual Effort:** Processes thousands of broken database rows instantly in less than 0.02 seconds.
* **Data Integrity Enforcement:** Prevents downstream financial or operational reporting system crashes by programmatically resolving missing metrics, invalid types, and duplicate entries.
* **Low Technical Overhead:** Completely built using open-source Python infrastructure, saving thousands of dollars in expensive proprietary data license costs.

## 🛠️ Core Capabilities & Architecture
The system functions as a modular pipeline Class that can be easily plugged into any automated backend cron-job or server data stream:
1. **Robust Ingestion:** Automatically reads and validates incoming CSV/data file schemas.
2. **Strict Schema Type Enforcement:** Programmatically converts loose object text strings into true datetime formats and numeric float calculations.
3. **Smart Missing Value Resolution:** Implements targeted business rule strategies (dropping critical empty identifiers while imputing mathematical medians/modes for minor fields).
4. **Anomalies & Duplicate Purging:** Deduplicates datasets completely to preserve clean database keys.

## 🚀 Technical Requirements
* **Python 3.x**
* **Pandas**
* **NumPy**

## 📂 Project Structure
```text
├── data/                  # Non-sensitive raw sample datasets for demonstration
├── notebooks/             # Exploratory analysis and pipeline sandbox (.ipynb)
├── src/                   # Production-grade source code Class (.py)
└── README.md              # Project business and technical documentation
```
