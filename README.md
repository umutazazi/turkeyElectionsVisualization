# Election Results Visualization

This project involves fetching and visualizing election results data using Selenium and Plotly libraries in Python.

## Description

This Python project fetches election results data from a website, processes and cleans the data, and then creates interactive visualizations using Plotly library. It uses Selenium to automate the web scraping process and Plotly for creating various visualizations.

## Features

- Web scraping using Selenium to fetch election results data.
- Data preprocessing and cleaning.
- Interactive visualizations using Plotly.
- Visualizations for national, Istanbul, Ankara, and Izmir election results.
- Histogram showing the total votes for each presidential candidate.

## Prerequisites

- Python 3.x
- `pip` package manager
- Chrome browser (required for Selenium)
- ChromeDriverManager (Python library for managing ChromeDriver)

## Installation

1. Clone the repository:

git clone <repository_url>


2. Install the required Python libraries:

pip install -r requirements.txt


3. Download and install the Chrome browser if not already installed.

## Usage

1. Run the `app.py` script:

 python app.py

 
2. Open a web browser and go to the provided URL (usually `http://127.0.0.1:5000/`) to view the interactive visualizations.

## Project Structure

- `app.py`: Main application script that fetches data, processes it, and creates visualizations.
- `fetch.py`: Contains the `Fetcher` class for web scraping using Selenium.
- `templates/index.html`: HTML template for rendering the Plotly visualizations.

## Acknowledgments

- This project utilizes the Selenium and Plotly libraries in Python.
- The [webdriver-manager](https://pypi.org/project/webdriver-manager/) package is used to manage the ChromeDriver.



