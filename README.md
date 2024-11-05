Mars News and Weather Data Scraping Project
This project scrapes data from two Mars-related websites using automated browsing with Splinter and BeautifulSoup. It collects information on Mars news articles and Curiosity rover weather data, storing the data for further analysis. The project involves two main deliverables: scraping Mars news titles and previews, and collecting and analyzing Mars weather data.

Table of Contents
Project Overview
Technologies Used
Deliverables
Setup Instructions
Usage
Analysis
Results
Project Overview
This project is divided into two main sections:

Deliverable 1: Scrapes Mars news article titles and preview text from a Mars news website.
Deliverable 2: Scrapes Mars weather data, including temperature and atmospheric pressure, from a Mars temperature data site and performs basic analysis on the collected data.
Technologies Used
Python
BeautifulSoup
Splinter
Pandas
Matplotlib
Deliverables
Deliverable 1: Scrape Titles and Preview Text from Mars News
Step 1: Using Splinter, navigate to the Mars news website.
Step 2: Scrape the titles and preview text of news articles using BeautifulSoup.
Step 3: Store each title and preview text pair in a dictionary with keys title and preview, then add each dictionary to a list. Print the list to confirm success.
Deliverable 2: Scrape and Analyze Mars Weather Data
Step 1: Use Splinter to navigate to the Mars temperature data website.
Step 2: Scrape the temperature and atmospheric pressure data from the table using BeautifulSoup.
Step 3: Assemble the scraped data into a Pandas DataFrame.
Step 4: Convert data types (date, integers, and floats) to prepare for analysis.
Step 5: Analyze the data to answer key questions, such as:
Number of months and sols (Martian days) of data.
Average minimum temperature and atmospheric pressure by month.
Coldest and warmest months based on average minimum temperature.
Months with the highest and lowest atmospheric pressure.
Step 6: Save the data to a CSV file.
Setup Instructions
Install dependencies:

Ensure you have Python installed along with the necessary libraries:
bash
Copy code
pip install splinter beautifulsoup4 pandas matplotlib
Set up Splinter:

Install and configure the Chrome browser driver for Splinter.
Run the Code:

Run the script to scrape and analyze the data. Be sure to check the URLs in the script for connectivity.
Usage
Run the Script: Run each deliverable script in sequence:

Deliverable 1: Scrapes Mars news titles and previews.
Deliverable 2: Scrapes weather data and performs analysis.
Output: The script will output the scraped data, analysis results, and save the Mars weather data to a CSV file (mars_weather_data.csv).

Analysis
For Deliverable 2, you will use the Pandas library to analyze the Mars weather data:

Determine the coldest and warmest months on Mars by finding the average minimum temperature for each month.
Determine which months have the lowest and highest atmospheric pressure.
Estimate the length of a Martian year based on temperature cycles.
Results
Sample Results
Number of Months on Mars: Shows how many unique months are represented in the data.
Number of Martian Days: Displays the total sols for which data is available.
Temperature Analysis: A bar chart shows the coldest and warmest months based on average minimum temperature.
Pressure Analysis: A bar chart indicates the months with the highest and lowest atmospheric pressure.
Martian Year Length: A plot shows daily minimum temperature trends over time to estimate a Martian year.
License
This project is for educational purposes and follows the guidelines for scraping and analyzing publicly available Mars data.

This README provides instructions to set up, use, and analyze the results of the Mars data scraping project. Make sure to follow the setup steps carefully, especially for installing and configuring dependencies.
