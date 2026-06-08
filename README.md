# Stock Portfolio Competition Analysis

A head-to-head comparison of two stock portfolios using live market data — mine vs. a friend's. Built as a DS350 project at BYU-Idaho.

**[Live Report](https://logan-lay21.github.io/stock-portfolio-analysis/stocks_tidyquant.html)**

---

## Overview

Each person picked 3 stocks. This project pulls real historical price data for all six, calculates portfolio value over time, and visualizes how each portfolio performed against the other.

The goal was to practice pulling live financial data, working with time series, and building clear multi-stock visualizations with intentional color encoding.

## Key Features

- Live stock price data pulled via `tidyquant`
- Portfolio value calculated and tracked over time for both picks
- Multi-stock line charts with deliberate color encoding to distinguish portfolios
- Written interpretation of results

## Tools Used

| Tool | Purpose |
|---|---|
| R | Core language |
| tidyquant | Pulling live stock price data |
| tidyverse / dplyr | Data wrangling |
| ggplot2 | Visualization |
| Quarto | Report rendering |

## How to Run

1. Clone the repo
2. Open the `.qmd` file in RStudio or Positron
3. Render with Quarto — stock data will pull live on render
