# Job-Scraper-

A Python-based job scraping tool that collects job listings from **Google Jobs**, **Glassdoor**, and **Indeed**, and compiles them into a single Excel file for easy review and analysis. 
Designed to help job seekers, data analysts, and researchers track trends in job markets across roles and cities — all while respecting each site's terms of use.

Salient features: 

1. Scrapes job title, company, location, and job summary
2. Supports multiple cities and job roles
3. Automatically stores and updates data in an Excel file
4. Selenium and BeautifulSoup for browser automation and HTML parsing
5. Complies with ethical scraping practices and site usage policies

Output: 
An Excel file (`job_postings.xlsx`) with the following columns:
1. `Source` (Google Jobs, Glassdoor, Indeed)
2. `Job Title`
3. `Company`
4. `Location`
5. `Summary/Description`
