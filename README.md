# Big Data Analytics - TP02

## Project Overview
This project explores different approaches for processing large datasets using Pandas and Dask.

## Objectives
- Demonstrate the memory limitations of loading a large CSV file using Pandas.
- Process large datasets using Pandas chunking.
- Use Dask for parallel and lazy data processing.
- Compare execution time and memory usage.

## Dataset
TalkingData AdTracking Fraud Detection dataset from Kaggle.

The original dataset is approximately 7 GB. The dataset is not included in this repository because of its large size.

## Methods
1. Traditional Pandas loading.
2. Pandas chunk processing.
3. Dask parallel processing.

## Results
Pandas chunking processed 184,903,890 rows in approximately 140.73 seconds.

Dask processed the same number of rows in approximately 342.85 seconds using 117 partitions.

Both approaches obtained 456,846 attributed records. Results depend on the execution environment and configuration.

## Tools
- Python
- Pandas
- Dask
- Google Colab
- Jupyter Notebook

## Author
Master 2 - Artificial Intelligence and Data Science
