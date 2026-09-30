# Exchange Rates Aggregator

A Python program that downloads historical exchange rates from the Frankfurter API and summarizes changes in CAD exchange rates.

## Data source

Data is retrieved from the Frankfurter API for CAD to USD, EUR, and GBP exchange rates from January to June 2024.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt