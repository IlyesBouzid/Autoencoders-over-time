# Autoencoders over time

## Project Description

We have developed autoencoders to detect anomalies over time. There are two variants of the project. In the first one (V1), we trained and tested the autoencoders on a set of time series from different datasets (UD1-UD4). In the second one (V2), we trained and tested the autoencoders on a single time series for each dataset (UD1-UD4).

## Datasets

Four types of datasets are used to train and test the model. These datasets, published by Yahoo, contain traffic data for Yahoo services.

- **UD1**: Most of the time series in this dataset are stationary. It consists of 67 different time series, each containing 1.9% anomalies.
- **UD2**: This dataset consists of 100 synthetic univariate time series where anomalies have been randomly inserted, representing point anomalies. On average, each time series contains 0.3% anomalies.
- **UD3**: Unlike the previous dataset, this one contains seasonality. The anomalies are inserted at random points, marking the change points. On average, 0.3% of the dataset is anomalous.
- **UD4**: This dataset differs from the previous one in that it also contains changepoint anomalies where the mean of the time series changes. For our evaluation, we focus on the main anomalous points and do not distinguish between types of anomalies. On average, 0.5% of the dataset is anomalous. The values of timestamps in UD3 and UD4 are the sum of the noise, trend, and three types of seasonality (half-day, daily, and weekly).

## Citation

Braei, M., & Wagner, S. (2020, April 1). Anomaly Detection in Univariate Time-series: A Survey on the State-of-the-Art. arXiv.org. https://arxiv.org/abs/2004.00433

## Contact

Ilyes Bouzid – www.linkedin.com/in/ilyes-bouzid

## Project Link

https://github.com/IlyesBouzid/Autoencoders-over-time
