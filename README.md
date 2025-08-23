# first-stock-project
My first repository/project, a collection of stock market data projects that include beginner-level stock price visualizations, among others.



## Day 1 (8/19/2025): Stock Price Visualization

**GOAL(S):**
- Create a stock price visualization tool that can be used with user-inputted ticker symbols and start/end dates for data analysis. The data will be visualized through data tables and graphs.

**COMPLETED TASK(S):**
- Created a proper input system for the ticker symbol
- Created a proper input system for the start/end date
- Coded a solution for errors in start/end date format
- Print two data tables for the first 10 days and last 10 days, which include columns for stock analysis
- Graph the closing price with an automatically adjusted scale depending on date disparity

**FIXE(S) NEEDED / NEXT GOAL(S):**
- Dates outside the range of the start/end date cause the program to break
- Short date ranges (within 10 days) cause issues with the tables and graph



## Day 2 (8/20/2025): Stock Price Visualization

**GOAL(S):**
- Fix issues in the previous program, while adding new features such as error messages for invalid starting dates (holidays, weekends)

**COMPLETED TASK(S):**
- Import tools to check for holiday/weekend, and prevent starting dates from being a holiday/weekend
- Coded a solution for errors when the starting date and ending date are the same
- Coded a solution for non-alphabetical inputs for the ticker (excluding "." and "")
- Date ranges under 5 days and within 730 days from the current date will have an interval of 1 hour
- Row numbers in the table change depending on the date range
- Error message for empty data returns

**FIX(ES) NEEDED / NEXT GOAL(S):**
- Create comparison options and multivariable graphs
- End date holiday/weekend checks may be optimal for this program
- Date and time are creating issues within the graphs
- Data for date ranges less than 5 days and more than 730 days old from the current date is very lackluster



## Day 3 (8/23/2025): Stock Price Visualization

**GOAL(S):**
- Implement end date checks and create a more organized method of scaling. Add comparison/multivariable options if time allows.

**COMPLETED TASK(S):**
- Programmed several checks to ensure date inputs are always valid (ex. starting date cannot be after ending date)
- Improved interval/scaling system for more accurate graphs based on the date range
- Implemented ending date checks for weekends and/or holidays
- Program now prints separate graphs for each value (Closing price, high, low, opening price, and trading volume)
- Programmed comparison graphs for up to three tickers
- Overall table and graph formatting updated
- Code was revamped for an easier-to-read, more efficient program

**FIX(ES) NEEDED / NEXT GOAL(S):**
- Start on a new project
