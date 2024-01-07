# stock_price_predictions
Prediction of stock prices using sequence to vector learning

* In this project, it is aimed to see if the stock prices can be estimated "slightly more accurate"
using non trivial models compared to other adhoc counterparts which will be discussed in the scripts.

* The initial attempts are to estimate open prices of some financial assets with sequence to vector 
models such as LSTM,GRU by only using daily autoregressive information of prices.

* The second step is to incorporate further details of the concerned financial asset such as
close price, highest/lowest value during the day, volatility etc., to make more sophisticated estimates
and compare these estimates with adhoc methods.

* The third step is to melt other finanical data in one large model to see if extra financial 
information helps improving validations since the behaviors of financial assets are expected to be 
affected by  political/economic events and similar assets operating in similar industries are 
expected to show similar behavior. To incorporate this, a dnn model with vector embeddings will be 
formed and the asset specific information will be passed as the vector embeddings.
