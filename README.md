STOCK RETURNS PREDICTOR

PROJECT DESCRIPTION!!

In today's dynamic financial landscape, accurately
predicting stock returns has become a challenging yet
crucial task for investors and financial analysts. This
project aims to harness the power of machine learning to
forecast stock returns over a multi-day horizon using a
novel approach that incorporates a diverse set of temporal
data.
The project's primary objective is to develop a
predictive model that can anticipate the returns of a
given stock over a 5-day window. The predictive process
leverages a unique dataset structure: the model is
provided with historical stock returns for the first day
of the trading week, followed by the return of the
subsequent day. On the third day ("D day"), the dataset
includes minute-wise stock returns for the initial 120
minutes of trading. Based on this information, the model
is expected to forecast the stock's return for the next
60 minutes and the returns for the subsequent two trading
days

DATASET DESCRIPTION

We provide 5-day windows of time, days D-2, D-1, D, D+1, and
D+2. You are given returns in days D-2, D-1, and part of day
D, and you are asked to predict the returns in the rest of day
D, and in days D+1 and D+2.
During day D, there is intraday return data, which are the
returns at different points in the day. We provide 180 minutes
of data, from t=1 to t=180. In the training set you are given
the full 180 minutes, in the test set just the first 120
minutes are provided.For each 5-day window, we also provide 25 features, Feature_1
to Feature_25. These may or may not be useful in your
prediction.
Each row in the dataset is an arbitrary stock at an arbitrary
5-day time window.
How these returns are calculated is defined by Winton, and
will not to be revealed to you in this competition. The data
set is designed to be representative of real data and so
should bring about several challenges.



