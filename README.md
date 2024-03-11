# Stock Analysis Chatbot Assistant

## Overview
This is a chatbot assistant designed to provide stock analysis information based on user input. The assistant utilizes OpenAI's GPT-3.5 language model for natural language processing and yfinance for fetching stock data. It offers various functionalities such as getting the latest stock price, calculating moving averages (SMA and EMA), computing the Relative Strength Index (RSI), determining the Moving Average Convergence Divergence (MACD), and plotting stock price over the last year.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/stock-analysis-chatbot.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Obtain an OpenAI API key and save it to a file named `API_KEY`.

4. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Launch the application by running the command specified in the setup.

2. Enter your input in the text input field.

3. The chatbot will respond with the requested stock analysis information based on the input.

## Features
- **Get Stock Price**: Retrieve the latest stock price for a given ticker symbol.
- **Calculate Simple Moving Average (SMA)**: Compute the SMA for a specified window and ticker symbol.
- **Calculate Exponential Moving Average (EMA)**: Compute the EMA for a specified window and ticker symbol.
- **Calculate Relative Strength Index (RSI)**: Calculate the RSI for a given ticker symbol.
- **Calculate Moving Average Convergence Divergence (MACD)**: Calculate the MACD for a given ticker symbol.
- **Plot Stock Price**: Generate a plot of the stock price over the last year for a given ticker symbol.

## Functions
The application provides several functions accessible through the chat interface:
- `get_stock_price`: Retrieves the latest stock price.
- `calculate_SMA`: Calculates the SMA.
- `calculate_EMA`: Calculates the EMA.
- `calculate_RSI`: Calculates the RSI.
- `calculate_MACD`: Calculates the MACD.
- `plot_stock_price`: Plots the stock price over the last year.

## Acknowledgments
- OpenAI for providing the GPT-3.5 language model.
- Yahoo Finance (yfinance) for providing access to stock data.


---

Make sure to customize the URLs, usernames, and paths according to your project's specifics. You can also add more sections or details as needed.
