# Web Scraping tool
📰 News Headlines Scraper with Text-to-Speech

A Python automation project that uses Selenium WebDriver to scrape the latest top headlines from the Hindustan Times website and converts each headline into an MP3 audio file using Google Text-to-Speech (gTTS).

Features
🌐 Automates Firefox browser using Selenium.
📰 Extracts top news headlines from Hindustan Times.
📄 Saves all headlines to a text file.
🔊 Converts each headline into a separate MP3 audio file.
📁 Automatically creates output directories if they do not exist.
🧹 Closes the browser safely after execution.
Technologies Used
Python
Selenium WebDriver
Firefox (GeckoDriver)
Google Text-to-Speech (gTTS)
Project Workflow
Launch Firefox using GeckoDriver.
Open the Hindustan Times homepage.
Scrape the latest top headlines.
Display headlines in the console.
Save headlines to a text file.
Convert each headline into speech and save it as an MP3 file.
Close the browser and exit the program.
Output
docs/headlines/Headlines.txt – Contains all scraped headlines.
audio/ – Contains MP3 files for each headline.

This project demonstrates the use of web scraping, browser automation, file handling, and text-to-speech conversion in Python, making it a practical example of automation and data extraction.
