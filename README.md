# stock-revenue-analysis
## Project Title: Stock and Revenue Analysis of Tesla and GameStop

## Overview
This project analyzes historical stock prices and revenue data for Tesla and GameStop. Using Python libraries like `yfinance`, `pandas`, and `plotly`, the project visualizes the trends in stock prices and quarterly revenues.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Code Explanation](#code-explanation)


## Installation
To run this project, you need to have Python installed along with the following libraries:
- `yfinance`
- `pandas`
- `requests`
- `beautifulsoup4`
- `plotly`

You can install the required libraries using pip:
```bash
pip install yfinance pandas requests beautifulsoup4 plotly
```
## Usage
To execute the project:

  1. Clone the repository:
   ```bash
    git clone https://github.com/xmoe10/stock-revenue-analysis.git
```
 2. Navigate to the project directory:
   ```bash
    cd yourprojectname
   ```
3. Run the Jupyter Notebook:
```bash
 jupyter notebook
  ```
4. Open the notebook and run the cells to visualize the stock and revenue data for Tesla and GameStop.



## Data Sources
- Tesla stock data: Obtained from Yahoo Finance using `yfinance`.
- GameStop stock data: Obtained from Yahoo Finance using `yfinance`.
- Tesla revenue data: Scraped from the specified URL (insert actual URL).
- GameStop revenue data: Scraped from the specified URL (insert actual URL).
## Code Explanation
- Data Fetching: The project fetches stock data using the `yfinance` library.
- Data Cleaning: The code cleans the scraped revenue data by removing missing values and empty strings.
- Visualization: The project uses Plotly to create interactive graphs for stock prices and revenues.
