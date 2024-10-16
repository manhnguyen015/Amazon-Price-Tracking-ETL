
# Amazon Web Scraper

This project is a simple web scraper built in Python that extracts product information from Amazon, specifically the **product title** and **price**. The scraper retrieves the data using the `requests` library and parses the HTML using `BeautifulSoup`. The scraped data is then saved into a CSV file (`AmazonWebScraperDataset.csv`) for easy analysis and reference.

### Features:
- Scrapes **product title** and **price** from an Amazon product page.
- Saves the data into a CSV file with appropriate headers.
- Handles potential issues like missing or dynamic content.

### Requirements:
- Python 3.x
- `requests` library
- `BeautifulSoup` library from `bs4`
- `csv` (standard library)

### Usage:
1. Run the script to scrape the product information from a specified Amazon product URL.
2. The data will be saved in the CSV file `AmazonWebScraperDataset.csv` with proper formatting, ready for use in applications like Excel or Google Sheets.
