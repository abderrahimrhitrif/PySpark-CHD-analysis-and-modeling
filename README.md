# PySpark CHD Analysis & Modeling

## Overview
This project implements distributed data analysis and exploratory workflows for Coronary Heart Disease (CHD) datasets using PySpark.

## Architecture & Pipeline
- **Spark Session**: Initializes a distributed SparkSession (`pyspark.sql`).
- **Data Ingestion**: Reads CSV datasets with inferred schemas and caches DataFrames in memory (`df.cache()`).
- **Exploratory Data Analysis**: Computes distributed descriptive statistics, null value distribution analysis, and data visualization charts.

## Data
- **Dataset**: Coronary Heart Disease records (`train.xls`).

## Method & Algorithms
- **Distributed Data Processing**: PySpark DataFrame operations, null imputation statistics, and aggregation pipelines.

## Verified Results & Metrics
- Successfully loaded and cached distributed datasets in Spark, executed distributed null-value auditing, and generated exploratory data summaries.

## Limitations & Caveats
- Data processing and preprocessing pipeline implemented; advanced MLlib predictive modeling depends on downstream notebook extensions.

## Run Instructions
```bash
jupyter notebook spark.ipynb
```
