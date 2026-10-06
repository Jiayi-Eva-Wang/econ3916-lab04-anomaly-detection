# econ3916-lab04-anomaly-detection

# Robust Statistics -- Automated Anomaly Detection

## Objective

In this lab, I compared different statistical methods for identifying unusual observations in the California Housing dataset.

## Methodology

- I calculated the mean, median, trimmed mean, standard deviation, IQR, and MAD for 20,640 observations.
- I manually used Tukey Fences to identify price outliers.
- I used Isolation Forest to detect unusual observations based on multiple features.
- I compared the observations flagged by Tukey Fences and Isolation Forest.
- I tested how the statistical measures changed after 5% of the data was intentionally contaminated.

## Key Findings

Tukey Fences and Isolation Forest identified different observations because they use different information to detect unusual values. In the contamination experiment, the mean shifted by 67.1%, while the median shifted by only 3.6%. This showed that the median was much less affected by the extreme values.
