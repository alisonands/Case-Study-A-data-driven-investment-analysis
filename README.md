# Case study: A data-driven investment strategy

## Preliminary analysis
- What makes a stock price appreciate?
  - A stock price is simply an earnings metric multiplied by a multiple metric. The most common ways to value a stock are P/E (price/earnings), EV/EBITDA (enterprise value/EBITDA) and FCF/Market Capitalization (or Free Cash Flow yield)
  - If a stock price is increasing, it is either being driven by higher earnings or multiple expansion. For example, if XYZ stock is trading at $10, and earns $1 per share in EPS, it is trading at 10x earnings.
- For a company to be considered a good investment, solid earnings are essential
  - Look at y-o-y or q-o-q results
- ROE - Return on investment
  - Net Income/Shareholder's Equity
  - Measures the ability of a company's management to turn a profit

#### Questions to be answered:
- How have sectors performed over the years. What has grown, what has become relatively small? Show this in a plotly animation.

### Stock Idea Generation
- An attractive long position: undervalued by the market and under-earning.
  - Under-earning --> the company is not realizing its full potential
    - Given by P/E ratio less than 1
- Resources
  - [WSJ](https://www.wsj.com/)
  - [NYtimes](https://www.nytimes.com/)
  - [FT](https://www.ft.com/)
- Traditional/Base screens:
  - Low P/E value
  - Low P/B calue
  - Low EV/EBITDA
  - High FCF
  - Spin-offs
  - Recent Insider Buying
- Other factors:
  - EV/Sales
  - FCF/Market Cap

*Note: Some metrics are industry specific

1. Graphical comparison of one stock to various other industries stock metrics/ratios. What makes this one stock better than the others?

## Value investing framework
- When the price of a secutiry diverges from its intrinsinc value, a value investor should work to exploit that divergence
- A security should be preferably purchased at a deep discount to its intrinsic value. This reduces risk

 ## Industry Analysis
 - Study market size and growth
  - i.e. marketing vs distribution for an industry can look very different
 - Historical Industry returns
 - Competitive positioning
  - Cylical/Seasonal
    
#
[1-page Hedge fund Case study](https://www.streetofwalls.com/finance-training-courses/hedge-fund-training/hedge-fund-case-study-1-page/)

## A quantative analysis based screener:
- The main drivers: Profitability, Valuation, Cash Flow, Growth, Capital Allocation, Price Momentum
- Run tests over a ~30 year period 1993 - 2023 or max
- These tests will be based on:
  - Operating Cash Flow to Capital Expenditures
  - P/E ratio
 
### Operating Cash Flow to Capital Expenditures
- This strategy looks at the amount of cash available in a company to fund its PP&E expenditures relative to it's cash flow
- Companies generating high cash flows relative to it's expenditures has excess cash that it can allocate to dividends, reducing debt, repurchase of shares, etc. and will likely have less debt
- Companies that do not generate enough cash flow, may not have financial flexibility
- 

- Data gathering: [IEX cloud](https://iexcloud.io/docs/api-basics)
- Data cleaning:
  - Tickers with >5 counts of data
