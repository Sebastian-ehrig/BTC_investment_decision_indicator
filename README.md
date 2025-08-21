# Bitcoin Trading Indicator for Informed Investment Decisions
Advanced Bitcoin indicator for strategic investment decisions, delivering consistent returns while minimizing drawdown risk.

![GitHub last commit](https://img.shields.io/github/last-commit/Sebastian-ehrig/BTC_investment_decision_indicator)

## Introduction

This implementation provides a comprehensive investment strategy for Bitcoin (BTC) only. It combines multiple technical indicators and real-time on-chain data, which allows investors to make informed decisions regarding entry and exit points in the volatile BTC market. The strategy is designed to help achieve cumulative returns while minimising drawdown risk. The aim is to provide a holistic approach to BTC investments, considering both trend direction and momentum signals.

## Example period

The example showcases market behavior from November 2022 to August 2025, demonstrating precise market entries and capitalizing on buy and sell opportunities, thereby achieving a cumulative return of ~520%. Gray vertical bars indicate entry and exit time-positions, whereby red dots are sell points and blue dots are buying points.

![Example Output](Figures/BTC-USD_2025-08-21_11.png)

## Performance

This strategy has demonstrated strong performance between 2019 and 2025, accurately identifying both the top and bottom of the Bitcoin market, thereby avoiding 412 days of continuous market downtrend. This has resulted in an impressive 6510% return - compared to a buy and hold strategy that would have yielded "only" 1500% for the same period and with considerably higher risk!

![Example Output](Figures/BTC-USD_2025-08-21_21.png)

In addition, this strategy has also been backtested on historical data yielding consistent returns over an extended timeframe (Sept 2014 - Aug 2025). In particular, it successfully predicted the BTC bear-market bottom in 2015, 2019, and 2022 as well the market top of the 2017 and 2021 bull-market. However, if this strategy continues to work in the future remains to be seen.

![Example Output](Figures/BTC-USD_2025-08-21_31.png)

## Some indicators and on-chain data included in this implementation

- **Squeeze Momentum Indicator**: Identifies the beginning and end of trends by combining Bollinger Bands and Keltner Channels.
- **Moving Average Divergence Convergence (MACD)**: used to determine trend direction through the crossing of short-term and long-term moving averages.
- **Relative Strength Index (RSI)**: Evaluates overbought or oversold conditions in BTC's price, providing insights into potential reversal points.
- **Ease-of-Movement (EOM)**: Measures price change relative to volume, highlighting trend strength and potential reversals.
- **MVRV Z-Score**: identifies Bitcoin overvaluation or undervaluation by comparing market and realized value.

## Usage Note

This script was developed solely for personal investment decision-making. If you're interested in utilizing it for your own purposes, feel free to get in touch.

## Contributors

- [Sebastian Ehrig](https://github.com/Sebastian-ehrig)
