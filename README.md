# ***📌 Project Overview***
....

This project is a web scraping application designed to extract hotel details from Booking.com. It scrapes hotel information, including name, price, location, ratings, reviews, and links, for any given city and date range, then saves the data as a CSV file in the local directory.

....

## **🎯 Objectives**
 1 Automate Hotel Data Collection – Extract key details from Booking.com efficiently.
 2 Flexible Scraping – Allow users to input a URL and a filename for custom searches.
 3 Data Storage – Save extracted hotel details in a structured CSV format.
 4 Error Handling & Performance – Implement sleep timers and request headers for smooth scraping.
 5 User-Friendly Execution – Provide a seamless command-line experience for users.

 .....
## ***🔧 Technologies & Libraries Used***
 1 Python 3.x
 2 BeautifulSoup4 – For parsing HTML and extracting hotel details.
 3 Requests – For sending HTTP requests to Booking.com.
 4 CSV – To store extracted data in a structured format.
 5 LXML – For fast and efficient HTML parsing.

.....
## ***📂 Features & Workflow***
 1 Users provide a Booking.com search URL and a file name.
 2 The scraper fetches the page and extracts:
 3 Hotel Name 🏨
 4 Price 💰
 5 Location 📍
 6 Rating ⭐
 7 Review Count 📝
 8 Booking Link 🔗
 
......
##The extracted data is saved into a CSV file in the local directory.

The program implements random sleep intervals to mimic human behavior and avoid blocking.
🚀 How to Run the Script
Install required dependencies:
pip install beautifulsoup4 requests lxml
Run the script:
python script.py
Enter the Booking.com URL and file name when prompted.
The data will be scraped and saved as a CSV file.
📌 Example Output (CSV Format)
hotel_name, locality, price, rating, score, review, link
"The Grand Hotel", "Mumbai, India", "₹5000", "4.5", "9.2", "1200 reviews", "https://booking.com/example"
...
⚠️ Disclaimer
This project is intended for educational purposes only. Scraping websites without permission may violate terms of service. Use responsibly and check Booking.com's scraping policies before deploying.

💡 Happy Scraping! 🚀
