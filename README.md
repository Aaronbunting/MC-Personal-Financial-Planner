# MC-Personal-Financial-Planner

Empower Your Financial Journey with the Personal Finance Planner

## Introduction
Enter the world of prudent financial decision-making with the Personal Finance Planner. This Python script presents a comprehensive solution for visualizing your savings and investments, enabling you to make informed choices. By fetching real-time cryptocurrency and stock prices, it calculates the current value of your holdings and employs a Monte Carlo simulation to project the value of your stock and bond investments over the span of 30 years.

## Backgroud
Upon running the script, you'll be presented with:

- The current valuation of your cryptocurrency and stock holdings
- A visually insightful pie chart illustrating the composition of your savings
- Pertinent details about your emergency fund
- A dynamic Monte Carlo simulation, projecting the cumulative returns of a 60% stocks (SPY) and 40% bonds (AGG) portfolio over the next three decades
- A line plot portraying 500 simulated cumulative return paths
- A histogram outlining the distribution of cumulative returns
- A range of potential outcomes for initial investments of $20,000 and $30,000 over 30 years, backed by a 95% confidence interval

## Important Note
Let's be clear: this script serves informational purposes only. It should not be misconstrued as financial advice. The Monte Carlo simulation is based on historical data and does not guarantee future performance. Prior to any investment decisions, seek counsel from a financial advisor.

## Dependencies
To embark on this journey, ensure you have the following dependencies in place:

- pandas
- os
- requests
- dotenv
- alpaca_trade_api
- MCForecastTools

## Steps
Kickstart your journey by installing the required dependencies.

Configure a .env file containing the following variables:

ALPACA_API_KEY=<your_alpaca_api_key>
ALPACA_SECRET_KEY=<your_alpaca_secret_key>

Personalization
Personalize the script by updating these variables with your current assets and investments:

- my_btc
- my_eth
- my_agg
- my_spy
- monthly_income

Embark on the Journey
Execute the script using the command:

python personal_finance_planner.py
