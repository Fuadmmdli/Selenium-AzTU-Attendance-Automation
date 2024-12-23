# Selenium Automation for Attendance Tracking

This project provides an automated solution for logging into the Azerbaijani university portal (AZTU) and extracting attendance data from the "Python Programming" course. It uses **Selenium** for browser automation and **BeautifulSoup** for web scraping to retrieve and display attendance information in the terminal.

## Features

- **Automated Login:** Uses Selenium WebDriver to programmatically log in to the AZTU portal.
- **Attendance Tracking:** Retrieves and displays attendance data for the "Python Programming" course.
- **User-friendly Interface:** Prompts for username and password input directly in the terminal.
- **Error Handling:** Provides helpful error messages in case of failed login attempts or issues during data retrieval.
- **Web Scraping:** Utilizes BeautifulSoup to parse HTML and extract relevant attendance information.

## Prerequisites

Before running the project, ensure that you have the following installed on your system:

- Python 3.x
- **ChromeDriver** (for Selenium)

The following Python packages are also required:

- selenium
- beautifulsoup4
- webdriver-manager

You can install the required Python packages via `pip`:

```bash
pip install selenium beautifulsoup4 webdriver-manager

```
setup:
Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/selenium-attendance-tracker.git
cd selenium-attendance-tracker

```
Install the required dependencies

```bash
pip install -r requirements.txt

```

Download the appropriate version of ChromeDriver for your version of Google Chrome:

Visit: https://sites.google.com/chromium.org/driver/
Download the driver that matches your Chrome version.
Ensure that chromedriver is in your system's PATH, or specify its location in the script.

## Usage
Run the script:
```bash
python attendance_tracker.py
```


Enter your username and password when prompted in the terminal.

After a successful login, the script will navigate to the "Python Programming" course page and display attendance information in the terminal.




