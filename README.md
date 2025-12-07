# Web Scraper

An educational Python web scraper for collecting machine offers (e.g., CNC) from websites with HTML tables.  
Uses `requests` and `BeautifulSoup` for fetching and parsing data.

---

## Features

- Retrieves multiple pages of offers (pagination).  
- Parses HTML tables and extracts data, stored in **Python dictionaries (`dict`)**, which can be easily saved as **JSON**.  
  Data includes:
  - category, quantity, photo, link, type of machinery, manufacturer, model, price, seller number, offer number.

> **Note:** The repository uses a **sample URL**. Replace it with a website you are authorized to scrape.

---

## Installation

```bash
py -m venv venv
# Windows
.\venv\Scripts\activate
# Linux / macOS
source venv/bin/activate
pip install -r requirements.txt
```
Legal Notice
This project is for educational purposes only.
Do not publish data from websites without the owner's permission and always check the website's Terms of Service before scraping.
