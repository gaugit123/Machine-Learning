# Book Data Scraper

## Overview

This project scrapes book information from the Books To Scrape website using Python, Requests, and BeautifulSoup.

The scraper collects:

- Book Title
- Price
- Rating
- Genre
- Description

The extracted data is stored in a Pandas DataFrame and exported as a CSV file for further analysis.

---

## Dataset Source

Website used:

https://books.toscrape.com/

This website is specifically designed for practicing web scraping.

---

## Features

✔ Scrapes multiple catalogue pages

✔ Extracts book information

✔ Visits individual book pages

✔ Retrieves genre and description

✔ Stores data in a structured format

✔ Exports results to CSV

---

## Technologies Used

- Python
- Requests
- BeautifulSoup4
- Pandas

---

## Workflow

1. Send HTTP requests to catalogue pages.
2. Parse HTML using BeautifulSoup.
3. Extract:
   - Title
   - Rating
   - Price
4. Visit each book page.
5. Extract:
   - Genre
   - Description
6. Create DataFrame.
7. Export dataset as CSV.

---

## Skills Demonstrated

- Web Scraping
- HTML Parsing
- Data Collection
- Data Cleaning
- Data Analysis
- Python Programming
- BeautifulSoup
- Requests Library

---

## Author

Gaurav Singh
