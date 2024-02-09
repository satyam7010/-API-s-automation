# LinkedIn Data Extraction
This repository contains scripts to extract user data from LinkedIn using both LinkedIn's API and Selenium for browser automation.

LinkedIn API Script
File: linkedin_api.ipynb
Utilizes LinkedIn's API to search for users based on first and last names.
Retrieves data such as name, title, location, and profile URL for the first 10 search results.
Selenium Script
File: linkedin_selenium.ipynb
Uses Selenium for browser automation to search for users on LinkedIn.
Simulates user interaction with the LinkedIn website to extract data for the first 5 search results.
Prerequisites
LinkedIn API access token (for API script)
Selenium WebDriver (ChromeDriver)
Python packages: selenium, csv
Usage
Replace 'ACCESS_TOKEN' with your LinkedIn API access token in linkedin_api.ipynb
Run the scripts and provide the first name and last name of the user when prompted.
Data will be extracted and saved to CSV files.
This README provides a brief overview of the scripts, their functionalities, prerequisites, and usage instructions. Users can refer to this documentation to understand how to use the scripts effectively.
