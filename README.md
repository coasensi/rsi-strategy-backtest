 This Python program is designed to backtest a technical analysis based algorithmic trading strategy.

 **The strategy**
 

The RSI (Relative Strength Index) trading strategy is a momentum oscillator used in technical analysis to measure the speed and change of price movements. 

RSI values range from 0 to 100 and are typically calculated using a 14-day moving average of gains and losses.

This strategy leverages two key thresholds: a lower threshold (commonly set at 30) and an upper threshold (commonly set at 70).

**BUY signal**: the RSI value crosses above the lower threshold. The asset is potentially oversold and may experience an upward price reversal.

**SELL signal**: the RSI value crosses below the upper threshold. The asset is potentially overbought and may undergo a downward price correction.

This strategy aims to capitalize on price momentum and identify potential reversal points. Positions are adjusted accordingly, buying when the RSI indicates oversold conditions and selling when it indicates overbought conditions. By holding positions until the RSI generates a contrary signal, this strategy seeks to exploit short-term price fluctuations and capture gains from anticipated price movements. It is particularly effective in ranging markets, where prices oscillate between support and resistance levels, providing clear buy and sell opportunities based on momentum shifts.

The initial report was elaborated using The Boeing Company as an example. However, you will find pdf reports for multiple companies and indexes.
You are able to execute the program with any ticker on yfinance api to generate a RSI strategy backtest report. Have fun !

PS: Cumulative returns are expressed on a logarithmic scale.
