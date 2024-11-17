# Cookie Clicker Bot Automation

This is a simple Python script using Selenium to automate the "Cookie Clicker" game. The script clicks on the cookie continuously and purchases upgrades automatically to increase your cookies per second (CPS).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [License](#license)

## Installation

Before running this script, you need to install the required dependencies. Follow these steps:

### 1. Install Python 3
Ensure you have Python 3 installed. You can download Python from the official website [here](https://www.python.org/downloads/).

### 2. Install Dependencies
Install the required libraries using pip:

```bash
pip install selenium
```
You also need to install webdriver-manager to manage the Chrome driver automatically:
```bash
pip install webdriver-manager
```
### 3. Download ChromeDriver
Make sure you have Google Chrome installed, as this script uses ChromeDriver for web automation.
---
## Usage
To run the script, simply execute the Python file in your terminal or command prompt:
```bash
python main.py
```
The bot will automatically start clicking the cookie on the Cookie Clicker webpage, purchase upgrades every 5 seconds, and stop after 5 minutes. The number of cookies per second (CPS) will be displayed at the end of the execution.
## How It Works
1. **Cookie Clicking**: The script clicks the cookie continuously to accumulate cookies.
2. **Upgrade Checking**: Every 5 seconds, the bot checks for available upgrades and compares the prices to the current cookie count.
3. **Upgrade Purchasing**: The bot will purchase the most expensive upgrade that it can afford.
4. **Stopping After 5 Minutes**: After 5 minutes, the script will stop and output the cookies per second (CPS) count.
5. **Error Handling**: The script includes retries in case of errors or connection issues.

## Flow of Execution:
1. **Start Cookie Clicking**: The bot clicks the cookie
2. **Check Upgrades**: Every 5 seconds, the bot checks the store for any upgrades.
3. **Purchase Upgrade**: If it has enough cookies, it buys the most expensive upgrade.
4. **Repeat**: This process continues for 5 minutes.
5. **Stop**: After 5 minutes, the bot stops, and the cookies per second count is displayed.

## License
This project is open-source and free to use. However, please note that this script is for educational purposes only. Use it responsibly and respect the terms and conditions of the game website.



Happy clicking! 🍪
