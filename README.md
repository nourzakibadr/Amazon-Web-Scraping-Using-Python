# Amazon-Web-Scraping-Using-Python
A Python-based Amazon web scraper that extracts product details such as title and price, stores them in a CSV file, and supports automated periodic price tracking.

# Amazon Web Scraper

A Python project that scrapes product details from Amazon, including product title and price, and saves them into a CSV file for price tracking over time. The scraper can be automated to run periodically for monitoring price changes.

## Features
- Extracts product title and price from a given Amazon product URL.
- Saves data into a CSV file with date stamps.
- Supports automation for regular tracking (e.g., using cron jobs or Task Scheduler).
- Can be extended to send email alerts for price drops.

## Technologies Used
- **Python** (BeautifulSoup, Requests, CSV, Datetime, smtplib)
- **BeautifulSoup4** for HTML parsing.
- **Requests** for fetching page content.
