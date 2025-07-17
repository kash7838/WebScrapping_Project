# ***📌 Project Overview***

This project is a web scraping application designed to extract hotel details from booking websites. It scrapes hotel information, including name, price, location, ratings, reviews, and links, for any given city and date range, then saves the data as a CSV file in the local directory.

## **🎯 Objectives**
 * Automate Hotel Data Collection – Extract key details from Booking Websites efficiently.
 * Flexible Scraping – Allow users to input a URL and a filename for custom searches.
 * Data Storage – Save extracted hotel details in a structured CSV format.
 * Error Handling & Performance – Implement sleep timers and request headers for smooth scraping.
 * User-Friendly Execution – Provide a seamless command-line experience for users.

## ***🔧 Technologies & Libraries Used***
 * Python 3.x
 * BeautifulSoup4 – For parsing HTML and extracting hotel details.
 * Requests – For sending HTTP requests to Booking Websites.
 * CSV – To store extracted data in a structured format.
 * LXML – For fast and efficient HTML parsing.

## ***📂 Features & Workflow***
 * Users provide a Booking Websites search URL and a file name.
 * The scraper fetches the page and extracts:
 * Hotel Name 🏨
 * Price 💰
 * Location 📍
 * Rating ⭐
 * Review Count 📝
 * Booking Link 🔗
 
## ***The extracted data is saved into a CSV file in the local directory.***
 * The program implements random sleep intervals to mimic human behavior and avoid blocking.
 * 🚀 How to Run the Script
 * Install required dependencies:
 * pip install beautifulsoup4 requests lxml
 * Run the script:
 * python script.py
 * Enter the Booking Websites URL and file name when prompted.
 * The data will be scraped and saved as a CSV file.

## ***📌 Example Output (CSV Format)***
- hotel_name, locality, price, rating, score, review, link
- "The Grand Hotel", "Rajasthan, India", "₹5000", "4.5", "9.2", "1200 reviews", Booking Websites.

# ***⚠️ Disclaimer***
This project is intended for educational purposes only. Scraping websites without permission may violate the terms of service. Use responsibly and check Booking Websites' scraping policies before deploying.

💡 Happy Scraping! 🚀
