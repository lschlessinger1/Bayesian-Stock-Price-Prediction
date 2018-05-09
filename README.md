# Bayesian-Stock-Price-Prediction
An evaluation of stock price prediction algorithms using analyst ratings

The problem of whether a stock will outperform the US stock market (as measured by S&P 500 Index, or another major index) is an important problem in quantitative finance pertaining to modern portfolio theory (i.e. trying to build a high-return low-risk portfolio) that many people have been working on for years with mixed results. 

The unique approach that is taken here is to incorporate analyst ratings into a prior. 

Research professionals at trading brokerages provide ratings on companies to help investors choose stocks. The vocabulary varies between companies, but almost all use a 1-5 scale, where a 5 indicates a “strong buy”, 1 indicates “strong sell” and 3 indicates hold. Access to aggregate analyst rating is provided as a service from the trading brokerage Morningstar. This data lists a company and how many analysts provide each rating now and across the past 3 months. For example, Amazon (NASDAQ: AMZN) currently has 13 strong buy (5) ratings, and 1 hold (3) rating, for an average rating of 4.86, and had the same rating 3 months ago. 
