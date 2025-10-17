# Web Scraping tool

**WebScraperPy** - A Simple Web Scraping Tool Using Python

WebScraperPy is a lightweight and beginner-friendly web scraping tool written in Python. It allows users to extract data from websites using simple and clean code, powered by requests, BeautifulSoup, and optionally pandas for data export.

**Features**

Fetches HTML content from any public URL

Parses HTML using BeautifulSoup

Extracts data like titles, headings, links, tables, and more

Exports scraped data to CSV or JSON

Easy to customize for different websites

**How It Works**

**1 Send HTTP Request**

The tool uses the requests library to send an HTTP GET request to the target URL and fetch the HTML content.

**2 Parse HTML Content**

The response is passed into BeautifulSoup, which parses the HTML and creates a navigable tree structure.

**3 Extract Targeted Data**

Specific HTML elements (e.g.<h1>, <a>, <div>, table rows) are selected using tags, classes, or IDs to extract data.

**4 Export Data (Optional)**

The extracted data can be saved in structured formats like .csv or .json for analysis or storage.
