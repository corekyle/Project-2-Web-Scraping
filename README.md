# Project-2-Web-Scraping

## This project builds an end-to-end web scraping and exploratory data analysis pipeline in Python. Using `requests` and `BeautifulSoup`, the pipeline scrapes five pages (250 top-selling titles) from the VGChartz Game Database, cleans the scraped records in `pandas`, and answers four data science questions programmatically and visually with `seaborn`:
1. Which top 10 publishers generate the highest combined global sales in the top 250, and what share does the #1 publisher hold?
2. How do North America, PAL/Europe, and Japan sales shares differ across the top 5 consoles?
3. Is there a positive correlation between critic scores and global unit sales among top-250 titles?
4. Which consoles achieve the highest average sales per hit, and which release decade produced the most top-250 games?

## Repository Files
* 'Project2_Part2_Web_Scraped_Data_Analysis_and_Visualizations-checkpoint.ipynb' Jupyter Notebook with web scraping, data cleaning, analysis, plots, and conslusions.
* 'vgchartz_raw_top250.csv' Raw scraped dataset generated when running the notebook.
* 'vgchartz_clean_top_250.csv' Cleaned dataset with numeric sales (in millions), parsed release years/decades, and standardized columns.
