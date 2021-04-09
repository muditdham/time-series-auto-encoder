# Anomaly Detection using AutoEncoders on Time Series Data
Using Auto Encoders to detect Anomalies in a time series data
6 different type of time series (3 Real and 3 Synthetic) are selected from the given dataset and different architectures of Auto Encoders applied to detect anomalies

| Filename | Description |
| --- | --- |
| Time Series AE.ipynb | Analysis Notebook |

# Types of Auto Encoders used
- 2 Layer LSTM Auto Encoder with (128-64-64-128) encode-decode architecture
- 2 Layer LSTM Auto Encoder with (64-32-32-64) encode-decode architecture
- 2 Layer CNN Auto Encoder with (16-8-8-16) encode-decode architecture

###  Dataset - [Yahoo! Webscope dataset ydata-labeled-time-series-anomalies-v1_0](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70)

| File Name | Description |
| --- | --- |
| Series 1 | /datasets/ydata-labeled-time-series-anomalies-v1_0/A1Benchmark/real_19.csv |
| Series 2 | /datasets/ydata-labeled-time-series-anomalies-v1_0/A1Benchmark/real_65.csv |
| Series 3 | ./datasets/ydata-labeled-time-series-anomalies-v1_0/A1Benchmark/real_37.csv |
| Series 4 | ./datasets/ydata-labeled-time-series-anomalies-v1_0/A2Benchmark/synthetic_50.csv |
| Series 5 | ./datasets/ydata-labeled-time-series-anomalies-v1_0/A2Benchmark/synthetic_26.csv | 
| Series 6 | ./datasets/ydata-labeled-time-series-anomalies-v1_0/A2Benchmark/synthetic_40.csv |

### Notes
- Results documented as info graphs / plots and saved in ./plots directory
- Functions documented with doc string and necessary comments
- Future changes and experiments and References mentioned after analysis and before Appendix
- Appendix attached at the very end of the ipynb file
- Link of Dataset - https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70

### References 
- [Yahoo! Webscope dataset ydata-labeled-time-series-anomalies-v1_0](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70)
- [Autoencoders for the compression of stock market time series](https://towardsdatascience.com/autoencoders-for-the-compression-of-stock-market-data-28e8c1a2da3e)
- [Time-series forecasting with deep learning & LSTM autoencoders](https://www.kaggle.com/dimitreoliveira/time-series-forecasting-with-lstm-autoencoders)
