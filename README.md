# Mid-Frequency-Statistical-Arbitrage

A simplified mid-frequency pairs trading strategy on stocks from the Nifty500, in an effort to demonstrate some of the core ideas of statistical arbitrage strategies.
We identify a pair of stocks (Bajaj Finserv and Indian Bank) that we find to be cointegrated at the one-minute time frequency on the 26th September 2024. We then use
linear regression to estimate the hedge ratio, which we use to compute a stationary spread. Finally, we test the strategy on unseen data from the following day,
and find that profitability persists into the 27th September 2024. We conclude by mentioning a handful of potential improvements to the strategy.
