# Anomaly detection on time series data

This repo contains some experiments I did for anomaly detection on time series data.

I used data from the [Numenta Anomaly Benchmark](https://github.com/numenta/NAB), which includes real data obtained from AWS servers. I mainly focus on analysing data of CPU usage in an AWS cluster.

## Methods
I explored different methods for anomaly detection.
- Median Absolute Difference
- Z-score
- Isolation Forest
- Local Outlier Factor
- SARIMA models

I also explore seasonal-trend decomposition, the autocorrelation and partial-autocorrelation functions.

The work is mainly exploratory and I used it to learn more about time series analysis and anomaly detection. The notebook `timeseries.ipynb` contains most of the code. The original data can be obtained [here](https://github.com/numenta/NAB/tree/master/data).
