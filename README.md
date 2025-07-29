# Automated-Data-Science-Resume-Collector

Description:
This project is designed to automate the process of searching, extracting, and downloading Data Science resumes in PDF format from Google search results. The script focuses on resumes from Pakistan and performs the following key tasks:

Web Scraping: Uses BeautifulSoup and requests to scrape Google search results for PDF resumes matching the query "data science resume Pakistan filetype:pdf".

Link Extraction and Purification: Extracts PDF links from the search results, removes duplicates, and ensures only valid PDF URLs are retained.

Automated Downloading: Utilizes Selenium with Chrome WebDriver to automatically download the PDF files to a specified local directory.

Google Drive Integration: Uploads the downloaded files to a Google Drive folder using the PyDrive library, enabling easy storage and sharing.

The project is ideal for recruiters, researchers, or anyone looking to analyze trends in Data Science resumes from Pakistan. It demonstrates skills in web scraping, automation, and cloud storage integration.

Key Features:

Scrapes multiple pages of Google search results.

Handles duplicate links and invalid URLs.

Automates file downloads and organizes them in a dedicated folder.

Supports batch uploading to Google Drive for centralized storage.

Technologies Used:

Python

BeautifulSoup, Requests, Selenium (for web scraping and automation)

PyDrive (for Google Drive integration)

Regular Expressions (for URL validation)
