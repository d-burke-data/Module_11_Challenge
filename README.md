# Module_11_Challenge : *Data Collection Challenge*

This repository contains Jupyter Notebooks for scraping web data regarding Mars. The first notebook, **part_1_mars_news.ipynb**, scrapes the page https://static.bc-edx.com/data/web/mars_news/index.html for news about Mars and writes it to the JSON file, **mars_news.json**. The second notebook, **part_2_mars_weather.ipynb**, scrapes the table on page https://static.bc-edx.com/data/web/mars_facts/temperature.html for weather data collected by the Mars Curiosity rover, performs analyses regarding temperature, atmospheric pressure, and length of year, then writes the data to the CSV file **mars_weather.csv**.  

The web scraping is performed using the Splinter and BeautifulSoup libraries.
  
### Relevant Files

Python (Jupyter Notebooks):
+ part_1_mars_news.ipynb *(Jupyter Notebook for web scraping Mars news headlines)*
+ part_2_mars_weather.ipynb *(Jupyter Notebook for web scraping and analyzing Mars weather data)*

Output:
+ Output/mars_news.json *(JSON file containing news article data in pairs of title and summary)*
+ Output/mars_weather.csv *(CSV file containing Mars weather data collected from the web)*

Data Sources:  
https://static.bc-edx.com/data/web/mars_news/index.html  
https://static.bc-edx.com/data/web/mars_facts/temperature.html
