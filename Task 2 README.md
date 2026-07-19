# Web Scraper for News Headlines

## Overview

The **Web Scraper for News Headlines** is a Python-based application that automatically extracts the latest news headlines and their corresponding article URLs from the **BBC News** website. The project uses the **Requests** library to retrieve webpage content and **BeautifulSoup** to parse the HTML structure and extract relevant information.

The extracted data is displayed in a structured format and saved in both **CSV** and **JSON** files for future reference and analysis.

---

## Features

* Scrapes the latest news headlines from BBC News
* Extracts corresponding article URLs
* Removes duplicate headlines
* Displays extracted data in a structured format
* Saves data in CSV format
* Saves data in JSON format
* Implements exception handling for reliable execution
* Compatible with Google Colab

---

## Technologies Used

* Python 3
* Google Colab

### Python Libraries

* requests
* beautifulsoup4
* pandas
* json

---

## Project Workflow

1. Import the required Python libraries.
2. Send an HTTP request to the BBC News website.
3. Retrieve the webpage HTML content.
4. Parse the HTML using BeautifulSoup.
5. Extract news headlines and article URLs.
6. Remove duplicate entries.
7. Display the extracted information.
8. Save the data in CSV format.
9. Save the data in JSON format.

---

## Project Structure

```text
Web_Scraper/
│
├── web_scraper.ipynb
├── headlines.csv
├── headlines.json
├── README.md
└── requirements.txt
```

---

## Output Files

After successful execution, the project generates:

* **headlines.csv** – Stores extracted headlines and article URLs in tabular format.
* **headlines.json** – Stores the same information in JSON format.

Example CSV:

| S.No | Headline         | Article URL                  |
| ---- | ---------------- | ---------------------------- |
| 1    | Example Headline | https://www.bbc.com/news/... |
| 2    | Another Headline | https://www.bbc.com/news/... |

---

## Applications

* News aggregation
* Data collection
* Market research
* Content analysis
* Data science projects
* Python web scraping practice

---

## Advantages

* Automates data collection from websites.
* Reduces manual effort.
* Stores data in multiple formats.
* Easy to understand and modify.
* Beginner-friendly project for learning web scraping.
* Demonstrates practical use of Requests and BeautifulSoup.

---

## Future Enhancements

* Support multiple news websites.
* Extract publication date and author information.
* Download article summaries.
* Store data in SQL or MongoDB databases.
* Add keyword-based filtering.
* Develop a Flask-based web interface.
* Schedule automatic scraping at regular intervals.

---

## Conclusion

The **Web Scraper for News Headlines** is a simple and efficient Python application that demonstrates web scraping using the Requests and BeautifulSoup libraries. It successfully extracts news headlines and article URLs, removes duplicate entries, and stores the information in CSV and JSON formats. The project provides practical experience in HTML parsing, data extraction, and structured data storage, making it an excellent beginner-friendly Python automation project.

---

## Author

**M. Ayshwarya**
Aeronautical Engineering Graduate
Python Development Internship Project
