# Getting and Visualizing stock data using Python

This code explores the yfinance library to get stock data from yahoo finance, and altair to visualize the data.

![](https://drive.google.com/open?id=1UIT5hrI-gxkJewQw8EUlxIPLVgU15iSq)

## Installation

Use the package manager [pip](https://pypi.org/) to install packages.

```bash
pip install pandas
pip install yfinance
pip install altair
```

## Usage

```python
import yfinance as yf
import altair as alt
import pandas as pd

# Define a function take an argument as a company name
def get_data(company_name):

# Call the function by passing the name of the company as 'GOOGL'
get_data('GOOGL')
```


