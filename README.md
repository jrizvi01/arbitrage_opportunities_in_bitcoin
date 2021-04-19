# arbitrage_opportunities_in_bitcoin
Arbitrage Opportunities in Bitcoin and Other Cryptocurrencies

This program has 3 different modules:

1. Collect the data.
  - Imports the data from csv files and creates a DataFrame(s)

2. Prepare the data.
  - Cleanse data for analysis:
    * by replacing or dropping all NaN values
    * removing the dollar signs ($) from the values in the 'Close' column
    * converts the data type of the 'Close' column to a float

3. Analyze the data.
   - Analysis provides the following:
     * provides summary statistics and plot the data.
     * analysis is done on specific dates.
     * calculates the arbitrage profits.