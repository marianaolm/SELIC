# Selic

### This program, developed on Jupyter Notebook, calculates a series that contains the total profit using the daily data of the SELIC interest rate available in the Open Data API of the Central Bank. 

## Features:

+ Calculates the total profit given an initial amount of capital in a given period of time on a daily, monthly and yearly frequency;
+ Calculates the most profitable period of n calendar days based on the given period of investment inputed by the user.

## Execution instructions:

1) Run all cells: click on the "Cell" button on Jupyter Notebook.

2) Inputs: insert informations as asked:
    + start date/end date of the application as the format "YYYY-MM-DD".
    + initial amount of capital.
    + integer number of n days.
    
3) The program will deliver the outputs:
    + dataframe (df_daily/df_monthly/df_yearly) containing the columns "Date", "Capital" and "Amount earned" on a daily/monthly/yearly frequency based on the user's inputs.
    + start and end date of the most profitable period of n calendar days.
