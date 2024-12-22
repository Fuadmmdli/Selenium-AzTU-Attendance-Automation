Selenium Automation for Attendance Tracking
This project is an automated solution for logging into the Azerbaijani university portal (AZTU) and extracting attendance data from the "Python Programming" course. It leverages Selenium and BeautifulSoup to navigate the website, log in with user credentials, and scrape attendance information, displaying the results in the terminal.

Features
Automated Login: Uses Selenium WebDriver to programmatically log in to the AZTU portal.
Attendance Tracking: Retrieves and displays attendance data for the "Python Programming" course.
User-friendly Interface: Prompts for username and password input directly in the terminal.
Error Handling: Provides helpful error messages in case of failed login attempts or issues during data retrieval.
Web Scraping: Utilizes BeautifulSoup to parse HTML and extract relevant attendance information.
Prerequisites
Before running the project, ensure that you have the following installed on your system:

Python 3.x
ChromeDriver (for Selenium)
The following Python packages:
selenium
beautifulsoup4
webdriver-manager
You can install the required Python packages via pip:



pip install selenium beautifulsoup4 webdriver-manager
Setup
Clone the repository to your local machine:

bash:

git clone https://github.com/yourusername/selenium-attendance-tracker.git
cd selenium-attendance-tracker
Install the required dependencies:

bash:

pip install -r requirements.txt
Download the appropriate version of ChromeDriver for your version of Google Chrome:

Visit: https://sites.google.com/chromium.org/driver/
Download the driver matching your Chrome version.
Ensure that chromedriver is in your system's PATH or specify its location in the script.
Usage
Run the script:

bash:

python attendance_tracker.py
Enter your username and password when prompted in the terminal.

After successful login, the script will navigate to the "Python Programming" course page and display attendance information in the terminal.

Example Output
yaml

Enter your username: your_username
Enter your password: your_password
Login successful. Proceeding to retrieve attendance...
Date: 2023-12-01, Status: Student attended the class.
Date: 2023-12-02, Status: Student did not attend the class.
Date: 2023-12-05, Status: Student attended the class.
...
Error Handling
If the login fails (incorrect username/password), the script will notify you and prompt for re-entry.
If no attendance data is found, the script will notify you with the message: "No attendance data found."
The script also gracefully handles unexpected errors and provides feedback.
Contributing
Contributions are welcome! If you have any suggestions or improvements, please feel free to submit a pull request or open an issue.

Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit your changes (git commit -m 'Add feature').
Push to your forked repository (git push origin feature-name).
Open a pull request
