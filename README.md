
# Sharpe Ratio for Making Big Finance

This is a Finance based Project where you are going to learn and apply the Sharpe Ratio.

How we are going to utilize this Sharpe Ratio for Making Big Financial Decisions.

Understand why to calculate Daily Stock Returns: -

The Sharpe Ratio uses the difference in returns between the two investment opportunities under consideration.

Data show the historical value of each investment, not the return.

To calculate the return, you need to calculate the percentage change in value from one day to the next.

Also, look at the summary statistics because these will become our inputs as we calculate the Sharpe Ratio.

Use the pct_change function to calculate the daily stock returns. After that use the same line plot function to plot the Daily stock return values for both Facebook and Amazon.

 
## Installation

Install Python Version 3.6.8 and then also Install Jupyter Notebook.

Python Libraries: -

- Numpy
- Pandas
- Seaborn
- Matplotlib

Setting the Figure Size and Background: -

Figure Values are entered according to the X-axis and Y-axis.
Fivethirtyeight Background for our Plots.

To select any other Background for your Charts then you can just type the command: “plt.style.available” and pick up any of the Styles for your Charts.

    
## Documentation

- First datasets consists of Stock Values for Amazon and Facebook for the Year 2016.
- Second Dataset consists of the Benchmark Value that is the S&P Global Data.
- A parameter “parse_dates” is set as TRUE, also specified the Date column as the Index Column for Both the Datasets.
- Check the First and Last Record of both the Datasets using the Head and Tail functions.
- Starting Date is 4th January 2016 and the Ending Date is 30th December 2016.
- Summarize Both the Datasets using the Describe function.
- The Stock Values for Amazon are Much Better in comparison to Facebook.
- But focus on the Sharpe Ratio which will help you to find out the Better Investment Options.

The Standard & Poor's 500 Index is the most commonly used benchmark for determining the state of the overall economy. 

Many investors also use The Standard & Poor's 500 Index is the most commonly used benchmark for determining the state of the overall economy. Many investors also use the S&P 500 as a benchmark for their individual portfolios.

The Dow Jones Industrial Average used to be the main gauge of economic health for the United States, but that index only contains 30 companies and is limited in the sectors it represents.

- S&P 500 has become the leading stock index due to its broader scope. Many hedge funds compare their annual performance to the S&P 500 – seeking to realize alpha in excess of the index's returns.

- Composed of 500 large-cap companies across a breadth of industry sectors, the index captures the pulse of the American corporate economy.

- Limited to just large-caps, however, the index misses the much larger swath of mid- and small-cap stocks that make up most of the economy.

- As a market-cap weighted index, this benchmark also gives disproportionate weight to the largest companies, which thus make up the bulk of the index.

Central advantage of using the S&P 500 as a benchmark is the wide market breadth of the large-cap companies included in the index.Index can provide a broad view of the economic health of the United States.

In addition to its broad scope, another advantage of the S&P 500 is that components of the index are updated on a quarterly basis.
Committee determines which companies to include in the index.

Factors considered include a market capitalization in excess of $6.1 billion, a public float of at least 50 percent, headquarters in the U.S., adequate liquidity and financial viability.

Visualizing our Datasets: -
For that, use the plot function and specify subplots equal to True, so that you can obtain a Separate Line plot for each Amazon and Facebook.
For S&P 500, again you will use the plot function to obtain a Line plot.

Choose a Line plot to visualize these Stock Values, because Line plots can be the Best Choice for Visualizing a Huge Number of Values and analyzing the Patterns it.

- In the first plot you have the stock values of Amazon and Facebook.
- In the second plot you have the stock values for the s&p 500.
- Growth and Fall Trends for Amazon and Facebook are very similar.
- The Scale is Quite High for Amazon as compared to Facebook.
- In the second plot you have the stock data for the s&p 500, which again has a very similar pattern to Amazon and Facebook.

Values are not very different, they are quite similar.
Repeat the same steps for the s&p 500 benchmark Data also and store the Daily returns for the s&p 500 in a variable called sp_returns.

## Contributing

The Standard & Poor's 500 Index is the most commonly used benchmark for determining the state of the overall economy. 
Many investors also use the S&P 500 as a benchmark for their portfolios.

The Dow Jones Industrial Average used to be the main gauge of economic health for the United States, but that index only contains 30 companies and is limited in the sectors it represents.

S&P 500 has become the leading stock index due to its broader scope. Many hedge funds compare their annual performance to the S&P 500 – seeking to realize alpha above the index's returns.

Composed of 500 large-cap companies across a breadth of industry sectors, the index captures the pulse of the American corporate economy.

Limited to just large-caps, however, the index misses the much larger swath of mid-and small-cap stocks that make up most of the economy.

As a market-cap-weighted index, this benchmark also gives disproportionate weight to the largest companies, which thus make up the bulk of the index.

The central advantage of using the S&P 500 as a benchmark is the wide market breadth of the large-cap companies included in the index. The index can provide a broad view of the economic health of the United States.

In addition to its broad scope, another advantage of the S&P 500 is that components of the index are updated every quarter.

Committee determines which companies to include in the index.
Factors considered include a market capitalization of over $6.1 billion, a public float of at least 50 percent, headquarters in the U.S., adequate liquidity, and financial viability.

The Sharpe ratio was developed by Nobel laureate William F. Sharpe and is used to help investors understand the return of an investment compared to its risk.

The Sharpe ratio is the average return earned in excess of the risk-free rate per unit of volatility or total risk.

Volatility is a measure of the price fluctuations of an asset or portfolio.

Subtracting the risk-free rate from the mean return allows an investor to better isolate the profits associated with risk-taking activities.

The risk-free rate of return is the return on an investment with zero risk, meaning it's the return investors could expect for taking no risk.

The yield for a U.S. Treasury bond, for example, could be used as the risk-free rate.

Greater the value of the Sharpe ratio, the more attractive the risk-adjusted return.

The Sharpe ratio adjusts a portfolio’s past performance or expected future performance for the excess risk that was taken by the investor.

A high Sharpe ratio is good when compared to similar portfolios or funds with lower returns. The Sharpe ratio has several weaknesses, including an assumption that investment returns are normally distributed.

The Sharpe ratio has become the most widely used method for calculating the risk-adjusted return.

Modern Portfolio Theory states that adding assets to a diversified portfolio that has low correlations can decrease portfolio risk without sacrificing return.

The difference in returns between stock_returns and sp_returns for each day.
Use the "sub function" among the two variables stock_returns and sp_returns where we stored our Daily Returns and after that store this value in a Variable called “excess_returns”.

After Calculating the Excess Returns, plot the Values using the plot function and check the summary using the describe function.
You can see that the Line plots for both Facebook and Amazon are quite Overlapping with Each Other.
## Conclusion


To Invest either in Amazon or in Facebook.

Which of these Companies would be a Better Choice for Investing Money.

To solve this Problem, you will be using the Sharpe Ratio Concept.
And Finally, print the summary using the describe function.
 The difference in returns between stock_returns and sp_returns for each day.
Use the "sub function" among the two variables stock_returns and sp_returns where we stored our Daily Returns and after that store this value in a Variable called “excess_returns”.
After Calculating the Excess Returns, plot the Values using the plot function and check the summary using the describe function.
You can see that the Line plots for both Facebook and Amazon are quite Overlapping with Each Other.

In 2016, Amazon had a Sharpe ratio twice as high as Facebook. This means that an investment in Amazon returned twice as much compared to the S&P 500 for each unit of risk an investor would have assumed.
the investment in Amazon would have been more attractive.

Difference was mostly driven by differences in return rather than risk between Amazon and Facebook.

The risk of choosing Amazon over FB (as measured by the standard deviation) was only slightly higher so that the higher Sharpe ratio for Amazon ends up higher mainly due to the higher average daily returns for Amazon.

When faced with investment alternatives that offer both different returns and risks, the Sharpe Ratio helps to make a decision by adjusting the returns by the differences in risk and allows an investor to compare investment opportunities on equal terms, that is, on an 'apples-to-apples' basis.

That means Client should Invest in Amazon Instead of Facebook.

