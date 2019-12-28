# The-Thomson-Reuters-NewsScope-Event-Indices
Notes and Implementation of - Managing real-time risks and returns: The Thomson Reuters NewsScope Event Indices

## Purpose
> Manage event risk, which is posed by unanticipated news that causes major market moves over short time interval.

## The Framework for Real-time News Analytics
> The core of the real-time news analysis engine relied on a scoring method that assesses the relative volume/significance of news from a specific category of news. For instance, we wish to identify period when the volume of news about foreign exchange markets is abnormally high, or when there is a flurry of macroeconomic news announcements.

> For a given topic, say foreign exchange news, the scoring procedure has the following parameters:
- A list of keywords/phrases and real-valued weights:<img src="https://render.githubusercontent.com/render/math?math=(W_1, \gamma_1),...,(W_k, \gamma_k)">
- A rolling window size, l
- A calibration rolling window size,L

> The score at a given point in time, t, is assigned as follows:\
> Let w be the vector of keyword frequencies in time interval [t-l, t]. The score at time t is then defined to be\
> <img src="https://render.githubusercontent.com/render/math?math=s_t = \sum_i \gamma_i w_i">



