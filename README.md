# Neel-s-Algo
Neel's Algo is a leading indicator for buying and selling stocks with TradingView Pine scripts as platform


 ███╗░░██╗███████╗███████╗██╗░░░░░██╗░██████╗   ░█████╗░██╗░░░░░░██████╗░░█████╗░
 ████╗░██║██╔════╝██╔════╝██║░░░░░╚█║██╔════╝   ██╔══██╗██║░░░░░██╔════╝░██╔══██╗
 ██╔██╗██║█████╗░░█████╗░░██║░░░░░░╚╝╚█████╗░   ███████║██║░░░░░██║░░██╗░██║░░██║
 ██║╚████║██╔══╝░░██╔══╝░░██║░░░░░░░░░╚═══██╗   ██╔══██║██║░░░░░██║░░╚██╗██║░░██║
 ██║░╚███║███████╗███████╗███████╗░░░██████╔╝   ██║░░██║███████╗╚██████╔╝╚█████╔╝
 ╚═╝░░╚══╝╚══════╝╚══════╝╚══════╝░░░╚═════╝░   ╚═╝░░╚═╝╚══════╝░╚═════╝░░╚════╝░

![image](https://user-images.githubusercontent.com/65644206/221404186-0ffe259c-db79-4890-bc8b-54b1546cfd99.png)

Strategy Buy Sell
The Buy Sell strategy is constructed with several indicators on several time units:

The trend indicator used is Supertrend. It is an indicator based on the volatility of the asset. It must be set on the two time units above the desired signal charts. For example, for 1-minute trading, the indicator should be set to 5 and 30 minutes.

Then there are two types of signals more or less aggressive. The first type of signal (the least aggressive) is based on the Stochastic indicator, which is a momentum indicator and the second type (the most aggressive) of signal is based on the Heikin Ashi candles.
