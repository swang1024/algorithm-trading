# algorithm-trading

This paper introduces an approach to pairs trading utilizing sparse portfolios, using different methods for feature selection and portfolio construction. Pairs trading, a popular
market-neutral strategy, involves exploiting short-term misalignments between two correlated assets. Pairs trading involving two assets can naturally be extended to a portfolio
of assets, but typically these portfolios are dense. Sparse portfolios enhance this strategy by automatically selecting a subset of the most relevant features, thereby improving in-
terpretability, reducing dimensionality, and potentially enhancing trading performance by creating more meaningful statistical arbitrage opportunities.

In this paper, we will discuss 2 different methods of forming spare portfolios using machine learning and greedy search. We will discuss a new method of testing for cointegration
when there are more than 2 time series, and how this new method gives the appropriate hedge ratios for the assets in our portfolio. We will discuss and compare several methods
of determining trading signals using a stochastic approach, as well as risk management considerations for our trading strategy including using VaR (value at risk) and sentiment
analysis. We will discuss how different parameters for our strategy are tuned, and the efficacy of our strategy in different trading periods.
