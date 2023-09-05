# cci-trend-signal-to-telegram
Utilize the 'tradingview-ta' package to extract CCI signals that are trend-oriented and seamlessly relay them to a designated Telegram channel.


# Trading Signal Notifier

## Overview
This Python script helps you detect trading signals, analyze market trends, and send notifications to a Telegram channel. It leverages the 'tradingview-ta' package to extract relevant data and make informed decisions.

## Getting Started

### Prerequisites
Make sure you have the following packages installed:
- `tradingview-ta`
- `numpy`
- `schedule`
- `telegram`

You can install them using pip:
pip install tradingview-ta numpy schedule python-telegram-bot


### Setting Up Your Telegram Bot
1. Create a Telegram Bot and obtain the API token.
2. Define your Telegram channel username where you want to send notifications.

### Configuration
- Add your Telegram Bot token and channel username in the script.

### Usage

#### Adding Symbols
- Define the trading symbols you want to monitor.

#### Detecting Signals using CCI Oscillators
- The script uses the Commodity Channel Index (CCI) to detect signals.

#### Detecting Trend using Slow and Fast EMA
- Utilizes Exponential Moving Averages (EMA) to determine market trends.

#### Detecting Signals based on CCI and Trend functions output
- Combines CCI signals and trend analysis for more accurate trading decisions.

#### Send to Telegram Channel
- Sends trading signals and updates to your designated Telegram channel.

#### Market Scanner
- Continuously scans the market for potential trading opportunities.


### Acknowledgments
Special thanks to the developers of the 'tradingview-ta' package.
Inspired by the need for an efficient trading signal notifier.

