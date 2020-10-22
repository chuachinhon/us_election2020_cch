#  Forecasting The 2020 US Presidential Election With (FB) Prophet And XGB [PART 2]

![](https://cdn-images-1.medium.com/max/1600/1*cXhAWPTzsdbmqJdeG7LRbg.jpeg)

With about two weeks to go before the 2020 US Presidential Election, the statistics on multiple fronts are looking rather grim for White House incumbent Donald Trump.

This new series of notebooks/datasets take a closer look at the latest electoral projections, as well as Trump and his challenger Joe Biden’s performance on Twitter in the past month.

[New datasets with forecasts up to Oct 19](https://github.com/chuachinhon/us_election2020_cch/tree/main/data):
- 538_19102020.csv 
- economist_19102020.csv 
- economist_chances_19102020.csv 
- trump_19102020.csv
- biden_19102020.csv

[New notebooks with forecasts up to Oct 19](https://github.com/chuachinhon/us_election2020_cch/tree/main/notebooks):
- [1.1_data_extract_19102020.ipynb](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/1.1_data_extract_19102020.ipynb): data extraction 
- [2.1_prophet_ev_19102020.ipynb](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/2.1_prophet_ev_19102020.ipynb): Biden-Trump EV count forecast using Prophet
- [2.2_prophet_chance_of_winning_19102020.ipynb](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/2.2_prophet_chance_of_winning_19102020.ipynb): Biden-Trump forecasted chance of winning EC using Prophet
- [3.2a_xgb_trump_ev_19102020.ipynb](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/3.2a_xgb_trump_ev_19102020.ipynb): Trump's EV count forecast using XGB
- [3.2b_xgb_trump_chances_19102020.ipynb](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/3.2b_xgb_trump_chances_19102020.ipynb): Trump's forecasted chance of winning EC using XGB
- [3.3a_xgb_biden_ev_19102020.ipynb](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/3.3a_xgb_biden_ev_19102020.ipynb): Biden's EV count forecast using XGB
- [3.3b_xgb_biden_chances_19102020.ipynb](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/3.3b_xgb_biden_chances_19102020.ipynb): Biden's forecasted chance of winning EC using XGB


## [Medium post: For Trump, no comfort in forecasts or Twitter in final stretch of 2020 US Presidential Election](https://chuachinhon.medium.com/for-trump-no-comfort-in-forecasts-or-twitter-in-final-stretch-of-2020-us-presidential-election-186e655e9bf5)


#  Forecasting The 2020 US Presidential Election With (FB) Prophet And XGB [PART 1]

![](https://miro.medium.com/max/2000/1*v-YmvO_fQ_vvHeUWwA3efA.png)

With about a month to go before the 2020 United States Presidential Election on November 3, all eyes are on the barrage of polls and forecasts for the highly volatile race for the White House. The repo outlines a way to leverage forecasts by reputable outlets tracking the election for further time series analysis using (FB) Prophet. 

### [notebook1.0](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/1.0_data_extract_cch.ipynb) : Data extraction and processing

### [notebook2.0](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/2.0_prophet_cch.ipynb) : Time series analysis with Prophet


### [notebook3.0](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/3.0_xgb_trump.ipynb) & [notebook3.1](https://github.com/chuachinhon/us_election2020_cch/blob/main/notebooks/3.1_xgb_biden.ipynb): Time series analysis with XGB


### [Medium post #1](https://medium.com/@chinhonchua/forecasting-the-2020-us-presidential-election-with-fb-prophet-36ab84f1a75a)

---
