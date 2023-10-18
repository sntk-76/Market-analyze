# Financial Market Analysis

## Project Overview

This project aims to analyze financial market data, specifically focusing on the "NYA" index. The dataset includes four key price values: Open, Close, High, and Low. Our primary objectives in this project are:

1. Extract the "NYA" index from the dataset.
2. Create a linear time-price chart to visualize the market's price movements over time.
3. Identify and handle any potential noise or outliers in the data.
4. Address missing values (NaN) that may affect the analysis.

## Dataset

The dataset used in this project contains historical price data for the financial market. It is structured with columns representing the following parameters:

- Open: Opening price for a given time period.
- Close: Closing price for a given time period.
- High: Highest price reached during a given time period.
- Low: Lowest price reached during a given time period.
- Date: Timestamp associated with each data point.
- Volume: Trading volume associated with each data point.
- Adj Close: Adjusted closing price.

## Analysis Steps

### 1. Data Extraction

We begin by extracting data related to the "NYA" index, allowing us to focus on this specific market indicator for our analysis.

### 2. Time-Price Chart

We create a linear time-price chart to visualize the market's performance over time. This chart provides a clear view of price movements and trends.

### 3. Noise Detection

One of our key objectives is to identify and address potential noise or outliers in the dataset. We use various methods, including data visualization and filtering, to detect and handle noisy data points.

### 4. Handling Missing Data

We address any missing values (NaN) that may exist in the dataset. Handling missing data is crucial for ensuring the accuracy of our analysis.

## Repository Structure

- `data.csv`: The dataset containing financial market data.
- `financial_analysis.ipynb`: A Jupyter Notebook containing the project's code and analysis.
- `README.md`: This file, providing an overview of the project.

## Usage

You can explore the project and analysis in the Jupyter Notebook, `financial_analysis.ipynb`, which contains the code, visualizations, and detailed explanations of the analysis process.

## Contribution

Contributions to this project are welcome. If you have suggestions, improvements, or additional analysis techniques, please feel free to submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).
