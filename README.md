# Automation in Python

Welcome to the Python Automation Scripts Repository! This repository contains a collection of Python scripts for automating various tasks and processes. These scripts are designed to simplify repetitive tasks and improve productivity.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Scripts](#scripts)
  - [AutomateNewsAljazeera.py](#automatenewsaljazeerapy)
  - [AutomateNewsBackground.py](#automatenewsbackgroundpy)
- [License](#license)

## Getting Started

### Prerequisites

To run the Python scripts in this repository, you need to have the following installed:

- Python (Latest version recommended)
- PyCharm (Recommended)
- Chromedriver (version may varries based on your web browser)
- Selenium Library ([How to install selenium in Python](https://selenium-python.readthedocs.io/installation.html))
- Pandas Library ([How to install Pandas in Python](https://pandas.pydata.org/docs/getting_started/install.html#installing-from-pypi))

### Installation

1. Clone or copy this repository to your local machine.
2. Install all the Prerequisites libraries

## Scripts

### AutomateNewsAljazeera.py

The provided Python script automates web scraping of news titles and links from the Al Jazeera website. It utilizes the **Selenium library** to interact with the chrome web browser and fetches the most-read news articles from the Al Jazeera homepage. The scraped data is then organized into a Pandas DataFrame and exported to a CSV file named "**AutomateNewsAljazeera.csv**."

To use the script, ensure you have installed the necessary libraries: **Selenium** and **Pandas**. Also, make sure to provide the correct path to the chromedriver.exe (required for Chrome browser automation) or adjust the WebDriver according to your preferred browser.

### AutomateNewsBackground.py


This Python script demonstrates web scraping of news titles and links from the Al Jazeera website in headless mode using **Selenium**. The script uses the Chrome WebDriver to fetch the most-read news articles from the Al Jazeera homepage in **headless mode**.

In headless mode, the web browser runs in the background without displaying a visible window, making the automation process faster and less intrusive.

The scraped data, consisting of article titles and corresponding links, is organized into a **Pandas DataFrame** and exported to a CSV file named "**AutomateNewsAljazeera.csv**."

