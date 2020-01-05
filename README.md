# The-Thomson-Reuters-NewsScope-Event-Indices
Notes and Implementation of - Managing real-time risks and returns: The Thomson Reuters NewsScope Event Indices

## Purpose
> Manage event risk, which is posed by unanticipated news that causes major market moves over short time interval.

## The Framework for Real-time News Analytics
> The core of the real-time news analysis engine relied on a scoring method that assesses the relative volume/significance of news from a specific category of news.

> In this notebook, I analyze log returns of several ETFs when there is a shift of sentimet measured by zscore over 60 day rolling dat.

## Files
1. `tones.csv` contains sentiment data of of several indices that are analyzed through few thousands news articles since 2017. Each score of "tone" is measured by average sentiment of artiles where related keyworkds appeared in. 
2. `etf_data.csv` contains stock data downloaded from Yahoo Finance.
3. `Event_Analysis.ipynb` is the notebook that attempts to analyze the shifts of distribution of log returns as a results of shift of zscore of the sentiment.



