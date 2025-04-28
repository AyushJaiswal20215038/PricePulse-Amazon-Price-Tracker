
# PricePulse: Amazon Item Price Tracker

## Project Overview

PricePulse is a real-time price tracking tool for Amazon items.
It fetches the latest item prices, updates dynamically, and visualizes the price trend using live plots.
This project is useful for monitoring price changes over time and detecting sudden fluctuations.


## Features


- Fetches the latest price data for a selected Amazon product.

- Dynamically updates and plots Price vs Time in real-time.

- Automatically clears old plots for clean, live visualization.

- Displays item price spikes, drops, and fluctuations clearly.

- Lightweight and runs inside Google Colab or Jupyter Notebook.
## Technologies Used

- Python 3

- Matplotlib — for plotting graphs

- Pandas — for handling time-series data

- IPython.display — for clearing previous plots in real-time

- BeautifulSoup + Requests — web scraping is used to fetch live prices 
## How It Works
- Generate or fetch updated price and time data inside a function.

- Plot the price vs date graph after clearing previous outputs.

- Continuously call the function in a loop to simulate real-time updates
