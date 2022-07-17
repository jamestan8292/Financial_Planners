# Financial_Planners

This application has prototypes of two financial planning tools for credit union members, viz:

1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Technologies

This application is written for use with Jupyter Lab. It uses the following packages/modules:

* [Pandas](https://github.com/pandas-dev/pandas)
* requests
* json
* alpaca_trade_api
* python-dotenv
* datetime
* MCForecastTools - provided in this repository

---


## Usage

In Windows GitBash or Mac Terminal app, enter "Jupyter Lab". Then open and run "financial_planning_tools.ipynb". An account must be registered with 
https://alpaca.markets, and the API keys obtained. The two API keys, ALPACA_API_KEY and ALPACA_SECRET KEY must be stored in a .env text file in the same directory as the application, in the following format:

ALPACA_API_KEY = "123456..."

ALPACA_SECRET KEY = "98765...."

---

## Contributors

This application is written by James Tan, with code snippets provided UBC Extension.

---

## License

MIT.
