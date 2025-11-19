# Web-Scraping-Exploratory-Data-Analysis-on-Second-Hand-Bikes-Droom-

## Objective
This project focuses on scraping second-hand bike listings from the Droom platform and performing detailed Exploratory Data Analysis (EDA) to understand pricing trends, brand performance, and market patterns. The goal is to automate data collection, clean the dataset, visualize key insights, and identify major factors influencing resale bike prices

## Problem Statement
The second-hand bike market in India is large but lacks transparent and consistent pricing. Buyers and sellers often struggle to compare bikes across brands, years, mileage, and cities. Online listings contain valuable information, but the data is unstructured, scattered, and difficult to analyze without automation.

## Features
## Web Scraping
Extracted bike details including:
=> Brand, Model, Price, Location, Engine Capacity, Model Year, Fuel Type, Road Trip (KM Driven)

Scraped data from four major Indian cities:
=> Hyderabad, Bangalore, Chennai, Mumbai
Automated scraping using Python (Requests + BeautifulSoup)

## Data Cleaning & Processing
- Removed irrelevant columns, duplicates, and inconsistent records
- Optimized memory usage for large scraped datasets
- Standardized numeric & categorical variables
- Prepared final cleaned dataset for EDA

## Exploratory Data Analysis (EDA)
- Univariate and Bivariate analysis
- Visualizations using Matplotlib & Seaborn
### Key insights derived:
- Kawasaki had the highest bike listings
- Mumbai is the largest market among the four cities
- Most bikes listed were from 2018–2020
- Weak correlation between bike price and distance driven
- City-wise price differences based on demand & brand value

# Project Files
- <a href="https://github.com/Shareef1827/Web-Scraping-Exploratory-Data-Analysis-on-Second-Hand-Bikes-Droom-/blob/main/EDA_Project.ipynb">Python Code File </a>
- <a href="https://github.com/Shareef1827/Web-Scraping-Exploratory-Data-Analysis-on-Second-Hand-Bikes-Droom-/blob/main/Final_Dataset_CSV.csv"> Uncleaned Dataset </a>

