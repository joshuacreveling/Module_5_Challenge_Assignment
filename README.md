# Module 5 Challenge - Financial Planning with APIs and Simulations

---

## Description

This Jupyter Lab Notebook has two seperate application utilites; Part 1: Create a Financial Planner or Emergencies and Part 2: Create a Financial Planner for Retirement.

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

1. Evaluate the Cryptocurrency Wallet by Using the Requests Library
2. Evaluate the Stock and Bond Holdings by Using the Alpaca SDK
3. Evaluate the Emergency Fund

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

1. Create the Monte Carlo Simulation
2. Analyze the Retirement Portfolio Forecasts (30 Years)
3. Forecast Cumulative Returns in 10 Years

---

## Technologies

This project leverages JupyterLab Version 3.0.14 in association with Anaconda distribution and the Conda package manager.  The following packages are also used: 

* [pandas](https://github.com/pandas-dev/pandas) - For the current source code hosted on GitHub.

Create accounts at the following site to get Alpaca API and Secret Key: 

* [Alpaca](https://app.alpaca.markets/signup) - For Alpaca signup page.

---

## Installation Guide

Before running the application, confirm installation of Python modules and libraries to facilitate API requests:

```python
  conda list requests
  conda list json
```

To directly install the dependanices, run the following commands: 

```python
  conda install -c anaconda requests
  conda install -c jmcmurray json
```

Install the python-dotenv Library: 

```python
  pip install python-dotenv
```

Install the Alpaca SDK:

```python
  pip install alpaca-trade-api
```
---

## Contributors

Joshua Creveling

Email: josh.creveling22@gmail.com

GitHub: https://github.com/joshuacreveling

LinkedIn: https://www.linkedin.com/in/joshua-creveling/

*Starter template provided by Trilogy Education Services*

---

## License

MIT
