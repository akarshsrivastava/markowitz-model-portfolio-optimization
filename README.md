# Markowitz model for portfolio optimization
The Markowitz model is a portfolio optimization model, which was put forward by Harry Markowitz. The Markowitz model helps in the selection of the most efficient portfolio by analyzing various possible portfolios of the given securities. The Markowitz model is also called mean-variance model as it is based on expected returns (mean) and the standard deviation (variance) of the various portfolios. It is foundational to Modern portfolio theory.

## Model portfolio theory

Modern portfolio theory (MPT) is a theory on how risk-averse investors can construct portfolios to maximize expected return based on a given level of market risk.

Higher risk is associated with greater probability of higher return and lower risk with a greater probability of smaller return. MPT assumes that investors are risk-averse, meaning that given two portfolios that offer the same expected return, investors will prefer the less risky one. Thus, an investor will take on increased risk only if compensated by higher expected returns.

Modern portfolio theory says that it is not enough to look at the expected risk and return of one particular stock. By investing in more than one stock, an investor can reap the benefits of diversification. Diversification can help you achieve even lower risk than a stock with the lowest risk in your portfolio, by optimising the allocation. 

## Methodology
### Determining the efficient set:
A portfolio that gives maximum return for a given risk, or minimum risk for given return is an efficient portfolio. Thus, portfolios are selected as follows:

(a) From the portfolios that have the same return, the investor will prefer the portfolio with lower risk.

(b) From the portfolios that have the same risk level, an investor will prefer the portfolio with higher rate of return.

## About the project:
### I have taken two cases:

(I) Optimize portfolio selection with two stocks. URL: https://github.com/akarshsrivastava/markowitz-model-portfolio-optimization/blob/main/Markowitz%20Portfolio%20Theory%20-%202%20stocks.ipynb
(II) Optimize portfolio selection with more than two stocks. URL: 

In both cases the approach is same, the only difference is the number of stocks to select in the portfolio.

### Approach:
1. We consider any 2 stocks. Now we need to find out weights of these two stocks to keep in our portfolio. 
2. Evaluate the portfolio expected return, variance and volatility(standard deviation)
3. We run a for loop to populate an array of size two (i.e. the number of stocks to select) with random weights summing to 1. Further in the loop evaluate portfolio expected return and volatility(standard deviation) to append in two lists for portfolio returns and portfolio volatility. 
4. Plot the data on graph with portfolio returns and portfolio volatility as axes to get the Markowitz Efficient Frontier.
5. From the Efficient Frontier we can reach the optimal weights selection to optimize portfolio.

### In case of more than 2 stocks, follow the same steps with number of stocks you select. Refer the 'Markowitz Portfolio Theory - more than 2 stocks.ipynb' file.
 
