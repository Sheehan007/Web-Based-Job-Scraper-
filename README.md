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

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

YouTube Trending Video Analytics in India and the USA

Analyze and visualize YouTube trending video data across regions to uncover global and local content patterns. 

Salient features: 
This project analyzes YouTube trending video datasets to discover:
- Most popular genres and categories
- Sentiment trends in video titles and tags
- Regional content preferences
- Trending durations over time

Merged dataset: 
**YT_combined.xlsx**
- Fields include: `video_id`, `title`, `channel_title`, `publish_time`, `trending_date`, `views`, `likes`, `dislikes`, `comment_count`, `tags`

Analysis Highlights
- Data Cleaning and Standardization across multiple countries
- Sentiment Analysis using NLTK VADER
- SQL aggregation to rank content categories by average views
- Time-series visualization of video trending duration

Key Visualizations: 
- Channel Dominance by Views (Treemap)
- Top KPIs- Total Views, Avg Likes, Avg Dislikes, Total Trending Videos
- Bar Chart- Trending Category vs Time Duration
- Area Chart- Relation between Title_sentiment and Tag_sentiment


Deliverables
- Power BI/Tableau Dashboard (Genres, Sentiments, Trends)
- Final Report with Data Storytelling
- Cleaned and Processed Dataset

Author: Sheehan Mathur
