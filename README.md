# Crypto-Trading-Analysis

## Overview

This project contains an analysis of  Crypto Store, a cryptocurrency trading platform. The analysis explores various trading aspects such as trade types, transaction fees, time-based patterns, coin preferences, and profitability metrics. Key findings provide valuable insights into user behavior, platform activity, and opportunities for optimization.

## Data Preparation

Key data preparation steps included:
- Standardizing numerical columns for accurate calculations.
- Formatting date and time columns for time-based analysis.
- Removing duplicates and addressing missing values to ensure data integrity.
- Defining key metrics (e.g., "Total Trade Fee", "Fee to Amount Ratio") using DAX formulas in Power BI.
- Creating date-time bins to effectively group data.

## Key Findings

### 1. Trade Type Analysis
- Sell trades are more likely to be completed (82.5%) compared to buy trades (68.3%).
- Sell trades occur more frequently, with a ratio of 17,994 sell trades to 4,698 buy trades.

### 2. **Fee Analysis**
- Zero-fee transactions often arise from promotional offers or specific trade types.
- High-volume traders (e.g., institutions) generate significant revenue, contributing $66,521.66 in transaction fees.

### 3. **Time-Based Analysis**
- Peak trading activity occurs between 3 pm to 7 pm, possibly influenced by after-work activity in Ghana and Malawi.
- Low trading volume is observed between 2 am and 8 am, potentially due to time zone differences.

### 4. **Currency and Coin Analysis**
- USDT contributes more revenue than BTC due to its stability and higher usage in trading pairs.
- USD is the dominant currency, with over 22,000 transactions, while local currencies like GHS are less frequently used.

### 5. **Transaction Patterns**
- Smaller trades are completed faster due to higher liquidity, while larger trades take longer and may incur lower relative fees.

### 6. **Profitability Metrics**
- Buy trades show limited profitability, often due to market downturns or poor timing.
- September saw the highest profitability, with $11,722.24 in fees, likely linked to favorable market conditions.

## Recommendations

1. Target peak hours (3 pm to 7 pm) for promotions to increase activity.
2. Offer zero-fee promotions for high-frequency traders to boost user engagement.
3. Increase support for local currencies (GHS) to promote their use.
4. Focus on stable coins like USDT to cater to users seeking stability.
5. Provide tools for informed buy trade decisions and real-time market insights.
6. Streamline large trade processes with reduced fees and faster execution.

## Limitations

The analysis is limited by incomplete data for May and November, which may affect the accuracy of certain findings.
