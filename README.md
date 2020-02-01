# ExchangeRateForecast
Forecast of US-SGD exchange rate with SIBOR, Daily Fed Fund Rate and historical rates

### Project Description

A Long Short-Term Memory network was used to predict the daily exchange rate figures for US-SGD. The relevant datasets can be
found in the repo. Overall, a high accuracy of 99.9% was achieved if Mean Absolute Percentage Error was used. Although the value
is high, this might be slightly decieving as the exchange rate band have largely remained the same (1.3 to 1.4) for a good
period of time. Thus, even random guessing in the 1.3 to 1.4 band would have generated a high "accuracy" rate. 

Daily Federal Fund rate refers to the lending interest rates between US banks. This is an important metric as other forms of interest rates are mainly influenced by this value. SIBOR, or Singapore Inter-Bank Offered rate, is the equivalent of the Fed
Fund rate for Singapore. As interest rates have a close relationship with exchange rates, I figured that combining the three might be very useful. 

### Acknowledgements 

A-Z Deep Learning (https://www.udemy.com/course/deeplearning/learn/lecture/6771188?start=15#overview)
