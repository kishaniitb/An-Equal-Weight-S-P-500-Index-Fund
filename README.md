# An-Equal-Weight-S-P-500-Index-Fund

## Description
 **What Is the S&P 500 Index?**

The S&P 500 Index, or Standard & Poor's 500 Index, is a market-capitalization-weighted index of 500 leading publicly traded companies in the U.S. It is not an exact list of the top 500 U.S. companies by market cap because there are other criteria that the index includes. Still, the S&P 500 index is regarded as one of the best gauges of prominent American equities' performance, and by extension, that of the stock market overall.

The S&P 500® Equal Weight Index (EWI) is the equal-weight version of the widely-used S&P 500. The index includes the same constituents as the capitalization weighted S&P 500, but each company in the S&P 500 EWI is allocated a fixed weight 

## Project

    Theory & Concepts: As mentioned above about the Equal Weight Index.
    Importing our Constituents: Imported the stocks.csv file( which constitute all the 505 stocks of S&P 500)
    Pulling Data For Our Constituents: Used IEX Cloud Sandbox API to pull out random data of company market captilization and random stock price.
    Calculating Weights : Calculated weight of each company stock by using Batch API calls because Batch API calls are fast and its improve performance.
    Generating Our Output File: Generated the output xlsx file using the xlswriter library.
    Final Output: Store the output (**Number of shares of each company a person would buy to get the equal weight according to his/her portfolio **) is         stored in Number_of_shares column of recommended_trades.xlsx file.
### For info look at the files mentioned above.
