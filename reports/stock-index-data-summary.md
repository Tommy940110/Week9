
# **Data Description and Summary**

This study utilizes a panel dataset of monthly stock index values collected between January 2024 and January 2025. The dataset is structured in a tidy format and includes three primary variables: the month and year of the observation (`月別`), the name of the stock market index (`股價指數`), and the numeric stock index value (`股價`). The data span 10 major international stock indices from markets including Taiwan, the United States, Japan, South Korea, Singapore, the United Kingdom, China, and Hong Kong. A complete variable specification and dataset structure is available in the [codebook for Stock Index Dataset].

Each of the ten indices is observed over 13 months, leading to a total of 132 observations. According to the variable summary file (`variable-summary.json`), the dataset is complete with no missing data. The `股價` (stock index value) variable ranges from a minimum of 237 to a maximum of 44,911, with a mean of approximately 15,466 and a standard deviation of 14,197, reflecting considerable variability across the indices. The `股價指數` variable is a factor with 10 levels, each representing a different national or regional stock market index.

## **Cross-sectional Summary**

To understand the performance of individual stock markets, we computed summary statistics for each index over the full sample period. As reported in `average-stock-by-index.json`, the United States' Dow Jones Industrial Index had the highest average stock price (40,851.77), followed by Japan's Nikkei 225 (38,825) and Taiwan's Weighted Index (21,545.31). In contrast, Taiwan’s Over-the-Counter Index and South Korea’s KOSPI Index exhibited the lowest average values, indicating relatively smaller market scales or different market dynamics.

The top three indices by average value, highlighted in `top3-stock-index.json`, underscore the dominance of developed markets with high market capitalization. These indices—Dow Jones, Nikkei 225, and Taiwan Weighted—are considered benchmarks for global economic conditions and investment trends.

## **Time-series Trends**

The temporal trend in the global stock market is examined by aggregating the average monthly stock prices across all indices. As detailed in `monthly-mean-stock.json`, the average monthly stock price increased steadily from 13,928.3 in January 2024 to 16,604.5 in January 2025. This upward trend indicates broad-based market optimism, which may reflect global macroeconomic recovery, monetary policy shifts, or investor sentiment. The accompanying rise in standard deviation—from 13,760 in early 2024 to over 15,800 in early 2025—suggests growing divergence across markets or increased volatility.

Overall, the dataset offers valuable insight into the comparative and dynamic behavior of major stock indices in 2024–2025. The clean structure and rich temporal and cross-sectional variation make it suitable for econometric modeling and financial market analysis.
