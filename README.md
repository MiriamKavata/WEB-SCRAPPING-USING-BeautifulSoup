# WEB-SCRAPPING-USING-BeautifulSoup
This project demonstrates how I successfully scrapped data from the Coin Market Cap website. Specifically, I collected informmationt about the ongoing,upcoming and ended cryptocurrency projects listed on the platform. I achieved this by leaveraging web scrapping techniques, with a particular focus on using the BeautifulSoup library in python.
In the coin_market_cap_scraper.ipynb notebook, I have documented the step-by-step process of scraping data from Coin Market Cap. Here's a breakdown of the key elements:
# 1. Webscrapping Using BeautifulSoup:
I used Beautiful Soup to parse the HTML structure of the Coin Market Cap website, allowing me to extract specific data elements.
The code demonstrates how I navigated through the website, identified relevant tags and classes, and extracted information such as project names, stage, start and end date as well as goals.
# 2. Using List and Loops:
Since Coin Market Cap lists multiple projects, I employed Python lists to store the scraped data. A loop was used to iterate through project entries on the website, systematically extracting information and appending it to the respective lists.
# 3. Data Export to CSV:
To ensure the data is easily shareable and analyzable, I utilized the Pandas library to create CSV files. The scraped data is organized into data frames, and then exported to CSV files for further analysis or presentation.
# Multiple Projects
It's important to note that Coin Market Cap hosts numerous cryptocurrency projects. To efficiently handle this, I designed the code to work seamlessly with multiple projects. The combination of empty lists and loops enabled me to gather data from all the projects listed on the website.
# Usage
Feel free to explore the Jupyter Notebook (coin_market_cap_scraper.ipynb) to see the code in action. You can use this code as a reference for your own web scraping projects or as a starting point for analyzing data from Coin Market Cap.
