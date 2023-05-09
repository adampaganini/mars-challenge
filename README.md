# Mars Web Scraping

In this exercise, the Mars news website (https://static.bc-edx.com/data/web/mars_news/index.html) was scraped for data and then extracted for an analysis.


## Part 1: Scrape Titles and Preview Text from Mars News

In the Jupyter Notebook named [part_1_mars_news.ipynb](https://github.com/adampaganini/mars-challenge/blob/main/part_1_mars_news.ipynb) automated browsing with Splinter was used to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html), and then the HTML code was extracted with Beautiful Soup.  The titles and preview text of the news articles were scraped and extracted. The scraped information was stored in a list of dictionaries. 

## Part 2: Scrape and Analyze Mars Weather Data

In the Jupyter Notebook named [part_2_mars_weather.ipynb](https://github.com/adampaganini/mars-challenge/blob/main/part_2_mars_weather.ipynb) automated browsing was used to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html). The HTML table was extracted into a Pandas DataFrame and Beautiful Soup was used to scrape the data, wheich was then used to answer the following questions:
  - How many months exist on Mars? 
  - How many Martian days' worth of data are there? 
  - Which month, on average, has the lowest temperature? The highest? 
  - Which month, on average, has the lowest atmospheric pressure? The highest? 
  - How many terrestrial days exist in a Martian year?

Lastly, the DataFrame was exported into a CSV file called [Mars_DF.csv](https://github.com/adampaganini/mars-challenge/blob/main/Mars_DF.csv).
