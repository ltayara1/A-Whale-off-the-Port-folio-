# A Whale off the Port-folio

This project explores the risk of investments in algorithmic trading strategies. There are multiple ways to determine 

## Risk

In order to determine the risk of each portfolio, I created a box plot, calculated the standard deviation for all, determined which portfolios were riskier than the S&P 500 and calculated the Annualized Standard Deviation. Berkshire Hathaway Inc. and Tiger Global Management LLC showed greater volatility some days.


## Rolling Statistics

Next, I analyzed the rolling statistics for risk and beta to show the changes in risk over time. 

I plotted the rolling standard deviation of the various portfolios along with the rolling standard deviation of the S&P 500 (consider a 21 day window). Risk does not increase for all of the portfolios at the same time risk increases in the S&P. Berkshire and Tiger do not follow along sometimes.

I constructed a correlation table for the algorithmic, whale, and S&P 500 returns to show that Algo2 and Soros most closely mimic the S&P.

I chose the Algo 2 portfolio and plotted a rolling beta between the portfolio's returns and S&P 500 returns.I showed that it does seem sensitive to movements in S&P (Cumulative Returns).

I also calculated the exponentially weighted moving (ewm) average  with a 21 day half-life, an alternative way to calculate a rolling window. This is like a moving window average, but it assigns greater importance to more recent observations. 


## Sharpe Ratios
Next, I looked at the ratio of return-to-risk. Using the daily returns, I calculated and visualized the Sharpe ratios using a bar plot. I determined that Algo 1 outperforms both the market (S&P 500) and the whales portfolios, but Algo 2 does not.


## Portfolio Returns

In this section, I built my own portfolio of stocks, calculated the returns, and compared the results to the Whale Portfolios and the S&P 500. According to the daily standard deviation, my custom portfolio is one of the top three most volatile with Tiger and Berkshire Hathaway. My custom portfolio is not the most competitive but still has a good return for the risk.