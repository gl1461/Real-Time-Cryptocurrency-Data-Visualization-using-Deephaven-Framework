# Crypto Price Analysis with Deephaven

This project uses Deephaven to analyze and visualize real-time cryptocurrency price data for **BTC-USD** and **ETH-USD**. The script aggregates, processes, and visualizes market data, highlighting price trends and relationships between Bitcoin (BTC) and Ethereum (ETH).

## Features

1. **Data Cleaning and Filtering**  
   - Removes unnecessary columns (`type`).  
   - Filters BTC trades with `size > 0.25` and ETH trades with `size > 5`.  
   - Highlights large BTC trades with `DEEP_RED` formatting.  

2. **Price Visualization**  
   - **Line plots:** BTC and ETH price trends over the latest 500 records.  
   - **Categorical bar plots:** Compare BTC and ETH prices at minute-level aggregation.  
   - **Scatter plot:** Visualizes the ratio relationship between ETH/BTC and BTC/ETH.  

3. **Minute-level Aggregation**  
   - Aggregates prices per minute using `lowerBin()` and averages.  
   - Combines BTC and ETH minute-level data into a single table.  
   - Computes ratios: `ETH_BTC = ETH_price / BTC_price` and `BTE_ETH = BTC_price / ETH_price`.  

## Requirements
- Python 3.8+  
- Deephaven (latest version)  
- Real-time or historical crypto trade data available as a Deephaven table  

## Usage
1. Load your trade data into `matches_table`.  
2. Run the script in a Deephaven Python environment.  
3. Visualizations will display interactive charts for analysis.

## Author
**Your Name / Team Name**  
**Email:** your.email@example.com  

