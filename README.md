
# GRM Project - QUIC Traffic Preprocessing Pipeline

This project contains a Jupyter notebook (`pipeline.ipynb`) for cleaning and transforming QUIC network traffic data to prepare it for machine learning tasks like anomaly detection.

## What It Does

- Loads flow-level data from `dataset.csv`
- Cleans and fills missing values
- Converts IPs, ports, and flags into numeric formats
- Labels traffic (e.g., DDoS, brute force, SQLi) if present
- Saves the cleaned dataset for ML use

## Requirements

- Python 3.x
- Libraries: `pandas`, `ipaddress`

Install with:
```bash
pip install pandas ipaddress
```

## How to Use

1. Place `dataset.csv` in the same folder.
2. Open `pipeline.ipynb` in Jupyter or VSCode.
3. Run all cells to generate the cleaned data.

## Output

A structured `.csv` file ready for machine learning models such as those built with `scikit-learn`.

## Project Context

Part of a cybersecurity research project on QUIC protocol evasion using various tools, machines including PA-3220 firewalls.

