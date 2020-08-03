# trading_resistance_support
Trading Stratagems Around Resistance and Support

https://towardsdatascience.com/detection-of-price-support-and-resistance-levels-in-python-baedc44c34c9

Create an algorithm to automatically detect two important tools of price action, which are supports and resistances.

Supports and resistances are often called “key levels”. They are price levels at which the stock price 
has inverted its trend. If the price rises and then inverts its trend moving down, the highest point 
it has reached is called resistance. If the price has gone down and then starts rising, the lowest 
price value is called support.

These price levels identify supply and demand zones, at which traders have increased their operation volume 
and have shown some interest. That’s why, as soon as the price gets closer to a key level, 
traders must keep their eyes open and see what happens.

There’s a rule of thumb that says that the more times a key level has been tested 
(i.e. the market has bounced near it many times), the higher the importance of the level.

Another rule of thumb is that, once a resistance level is broken, it automatically becomes a support level. 
Viceversa, a broken support level becomes a resistance level.

A good idea is to use the candlestick chart and check the high and low prices of every candle. 
If a candle low is lower than the previous and the next candle’s low, that’s a support. 
This particular price action pattern is called swing. Unfortunately, this pattern often 
shows some flaws due do market volatility and noise, that’s why we can use a better pattern called fractal.

Fractals are very useful because they remove some of the noise shown by the swings 
and identify key levels with higher accuracy.
