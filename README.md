# MultivariateTimeSeriesClassificationLSTM
Multivariate Time Series Classification using LSTM 

31 values in Arousal_Valence 

14687 values for GSR - sampling frequency: 4 Hz

348598 values for PPG - sampling frequency: 100 Hz

Arrange data points into sequences of about 473 timesteps
ppg_series

gsr_series

n = sequence length = 473

Sliding window if want overlap between sequences


X_train :

| subject_id | sequence_id | ppg_series | gsr_series |
|------------|-------------|------------|------------|
| 1          | 1           | [...]      | [...]      |
| 1          | 2           | [...]      | [...]      |
| 1          | 3           | [...]      | [...]      |
| 2          | 1           | [...]      | [...]      |
| 2          | 2           | [...]      | [...]      |
| 2          | 3           | [...]      | [...]      |




