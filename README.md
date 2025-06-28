Craigslist Rental Data Scraping and Analysis

Project Overview

This project scrapes and analyzes rental listings from Craigslist, focusing on cities like Davis and Berkeley in California. It extracts relevant data such as rental price, number of bedrooms, and the presence of amenities (e.g., washer/dryer, parking), and visualizes differences between regions.

Key Features

- Webscraping: Automates a browser session to dynamically extract rental listings.
- Data Cleaning: Transforms unstructured Craigslist text into clean, structured data.
- Exploratory Data Analysis (EDA):
  - Rent distribution by city and bedroom count
  - Effect of amenities on price
  - Rent per bedroom comparisons

Install All Necessary Dependencies

```r
install.packages(c("RSelenium", "rvest", "xml2", "dplyr", "ggplot2", "tidyr", "stringr"))
