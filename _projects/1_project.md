---
layout: page
title: PredXGBR
description: PredXGBR A Machine Learning based Short term Electrical Load Forecasting Architecture
img: assets/img/project1.png
importance: 1
category: Research
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/PredXGBR_3.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Actual vs Predicted Power Consumption of National Grid Bangladesh
</div>




The growing demand for consumer-end electrical load is driving the need for smarter
management of power sector utilities. In today’s technologically advanced society, efficient energy
usage is critical, leaving no room for waste. To prevent both electricity shortage and wastage,
electrical load forecasting becomes the most convenient way out. However, the conventional and
probabilistic methods are less adaptive to the acute, micro, and unusual changes in the demand trend.
With the recent development of artificial intelligence (AI), machine learning (ML) has become the
most popular choice due to its higher accuracy based on time-, demand-, and trend-based feature
extractions. Thus, we propose an Extreme Gradient Boosting (XGBoost) regression-based model—
PredXGBR-1, which employs short-term lag features to predict hourly load demand. The novelty of
PredXGBR-1 lies in its focus on short-term lag autocorrelations to enhance adaptability to micro-trends
and demand fluctuations. Validation across five datasets, representing electrical load in the eastern
and western USA over a 20-years period, shows that PredXGBR-1 outperforms a long-term feature-
based XGBoost model, PredXGBR-2, and state-of-the-art recurrent neural network (RNN) and long
short-term memory (LSTM) models. Specifically, PredXGBR-1 achieves a mean absolute percentage
error (MAPE) between 0.98 and 1.2% and an R2 value of 0.99, significantly surpassing PredXGBR-2’s
R2 of 0.61 and delivering up to 86.8% improvement in MAPE compared to LSTM models. These
results confirm the superior performance of PredXGBR-1 in accurately forecasting short-term load
demand.

