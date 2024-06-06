# Stock Data Analysis

## Description

This project involves extracting and visualizing stock data for Tesla and GameStop using a Jupyter Notebook. Using the `yfinance` library, historical stock data is retrieved and plotted. Additionally, web scraping techniques are employed to extract revenue data for both companies. The project is structured as follows:

1. **Define a Function that Makes a Graph**: A function is created to facilitate the plotting of graphs.
2. **Extract Stock Data using yfinance**: Historical stock data for Tesla and GameStop is extracted using the `yfinance` library.
3. **Webscraping for Revenue Data**: Revenue data for Tesla and GameStop is extracted from the web using web scraping techniques.
4. **Plotting Stock and Revenue Data**: The extracted data is visualized using graphs to provide a clear and concise representation of the stock and revenue trends.

## Acknowledgement

This project was completed as part of the IBM Python Project for Data Science course.

## Getting Started

### Prerequisites

- Python 3.x
- `yfinance==0.1.67`
- `beautifulsoup4==4.10.0`
- `requests`
- `nbformat==4.2.0`
- `plotly`
- `notebook` (Jupyter Notebook)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/stock-data-analysis.git
    ```
2. Install the required libraries:
    ```bash
    pip install yfinance==0.1.67
    mamba install bs4==4.10.0 -y
    pip install nbformat==4.2.0
    pip install plotly
    pip install notebook
    ```

## Usage

1. Navigate to the project directory:
    ```bash
    cd stock-data-analysis
    ```
2. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3. Open the Jupyter Notebook file (`.ipynb`) in the Jupyter interface.
4. Follow the steps in the notebook to:
    - Import the required libraries:
        ```python
        import yfinance as yf
        import pandas as pd
        import requests
        from bs4 import BeautifulSoup
        import plotly.graph_objects as go
        from plotly.subplots import make_subplots
        ```
    - Extract stock data using `yfinance`.
    - Extract revenue data using web scraping.
    - Plot the stock and revenue data using `plotly`.
