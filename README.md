# Stock-Analysis

## Overview of Project
Steve wants help with analyzing different stocks for his parents in order to recommend favorable investments.  Steve would like to be able to pull data from any stock and have the data analyzed in the future. Steve would like the most efficient program to analyze the stock data quickly.

## Results
The original data was able to factor the code for the stocks on the spreadsheet created, however, was insufficient to immediately factor codes for thousands of stocks to be analyzed.  The original code was able to factor codes in less than 1 complete second for both years 2017 and 2018.  2017 ran in .57 seconds and 2018 ran in .58 seconds.

When refactoring the data to run any stock that is added to the spreedsheet, the code was able to run in 4.78 seconds for 2017 and 4.74 seconds for 2018.  The refactored stock did not run as expected, as the data point for the array "tickerVolumes(tickerIndex)" had no reference.  The overall outcome of the code was not successful and likely can be refactored to run the correct data over a shorter perior of time.

## Summary

The benefits of refactoring code is that you can apply the code to any set of data with the same structure as the code and analyze new sets of data.

The challenges of refactoring code is that you have to ensure the syntax syncs with the data in the set.  For example, setting the value of one variable at a certain index could give the incorrect value if the variable changes or the order of the array list in a variable set changes.  
