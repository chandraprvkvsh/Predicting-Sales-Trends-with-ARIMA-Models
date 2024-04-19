# Brief Introduction

Objective of this project was to build different time-series models for each article ID. 
The project involved historical sales record (on a daily basis) from different countries, Performing data stationarity check and making it stationary if it's not, Building different time-series models for different article IDs, Backtesting for each time-series on the last 10 values and then calculating mean absolute error country wise for the last 10 dates.
ARMA model with other user defined functions were used.

# Details about the project

Problem Statement: 

You are provided with a “Historical_Data.csv”  from a company named ABC which sells products online. 
Historical data contains sales record (on daily basis ) from different countries 

Use Historical_Data.csv to build different time-series models for each Article ID.

PATH OF FILES:

Historical_Data.csv: https://media-doselect.s3.amazonaws.com/generic/YKMpgL4avRjQgoPKXoKBgBvy7/Historical_Data.csv

For the above scenario,
Perform backtesting for each time-series on the last 10 values and report the Mean Absolute Error country-wise for each of the last 10 dates (up to 3 decimal places). 

Output Format:
•	Perform the above operations and write your output to a file named output.csv, which should be present at the location /code/output/output.csv
•	output.csv should contain the answer to each question on consecutive rows.

Note: Forecasting model might take some time to generate the output on the test dataset, request your patience in this interim. 


