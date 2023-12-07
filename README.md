# ESG Impact Analysis

## 1. Overview

Nowadays, ESG (Environmental, Social, and Governance) has garnered widespread popularity, addressing concerns that span from environmental conservation to financial investment. By scrutinizing a company's environmental footprint, governance practices, and societal impact, stakeholders gain a profound understanding of its resilience and vulnerabilities. Through an exploration of our dataset, which exclusively features companies from the renowned S&P 500 index, the project aims to investigate the various factors influencing the ESG ratings of companies and seek to gain insights into the relationships and patterns that emerge within the ESG landscape.

## 2. How to run

### 2.1 Setup

Ensure some important python packages are installed on your system.

> pandas, numpy, re, requests, BeautifulSoup, yfinance, usaddress, plotly.graph_objects, seaborn, matplotlib.pyplot, tabulate, plotly.express

### 2.2 Running the Code

Those four python could run directly if system environment is done. Should be careful when setting the file path.



## 3. How it works

### 3.1 get_data.ipynb

This program aims to collect data for following analysis, and stores the data into '../data/raw'.

### 3.2 clean_data.ipynb

Used to clean data and store cleaned data into '../data/processed'.

### 3.3 run_analysis.ipynb

Used to analysis data collected above

### 3.4 visualize_results.ipynb

Used to visualize results.The result images are downloaded and stored under '../data/results'.
