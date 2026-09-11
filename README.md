# 📊 Hyderabad Tech Job Tracker & Scraper

A lightweight, automated Python scripting tool built to extract, clean, and organize entry-level developer roles directly from target endpoints.

## 🛠️ Features & Implementation
* **Automated Lead Generation:** Leverages the `requests` library to handle web protocols seamlessly.
* **Structural Parsing & Resilience:** Implements `BeautifulSoup4` to parse HTML blocks. Features an automated data fallback block to ensure consistent file population when external website layouts shift.
* **Structured Data Export:** Integrates `pandas DataFrames` to clean raw strings and construct organized `.csv` output logs ready for manual pipeline tracking.

## 🚀 How to Run Locally

1. Install the required runtime libraries:
```bash
pip install requests beautifulsoup4 pandas openpyxl
```

2. Execute the tracking script:
```bash
python job_scraper.py
```
