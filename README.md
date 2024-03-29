# Unit 5 - Financial Planning

![Financial Planner](Images/5-4-challenge-image.png)


## Background

You’ve decided to start a fintech consulting firm that focuses on projects to benefit local communities. You just won your first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants you to develop a prototype application to present at its next assembly.

---

### What You're Creating
You’ll create two financial analysis tools by using a single Jupyter Notebook:

1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.

---

### Files
* [Personal Finance Planner](financial_planning_tools)

* [MCForecastTools toolkit](MCForecastTools.py)

---

### Resources

This homework will utilize two APIs:

* The **Alpaca Markets API** will be used to pull historical stocks and bonds information.  
    
* The **Alternative Free Crypto API** will be used to retrieve Bitcoin and Ethereum prices.

The documentation for these APIs can be found via the following links:

* [Free Crypto API Documentation](https://alternative.me/crypto/api/)

* [AlpacaDOCS](https://alpaca.markets/docs/)
  
---

## Instructions

### Part 1: Create a Financial Planner for Emergencies
In this section, you’ll create a personal financial planner for emergencies. To develop the prototype, assume the following:

* The average monthly household income for each credit union member is $12,000.

* Each credit union member has a savings portfolio that consists of a cryptocurrency wallet, stocks, and bonds.
    * Assume the following amount of crypto assets: `1.2` BTC and `5.3` ETH.

    * Assume the following amount of shares in stocks and bonds: `50` SPY (stocks) and `200` AGG (bonds).

Use the starter Jupyter notebook to complete the following steps.

## Technologies

> This project uses the software jupyter lab with the following  softwares, and their installed versions :

### Part 2 - Retirement Planning

In this section, you will use the Alpaca API to fetch historical closing prices for a retirement portfolio and then Use the MCForecastTools toolkit to create Monte Carlo simulations to project the portfolio performance at `30` years. You will then use the Monte Carlo data to answer questions about the portfolio.

Follow the steps outlined in the starter notebook to complete the following:

#### Monte Carlo Simulation

1. Use the Alpaca API to fetch five years historical closing prices for a traditional `40/60` portfolio using the `SPY` and `AGG` tickers to represent the `60%` stocks (`SPY`) and `40%` bonds (`AGG`) composition of the portfolio. Make sure to convert the API output to a DataFrame and preview the output.

    > *Note*: As before, use the parameter `limit=1000` to ensure you get the most data possible back from the API. In Monte-Carlo Simulation, getting data as far back as possible matters, because if we simulate using only small amounts of data during a recent time when markets are booming, or instead falling precipitously, a Monte-Carlo Analysis will inadvertently extrapolate this temporary market movement too far into the future. Getting data over a longer time period mitigates this effect.

2. Configure and execute a Monte Carlo Simulation of `500` runs and `30` years for the `40/60` portfolio.

3. Plot the simulation results and the probability distribution/confidence intervals.
   
![monte carlo](Images/5-4-monte-carlo-histogram.png)
        
![histogram](Images/5-4-monte-carlo-line-plot.png)

#### Retirement Analysis

1. Fetch the summary statistics from the Monte Carlo simulation results.

1. Given an initial investment of `$20,000`, calculate the expected portfolio return in dollars at the `95%` lower and upper confidence intervals.

2. Calculate the expected portfolio return at the `95%` lower and upper confidence intervals based on a `50%` increase in the initial investment.

---

## Technologies


---

The following python modules are also used in the application. Remember to install these packages via Terminal for MacOS/Linux or GitBash for windows clients. 
* [pandas](https://github.com/pandas-dev/pandas) - pandas is used to interact with data packages, plot data frames, create new dataframes, describe abailable data, and helps traders and fintech proffesionals organize financial data to perform advanced decisionmaking. 

* [pathlib](https://github.com/python/cpython/blob/main/Lib/pathlib.py) - Allows the user to specify the path to a data frame / any data in a csv file. 

* [numpy]
(https://github.com/numpy/numpy)
- NumPy is the fundamental package for scientific computing with Python. It provides: a powerful N-dimensional array object, sophisticated (broadcasting) functions tools for integrating C/C++ and Fortran code, useful linear algebra, Fourier transform, and random number capabilities. 

* [json]
(https://github.com/nlohmann/json)
- JSON (JavaScript Object Notation), specified by RFC 7159 (which obsoletes RFC 4627) and by ECMA-404, is a lightweight data interchange format inspired by JavaScript object literal syntax (although it is not a strict subset of JavaScript. 

* [os]
(https://docs.python.org/3/library/os.html)
- This module provides a portable way of using operating system dependent functionality. If you just want to read or write a file see open(), if you want to manipulate paths, see the os.path module, and if you want to read all the lines in all the files on the command line see the fileinput module. For creating temporary files and directories see the tempfile module, and for high-level file and directory handling see the shutil module..

* [dotenv]
(https://pypi.org/project/python-dotenv/)
- Python-dotenv reads key-value pairs from a .env file and can set them as environment variables. It helps in the development of applications following the 12-factor principles.

* [alpaca_trade_api]
(https://github.com/alpacahq/alpaca-trade-api-python)
- alpaca-trade-api-python is a python library for the Alpaca Commission Free Trading API. It allows rapid trading algo development easily, with support for both REST and streaming data interfaces. For details of each API behavior, please see the online API document.

* [requests]
(https://pypi.org/project/requests/)
- Requests is a simple, yet elegant, HTTP library..

* [MCForecastTools]
- 'Monte Carlo Forecast Tools' provided by the Berkley Fintech Bootcamp; provides functionality to help interact with data, and simulate market results with varying weight, stock, and time paramaters.


## Installation Guide

There are fo installations neccesary for the program to run. Make sure these are installed via terminal (for MacOS) or GitBash (Windows/Linux)

'''python
    pip3 install pandas
    pip3 install numpy
    pip3 install pathlib
    conda install -c pyviz hvplot geoviews
'''


## Usage

In order to interact with the application, please first clone the repository, and then in the command line run type in:

'''python
python financial_planning_tools.ipynb
'''
NOTE : remember to be in the application folder (clone) when imputing the command.
---

## Contributors

The sole contributor for this project is:

**NAJIB ABOU NASR**
 no instagram or linkedin yet!

--

## License

Using the 'MIT' license!

--
## History

### 
    Here, I documented my command line inputs, to show the changes I had made, and document the debugging and programing process:  


© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
