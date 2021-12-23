# trading-strategies
Repository of different automated stock trading strategies.

Mean reversion trading - based off concept that stocks tend to revert to mean price. This strategy
uses two cointegrated securities, calculates the moving average of their ratio and then graphs the z-score.
When the z-score goes above 2 the security is automatically shorted and when it dips below -2
a long position is taken.
