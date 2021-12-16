# Week5_HomeWork
Financial Planning Homework for Week5

## Background
> I am starting by FinTech consultancy firm, and want to make a difference by working on projects with high social impact in local communities. For my first contract to help one of the biggest credit unions in my area. They want to create a tool that helps their members enhance their financial health. The Chief Technology Officer (CTO) of the credit union asked me to develop a prototype application to demo in the next credit union assembly.

>The credit union board wants to allow the union's members to assess their monthly personal finances, and also be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.

> I can use all the skills I learned in my FinTech Bootscamp with MonashIn with a focus on using APIs as part of the technical solution - to create two financial analysis tools. The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund. The tool is very simple and premitive, as in its initial and beta stage. 

> The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. We will use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

> resources used :  **Alpaca Markets API** and **Alternative Free Crypto API** 

### Please note that I replaced the currency from CAD to AUD, to be more relevant

### Part-1 Personal Financial Planner

- The Alternative Free Crypto API was used to retrieve Bitcoin and Ethereum prices. After connecting to the API, we computed total value of crypto portofolio.
- The Alpaca Markets API was used to pull historical stocks and bonds information. After connecting to the API, we computed total value of stocks/bonds portfolio.

### Part-2 Monte Carlo Simulation

- We obtained Five years' worth of historical data for SPY and AGG using the Alpaca API "get_barset()" function, and a Monte Carlo simulation was configured to forecast 30 years cumulative returns.
- We then calculated the expected portfolil returns at 95% lower and upper confidenece intervals based on $20,000 initial investment. 
