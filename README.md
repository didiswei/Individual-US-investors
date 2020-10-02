# Individual investors in the U.S. stock market
Data Science project identifying potential individual investors in the U.S. 

## Motivation
With the rise of easy app-based trading, the individual investor is reshaping the U.S. stockmarket. According to the [Wall Street Journal](https://www.wsj.com/articles/individual-investor-boom-reshapes-u-s-stock-market-11598866200?mod=itp_wsj&yptr=yahoo), during the first half of 2020, individual investor shares traded in the U.S. stock market jumped from 14.9% to 19.5%, and in 2019 the total value of stocks traded in the U.S. was about 23 trillion dollars according to the [World Bank](https://data.worldbank.org/indicator/CM.MKT.TRAD.CD?end=2019&locations=US&start=1984&view=chart). This means that a reasonable estimate for the value of trades of individual investor shares in 2020 is about 4.5 trillion dollars. 

It would behoove any financial company to identify the primary demographics of people who are most likely to invest their money, so they can identify likely customers and gain a larger share of this fast-growing segment of the financial market.

## Problem Statment
Given limited demographic information, can we identify people who are likely to invest in the stock market?

## Methodology
Here we use demographic data of financial investors to build both a logistic regression and KNearestNeighbors model to understand and identify investors and non-investors based on demographic information alone. This model is then used to predict the likelihood of investment for a number of test cases. Regression is also used to identify the most important demographic characteristics in identifying potential investors.   

## Languages and libraries
Python (numpy, pandas, sklearn, scipy, statsmodels, matplotlib, seaborn)

## Impact
Given the portion of investors vs. non-investors found in our representative data set, if we try to blindly identify potential investors we have about a 65% possibility of success. Using the model built here, using a few demographic characteristics, we are able to correctly identify someone as an investor or a non-investor with an 83% accuracy rate. Based on the 4.5 trillion dollars of individual U.S. investor trades per year, this translates to a billion dollar opportunity dollar opportunity. 
