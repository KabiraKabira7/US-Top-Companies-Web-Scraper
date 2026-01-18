# US-Top-Companies-Web-Scraper
Project Overview

This project demonstrates an end-to-end web scraping workflow using Python, focusing on extracting structured business data from unstructured web content. The dataset is sourced from Wikipedia and contains information on the largest U.S. companies by revenue.

The project emphasizes:

Responsible and ethical web scraping practices

Clear, reproducible data pipelines

Transformation of raw HTML into clean, analysis-ready data

🛠️ Tools & Technologies

Python

Requests – for sending HTTP requests

BeautifulSoup (bs4) – for parsing HTML content

Pandas – for data cleaning and tabular structuring

CSV – for exporting data in an analysis-ready format

🔄 Workflow

Data Source Identification

Wikipedia page listing the largest U.S. companies by revenue

Web Request Handling

Fetching HTML content using the requests library

HTML Parsing & Extraction

Parsing tables with BeautifulSoup

Extracting relevant fields (e.g., company name, revenue, industry, rank)

Data Cleaning & Structuring

Converting raw scraped data into a clean Pandas DataFrame

Handling inconsistencies and formatting issues

Data Export

Saving the final dataset as a CSV file ready for analysis or visualization

📂 Project Structure
MySQL_Data_Cleaning_Project/
│
├── scraper.py              # Main web scraping script
├── companies.csv           # Cleaned dataset (output)
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation

📊 Output

A clean CSV dataset containing structured information on major U.S. companies by revenue

Ready for use in:

Exploratory Data Analysis (EDA)

SQL databases

Business intelligence dashboards

Machine learning pipelines

⚖️ Ethical Considerations

Data was scraped from a publicly accessible Wikipedia page

No aggressive requests or bypassing of protections

Intended strictly for educational and analytical purposes

🚀 Possible Extensions

Automate updates using scheduled scripts

Store scraped data in a SQL database

Perform trend analysis and visualizations

Extend scraping to global company rankings

👤 Author

Tim
Data Analyst | Data Scientist (in training)
Passionate about building transparent, reproducible data pipelines and real-world analytics solutions.
