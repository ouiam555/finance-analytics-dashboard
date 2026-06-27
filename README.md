# Finance Analytics — Interactive Dashboard

Interactive financial analytics dashboard built with Python and Streamlit, backed by a PostgreSQL database.

## Overview

An end-to-end data application that connects to a PostgreSQL database, transforms financial data through a lightweight ETL pipeline, and presents it through an interactive multi-page Streamlit dashboard.

## Tech Stack

**Python** · **Streamlit** · **PostgreSQL** · **Pandas** · **Plotly**

## Project Structure

```
├── app.py             # Main Streamlit entry point
├── pages/             # Dashboard sub-pages
├── utils/             # DB connection and data helpers
├── .env.example       # Environment variable template
├── .gitignore
└── requirements.txt
```

## How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your DB credentials

# Launch dashboard
streamlit run app.py
```

## Features

- Financial KPI overview (revenue, cost, margin)
- Time-series trend charts
- Category and segment breakdown
- Interactive date range filters
