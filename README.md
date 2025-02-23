# GameStop and Tesla Stock & Revenue Analysis

This repository contains analysis of **GameStop (GME)** and **Tesla (TSLA)** stock and revenue data, using Python and various libraries to extract, process, and visualize historical data. The analysis includes stock price trends, revenue figures, and visualizations showing the relationship between stock prices and revenue for these two companies.

## Table of Contents
1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Data Sources](#data-sources)
4. [Plot Overview](#plot-overview)
5. [Conclusion](#conclusion)
6. [License](#license)

## Overview

This project focuses on analyzing the historical stock data and revenue for **GameStop (GME)** and **Tesla (TSLA)**. The main goals are:
- Extract stock and revenue data using `yfinance` and web scraping techniques.
- Clean and preprocess the data (remove commas and dollar signs).
- Generate visualizations to observe trends in stock prices and revenue over time.

The project aims to provide insights into how the stock prices and revenue of these companies evolved and whether there are any noticeable trends.

## Technologies Used

- **Python**: The primary programming language used for analysis.
- **Pandas**: Used for data manipulation and cleaning.
- **yfinance**: A library to fetch stock data.
- **BeautifulSoup**: For scraping revenue data from web pages.
- **Plotly**: For creating interactive visualizations.
- **Matplotlib**: For static visualizations.
- **Requests**: For making HTTP requests to download webpages.

## Data Sources

1. **Stock Data**: 
   - Tesla (TSLA) and GameStop (GME) historical stock data obtained via the `yfinance` library.
   - The stock data includes information such as the date, open, high, low, close prices, and volume.
   
2. **Revenue Data**:
   - GameStop revenue data scraped from a publicly available web page using BeautifulSoup.
   - Tesla revenue data sourced from publicly available data and financial reports.

## Plot Overview

### Tesla Stock & Revenue Data

Below is the graph showing the historical stock price and revenue of **Tesla (TSLA)**. The data includes stock prices up until June 2021 and revenue data up until April 2021.

![Tesla Plot](https://github.com/saf1Hckr/Tesla-and-GameStop-Stock-Revenue-Analyze-/blob/main/Tesla.png)

### GameStop Stock & Revenue Data

Below is the graph showing the historical stock price and revenue of **GameStop (GME)**. The data includes stock prices up until June 2021 and revenue data up until April 2021.

![GameStop Plot](https://github.com/saf1Hckr/Tesla-and-GameStop-Stock-Revenue-Analyze-/blob/main/GameStop.png)

## Conclusion

This project demonstrates how to extract, process, and visualize stock and revenue data for GameStop and Tesla. By analyzing the data, we can explore trends in stock prices and revenue over time. Interactive visualizations make it easier to identify key trends and potential relationships.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
