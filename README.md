# Stock Data Extraction and Visualization

This project focuses on **extracting stock price and revenue data** for Tesla and GameStop using **Python**, and **visualizing** the trends over time.  
We leverage **yfinance** for stock data and **web scraping** techniques for revenue data, and build simple graphs to better understand company performance.

## Project Structure

- **Data Extraction:**
  - Tesla and GameStop stock data extracted using `yfinance`.
  - Tesla and GameStop revenue data extracted using web scraping with `requests` and `BeautifulSoup`.
  
- **Data Cleaning:**
  - Formatted and cleaned revenue fields for analysis.

- **Visualization:**
  - Plotted stock price vs revenue using a custom `make_graph` function.

## Technologies Used

- Python
- yfinance
- pandas
- BeautifulSoup
- matplotlib

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
