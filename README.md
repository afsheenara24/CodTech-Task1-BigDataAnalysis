# CodTech Internship - Task 1: Big Data Analysis using PySpark

This repository contains the first task completed for the CodTech Data Analysis Internship.

## 📌 Objective
To demonstrate scalable data processing by analyzing a large dataset using **PySpark**.

## 📊 Dataset
A synthetic dataset `sample_taxi_data.csv` was generated to simulate NYC yellow taxi trips.

### Sample Features:
- `trip_id` — Unique identifier for each trip
- `pickup_datetime`, `dropoff_datetime` — Trip times
- `passenger_count` — Number of passengers
- `trip_distance` — Distance traveled (km)
- `fare_amount` — Fare charged (₹)
- `payment_type` — Type of payment (Cash, Card, etc.)

## 🧠 Key Analysis Performed
- Count of trips by **passenger count** and **payment type**
- Summary statistics for **trip distance** and **fare amount**
- Trip volume analysis by **hour of day**

## 📁 Files Included
- `sample_taxi_data.csv` – Generated dataset
- `big_data_analysis.ipynb` – PySpark notebook used for analysis

## 🚀 How to Run
1. Make sure you have PySpark installed:
   ```bash
   pip install pyspark
