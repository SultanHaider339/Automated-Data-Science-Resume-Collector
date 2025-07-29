# Automated Data Science Resume Collector

## Description  
This project automates the process of searching, extracting, and downloading Data Science resumes in PDF format from Google search results. The script focuses on resumes from Pakistan and performs key web scraping and file management tasks.

## Key Features
- **Web Scraping**: Uses `BeautifulSoup` and `requests` to scrape Google for PDFs matching `" data science resume Pakistan filetype: pdf"`
- **Link Management**:
  - Extracts PDF links from search results
  - Removes duplicate entries
  - Validates URLs using regex
- **Automated Downloading**: Uses Selenium with Chrome WebDriver to download PDFs to local storage
- **Cloud Integration**: Uploads files to Google Drive via PyDrive for centralized access

## Ideal Use Cases
- Recruiters analyzing resume trends
- Job market researchers
- Data science competency assessments

## Technology Stack
| Category        | Tools/Libraries               |
|-----------------|-------------------------------|
| Core Language   | Python                        |
| Web Scraping    | BeautifulSoup, Requests       |
| Browser Automation | Selenium                    |
| Cloud Storage   | PyDrive (Google Drive API)    |
| URL Validation  | Regular Expressions           |

## Workflow
1. Google search result scraping
2. PDF link extraction and purification
3. Automated file downloading
4. Batch upload to Google Drive

> **Note**: Demonstrates practical skills in web scraping, automation, and cloud integration.
