
📌 Quotes Web Scraper – Python Web Scraping Project

📖 Project Overview

This project is a simple and efficient web scraping tool built in Python to extract quotes and their authors from a quotes website.
It uses the Requests library to fetch web pages and BeautifulSoup to parse the HTML content.

The scraped data is cleaned, structured, and stored in a CSV file for further analysis or NLP projects.

🚀 Features
Scrapes quotes and their respective authors
Extracts data from multiple pages
Stores data in a clean CSV file
Lightweight and beginner-friendly
Follows ethical scraping guidelines

🛠️ Tech Stack
- Python 3.x
- Requests
- BeautifulSoup (bs4)
- Pandas (optional for saving CSV)

### Requirements
```
requests
beautifulsoup4
pandas
matplotlib
```

### Installation
1. **Clone this repository:**
```bash
git clone https://github.com/yourusername/quotes-webscraper.git
cd quotes-webscraper
```

2. **Install required packages:**
```bash
pip install requests beautifulsoup4 pandas matplotlib
```

### Usage
1. **Run the scraper script:**
```bash
python scraper.py
```

### Code Structure
- The base URL of the quotes website
- Logic to send HTTP requests
- Fetching the HTML for each page (if pagination exists)
- Passing the raw HTML to the parser module
- Collecting scraped data (quotes + authors)
- Saving the final output to CSV using pandas

Concepts included:
requests.get(), handling responses, calling parser functions, returning structured data.

### HTML Extraction Logic

Creates a BeautifulSoup object to read the webpage, then loops through each <div class="quote"> block to pull quote text and author names from the relevant tags.
After processing, it returns clean Python lists containing all extracted quotes and authors.



🧠 Concepts Used
HTML parsing
CSS selectors
Looping through pages
Data extraction and cleaning
Exporting scraped data


⚠️ Ethical Web Scraping Reminder

This project is for educational purposes only.
Please ensure you:
Check website terms before scraping
Avoid sending too many requests quickly
Use the data responsibly


