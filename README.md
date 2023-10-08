# nykaa-web-scrapping
This Python project is a web scraper designed to gather data from the NykaaFashion website, specifically focusing on women's western wear. The scraper collects information about various clothing items, including product names, original prices, discount prices, ratings, and more.

## Overview
The project utilizes the BeautifulSoup library for parsing HTML content and the requests library to fetch web pages.

It extracts valuable information from product pages, such as product names, pricing details, user ratings, and various product specifications.

The scraper is capable of navigating through multiple pages of the NykaaFashion website, allowing you to collect data from a large number of products efficiently.

## How to Use
Clone or download this repository to your local machine.

Make sure you have Python installed along with the required libraries (BeautifulSoup, requests, pandas).

Run the Python script nykaa_scraper.ipynb.

The script will start scraping data from the NykaaFashion website, and the collected data will be saved to a CSV file named NykaaScrap.csv.

You can then analyze, visualize, or use the collected data for your specific needs.

## Customization
You can customize the script to scrape data from other sections or categories of the NykaaFashion website by modifying the URL in the script.

Adjust the sleep duration between requests (currently set to 1 second) to comply with website scraping guidelines.






