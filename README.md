# Iran Bourse Market Analysis

This project is created for educational purposes.  
It fetches daily data from the Iran Bourse market, extracts and transforms the data using Python, stores it in ClickHouse, and then builds interactive dashboards with Metabase for analysis.

## Tech Stack
- Python (pandas, requests, clickhouse-connect)
- ClickHouse (data warehouse)
- Metabase (visualization)
- Git & GitHub (collaboration)

## Setup Instructions
1. Clone the repo
2. Create a virtual environment: `python3 -m venv venv`
3. Activate it: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run the ETL pipeline: `python main.py`