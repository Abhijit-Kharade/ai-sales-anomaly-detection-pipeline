# AI-Enabled Sales Anomaly Detection Pipeline

This project demonstrates an end-to-end data engineering pipeline using Apache Spark and machine learning to detect anomalous sales transactions.

## Project Highlights
- Implemented a scalable Spark-based data pipeline using Bronze–Silver–Gold architecture
- Performed feature engineering for transaction-level analytics
- Integrated unsupervised ML (Isolation Forest) for anomaly detection
- Designed pipeline to simulate real-world AI-enabled data engineering use cases


## Architecture
Bronze → Silver → Gold

- Bronze: Raw sales data ingestion
- Silver: Data cleaning and feature engineering using Spark
- Gold: ML-based anomaly detection using Isolation Forest

## Tech Stack
- Apache Spark (PySpark)
- Pandas
- scikit-learn
- Python

## Workflow
1. Load raw sales CSV into Spark
2. Perform data cleaning and transformations
3. Engineer features like total transaction amount
4. Convert Spark DataFrame to Pandas for ML processing
5. Apply Isolation Forest for anomaly detection
6. Generate final dataset with anomaly flags

## Anomaly Detection
Isolation Forest is used as an unsupervised ML algorithm to identify unusual sales transactions based on quantity and total amount.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
