Project Title
The title of this project is Financial Planning Tools . I created two financial analysis tools by using a single Jupyter notebook:

Technologies
# Import the required libraries and dependencies
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline

Installation Guide

Requires .env file to access the Data from the API calls.

Calculate the monthly debt ratio
monthly_debt_ratio = calculate_monthly_debt_ratio(debt, income)
print(f"The monthly debt to income ratio is {monthly_debt_ratio:.02f}")




Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.
![Portfolio Pie Chart](OneDrive/Desktop/Homework_5_-MOD_5/MOD_5im2.png)
Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

![30 year Monte Carlo Simulation](OneDrive/Desktop/Homework_5_-MOD_5/MOD_5im1.png)

Contributors
In addtion to me the GW Bootcamp TA, LA, and tutors help me create this project

License
The Source code is for educational purposes only and should not be used to qualify any applicant for a loan. Feel free to use for any educational needs