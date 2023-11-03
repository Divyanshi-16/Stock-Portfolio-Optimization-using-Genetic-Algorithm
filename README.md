# Stock-Portfolio-Optimization-using-Genetic-Algorithm
## Optimizing Stock Portfolio using Genetic Algorithm from Scratch
Portifolio Optimization ( Optimal Asset Allocation / Modern Portfolio Theory ) is a formal mathematical approach in making investment decisions across a collection of financial instruments or assests. To deal with the optimization problem, a quantative model was developed, also called mean-variance model. This model incorporates either the minimization of an objective function representing the portfolio variance ( risk ) for a given level of return or the maximization of an objective function representing the portfolio return for a given level of risk.
### Some terms related to Stock Portfolio Otimization
- Portfolio: The portfolio is a collection of all the investments that an investor has made right from purchasing a share for the first time.
- Liquidity: Liquidity means how stocks can be sold off quickly. Shares that get sold consist of high trade volumes quickly and are called highly liquid.
- Alpha: The amount of return expected from an investment from its inherent value.
- Appreciation: The increase in value of a financial asset.
- Benchmark: A standard, usually an unmanaged index, used for comparative purposes in assessing performance of a portfolio or mutual fund.
- Equities: Shares issued by a company which represent ownership in it.
- Index: An investment index tracks the performance of many investments as a way of measuring the overall performance of a particular investment type or category.
- Inflation: A rise in the prices of goods and services, often equated with loss of purchasing power.
- Maturity: The date specified in a note or bond on which the debt is due and payable.
- Premium: The amount by which a bond or stock sells above its par value.
- Stock: A long-term, growth-oriented investment representing qwnership in a company, also known as 'equity'.
- Sharpe Ratio: A risk-adjustment measure that measures reward per unit of risk. The higher the sharpe ratio, the better. The numerator is the differnce between the Fund's annualized return and the annualized return of the risk-free instrument(T-Bills).
### Problem Statement and Genetic Algorithm Approach
- Portfolio containing some N financial assets(stock, funds, bonds, ETF, etc.). Each one of them has many historical returns, that is the price relative difference from one period to another. The goal of portfolio optimization is to find the values of the weights that maximize returns and minimize risk simultaneously of our portfolio under some constraints.
##### Why using Genetic Algorithm Approach?
Genetic algorithm is an evolutionary algorithm, based on genetics and evolution, is used to deal with computionally complex problems, with large search spaces ( either discrete or continuous ). It works to find out the near optimal solution using stochastic search methods. Principles of GA works on two fundamental biological processes: Geneteics ( producing new solutions ( offsprings ) from the original population of individuals ) and Evolution ( Heredity, Population Diversity, Selection, Ranking ). 
##### Given data: -
Monthly closing stock values of HDFC, ITC, L&T, M&M, Sun Pharma and TCS from June 2015 to June 2018.
##### Genetic Algorithm Approach: -
1) All the data is combined into one dataframe.
2) Historical returns for 3, 6, 12, 24, and 36 months are generated as fractions for each stock.
3) Gene: ( Real Encoding ), a fraction of the total capital assigned to a stock.
4) Chromosome: set of genes ( 1D array )
5) Initial Population: set of randomly generated chromosomes ( 2D array )
6) Fitness Function:
7) 
