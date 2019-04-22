---
layout: post
title:  "Application for the Challenge"
date:   2019-04-22 00:00:00 +0200
categories: jekyll update
---
Today we submitted our proposal for the topic "Machine learning for predicting extreme weather hazards" of ECMWF's Summer of Weather Code (ESoWC) 2019. The plan is to compare various machine learning methods on the subject of flood forecasting using data from Copernicus' ERA5 reanalysis, data from the Global Flood Awareness System (GloFAS)  and ECMWF's severe weather event database. All the code will be open source available through this github account.

We will be posting tutorials for everyone interested in using Copernicus' open data to achieve results quickly without spending too much time on data preprocessing, finding suitable model parameters and searching through APIs.

{% highlight python %}
from this_team import MachineLearning

def my_extreme_weather(event):
    ML = MachineLearning.train(on=event)
  return ML.fast_success()
{% endhighlight %}
