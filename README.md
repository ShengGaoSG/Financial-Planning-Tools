# Financial-Planning-Tools

This program creates two financial analysis tools:
1.	A financial planner for emergencies. The credit union members are able to use this tool to visualize their current savings. The members can then determine if they have enough emergency fund.
2.	A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations. 

Part 1: Create a Financial Planner for Emergencies
Evaluate the Cryptocurrency Wallet by Using the Requests Library: This section is designed to determine the current value of a member’s stock and bond holdings. 
Evaluate the Emergency Fund: This section uses the valuations for the cryptocurrency wallet and for the stock and bond portions of the portfolio to determine if the credit union member has enough savings to build an emergency fund into their financial plan. 

Part 2: Create a Financial Planner for Retirement
This part uses the Alpaca API to get historical closing prices for a retirement portfolio. The program runs simulations to forecast the portfolio performance 30 years from now. 
Create the Monte Carlo Simulation
This section uses the MCForecastTools Library to create a Monte Carlo simulation for the member’s savings portfolio. This is achieved by:
1.	Make an API call via the Alpaca SDK to get 3 years of historical closing prices for a traditional 60/40 portfolio split: 60% stocks (SPY) and 40% bonds (AGG)
2.	Run a Monte Carlo simulation of 500 samples and 30 years for the 60/40 portfolio, and then plot the results. 
3.	Plot the probability distribution of the Monte Carlo simulation.
4.	Generate the summary statistics for the Monte Carlo simulation.

Analyze the Retirement Portfolio Forecasts: using the current value of only the stock and bond portion of the member’s portfolio and the summary statistics that you generated from the Monte Carlo simulation, calculate the lower and upper bonds for the expected value of the portfolio with a 95% confidence interval. 

Forecast Cumulative Returns in 10 Years: Adjust the retirement portfolio and run a new Monte Carlo simulation to find out if the changes will allow members to retire earlier. 
