# US Dataset Crawler & Database Management System

## Overview
A complete data pipeline project developed to automate the extraction, structuring, and storage of web-based datasets. This system crawls American dataset webpages, structures the raw data into Excel spreadsheets, and seeds a custom-built relational database. It also includes an integrated user management system for secure data access.

## Key Features
*   **Automated Web Crawling:** Efficiently navigates and extracts target data from dataset web pages.
*   **Data Transformation:** Cleans and exports the scraped web data directly into `.xlsx` formats for easy viewing and auditing.
*   **Custom Relational Database:** A fully normalized database designed from scratch to house the extracted datasets.
*   **User Access Controls:** Includes a dedicated user schema to manage authentication and read/write permissions for the database.

## Tech Stack
*   **Language:** Python (BeautifulSoup, Pandas) / [Change if needed]
*   **Database:** SQL (MySQL / PostgreSQL) / [Change if needed]
*   **Tools:** Excel, Git

## Setup and Installation

1. **Clone the repository:**
```bash
   git clone [https://github.com/yourusername/dataset-crawler-db.git](https://github.com/yourusername/dataset-crawler-db.git)
   cd dataset-crawler-db
