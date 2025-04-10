# sp500-bigdata-spark-mongodb
SP analysis


# Big Data Analysis of S&P 500 Using Spark and MongoDB

## Overview
This project analyzes historical stock data of S&P 500 companies using Apache Spark and MongoDB. It covers annual performance, volatility ranking, and behavior during financial crises.

## Tools Used
- Apache Spark (PySpark)
- MongoDB Atlas
- Python (Pandas, Matplotlib)
- Google Colab

## Features
- Load S&P 500 data into MongoDB
- Process data using Spark (annual returns, std dev)
- Analyze 2008 & 2020 crises
- Export results to CSV
- Visualize with matplotlib

## How to Run
1. Open `Sp.ipynb` in Google Colab
2. Upload `S&P500.csv` if needed
3. Follow cells from top to bottom

> Note: If MongoDB Spark Connector doesn't work in Colab, use the `PyMongo + Spark DataFrame` method (already handled in this notebook).

## Authors
- Zhenliang Hao 
- Peng Ren 
