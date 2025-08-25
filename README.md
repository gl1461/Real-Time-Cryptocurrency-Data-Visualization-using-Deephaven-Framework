# Real-Time Cryptocurrency Data Visualization Using Deephaven Framework

This project provides real-time visualization of cryptocurrency price data for **Bitcoin (BTC)** and **Ethereum (ETH)** using the **Deephaven** Python framework. It includes price tracking, minute-level aggregation, and comparative analysis between BTC and ETH.

---

## Features

- **Real-Time Price Tracking**: Fetch and display real-time BTC and ETH prices.  
- **Large Trade Highlighting**: Highlight large BTC and ETH trades (e.g., BTC trades > 0.25, ETH trades > 5).  
- **Minute-Level Aggregation**: Aggregate price data at the minute level using `lowerBin` and `avg_by`.  
- **Comparative Analysis**: Calculate and visualize BTC/ETH price ratios.  
- **Interactive Visualizations**:
  - Line plots for BTC and ETH prices over time.
  - Bar charts comparing BTC and ETH prices.
  - Scatter plot of BTC/ETH vs ETH/BTC ratios.

---

## Installation

1. Install Deephaven Python API:

```bash
pip install deephaven
Clone this repository:

2.Clone this repository:

'''bash
git clone https://github.com/yourusername/Real-Time-Cryptocurrency-Data-Visualization.git
cd Real-Time-Cryptocurrency-Data-Visualization
