Databento_Order Books JSON.ipynb retrieves historical order books across the top ten price levels for specified outright and spread/butterfly contracts at a target snapshot time. Books are then stored in .json format. 

Databento_Settlement Prices.ipynb retrieves contract historical daily final settlement prices across a specified date range. A continuous contract series can also be used. File is exported in .xlsx format; final_settlement_prices_complete.xlsx files were then manually constructed to mirror the roll scheme of the curve for one year of data. Futures data has been repeated as IMM swap rates for example purposes only.

These prices have then been back adjusted using a Panama method in Back Adj Panama.ipynb for use in covariance matrix calculations. 

More information on use of the Databento API is available in their documentation: https://databento.com/docs/ 
