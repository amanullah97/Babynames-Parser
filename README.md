# Babynames-Parser
"Web Scraping Baby Names Data from [babynames](https://babynames.com/) using Selenium"

This Git repository contains a Python script that utilizes Selenium to scrape baby names data from the [babynames](https://babynames.com/) website. The script interacts with the website, navigates through various pages, and extracts relevant information about baby names.

The `BabyNames` class initializes the CSV file to store the scraped data and sets up the Selenium web driver. It starts by accessing the main website URL and then proceeds to parse the data.

The `parse` method finds and retrieves URLs for different letters of the alphabet, while the `parse_letters` method extracts URLs for individual names starting with each letter. The script then navigates to each name URL and calls the `export_items` method to extract specific information about the name, such as the name itself, gender, origin, meaning, description, and source URL. The extracted data is written to a CSV file using the `csv` module.

The script utilizes Selenium's capabilities to interact with the website, find elements using CSS selectors and XPath, and extract desired information from the web page.

This project demonstrates how to scrape baby names data from babynames.com using Selenium, enabling the collection of useful information for analysis or further processing.
