A VBA script called Analyze_Stock_Data was created that will:

- loop through all the stocks for one year at a time and outputs the following information for each 
  year:
  * The ticker symbol
  * Yearly change from the opening price at the beginning of a given year to the closing price at the end of that year.
    If the change was negative the cell will be colored red.  If the change was positive the cell will be colored in green.
    If there was no change the cell will not be colored.
  * The percentage change from the opening price at the beginning of a given year to the closing price at the end ofthat year.
    The data will be formatted as "0.00%"
  * The total stock volume of the stock
- the information gathered will be stored in newly created columns on each sheet:
  Ticker
  Yearly Change
  Percent Change
  Total Stock Volume

- In addition the script will:
  * return the stock with the "Greatest % increase", "Greatest % decrease", and"Greatest total volume".
  * this information will be displayed on the sheet containing data from that year in newly added columns.

- the script will gather the aforementioned information for each year (separate sheet) contained in the Excel file automatically.

In the VBA_Challenge Repository you will find:
  * this ReadMe File
  * a PDF document that shows screenshots of the results for each year of 2018, 2019, and 2020 in a separate sheet.
    This file is called "Screenshots - Multiple_Year Stock Analysis Results.pdf"
  * A notepad document that constains the Analyze_Stock_Data script is named "Analyze_Stock_Data.txt"


  * The full excel spreadsheet that contains the data and the Analyze_Stock_Data script included that has been executed resides in the following file on Google Drive:
    This file is called:  "Solved - Multiple_year_stock_data.xlsm"
  * The full excel spreadsheet that contains the data and the Analyze_Stock_Data script included that has NOT been executed resides in the following file on Google Drive.
    This file is called:  "UnSolved - Multiple_year_stock_data.xlsm"

Google Drive Link:
https://drive.google.com/drive/folders/1-4DajCDAS8wUDWAnG-QO-EIZCXYo9ZtU?usp=sharing
