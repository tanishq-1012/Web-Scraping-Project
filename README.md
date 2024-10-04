# Web-Scraping-Project

Project Overview
This project is a simple web scraper that extracts data from a website using BeautifulSoup and Requests libraries in Python. The data is primarily focused on extracting table data from the HTML of the website. Once extracted, the data is processed and stored in a pandas DataFrame for easy manipulation. Finally, the processed data is saved as a CSV file in an output folder.

# Features

* Web Scraping: Extracts table data from a website's HTML using BeautifulSoup.
* Data Processing: Uses pandas to convert the extracted data into a DataFrame.
* CSV Export: Saves the processed data into a CSV file within an output folder.

# How to Run the Project

Prerequisites
Before running the project, ensure you have the following libraries installed:

* requests
* beautifulsoup4
* pandas

You can install them using pip:

pip install requests beautifulsoup4 pandas

# Detailed Workflow

1. Extract Data:
 * The script fetches the HTML content of the webpage using requests.
 * Using BeautifulSoup, it parses the HTML to find the required table data.
2. Process Data:
 *The data is cleaned and organized into a pandas DataFrame.
3. Save Data:
 *The DataFrame is exported to a CSV file and stored in the output/ directory.

# License

This project is licensed under the MIT License. You are free to use, modify, and distribute it as per the terms of the license.



