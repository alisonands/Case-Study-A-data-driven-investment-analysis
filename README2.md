# Case study: A data-drive investment analysis

## Summary

## Introduction
The purpose of this analysis is to explore variables of the financials of stocks to determine best ratios that result with low volatility and good returns, with the aim of enhancing portfolio development. The structure of this study is heavily infulenced by the methodology used in [Quantative Stratagies for Measuring Alpha](1). Specifically, we will look at Cash Flow factors, namely Operating Cash Flow and Capex. We will use the ratio Operating Cash Flow to Capex, to determine what the optimal ratio is that yields high returns. Note that this is not necessarily a standalone strategy, rather, it's purpose is to determine how the management of cash affects overall returns. The results from this analysis, paired with other relavant stratagies, can contribute to the development of a strong portfolio.

### Common Screeners
In order to narrow down the factors to Operating Cash Flow and Capex, sevaral other variables were taken into account. Some common variables used in screeners today are: P/E, ratio, P/B ratio, FCF, EV/EBITDA, Market Cap, Dividend Yield, ROE, etc. These metrics are well known, and are good indicators of the performance of a stock. This project aimed to test the efficiency of the use of cash in a companies expenditures, in comparison to the free cash flow. 

### Operating cash flow to Capital Expenditures
In the daily operations of a business, a certain level of expenditures is required to replace a companies PP&E expenses, and the operating cash flow looks at how much a company has available to fund this expense. Companies that have a high cash flow relative to their capex are generally more stable, have less debt, and have enough cash on hand to pay off their expenses. On the other hand, companies with little cash flow to capex may not have the financial flexibility to improve upon their performance. 

## Methodology
1. Data Gathering:
- The dataset used is from the [IEX cloud](https://iexcloud.io/docs)(2) API database.
- Stocks are gathered from [NASDAQ](https://www.nasdaq.com/market-activity/stocks/screener)(3) database and filtered to the **tech** industry, since 2013.

2. Ranking Stocks:
- For each year, the the stocks are ranked based on the operating cash flow to capex ratio.

3. Quintile assignment:
- The ranked list is then divided into quintiles, where the first quntile has the highest ratios of Operating Cash Flow to Capex and the fifth quintile has the lowest ratios.

4. Analysis:
- The returns based on the historical data is calculated for each quintile. 
- The % change in closing prices is calculated annually, for each stock. 
- The excess return compared to the universe is also calculated for comparison.

### Data sources

## Results

## Analysis

## Conclusion

## References
[1.] (Quantative Stratagies for measuring Alpha)
[2.] [IEX cloud](https://iexcloud.io/docs)
[3.] [NASDAQ](https://www.nasdaq.com/market-activity/stocks/screener)