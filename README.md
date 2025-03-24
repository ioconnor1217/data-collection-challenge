# web-scraping-challenge
This challenge was split into two separate parts. The first part is called "mars_news_scrape", and the second part is called "mars_weather_analysis". 

## Part One
In this part of the challenge I used [Beautiful Soup](https://pypi.org/project/beautifulsoup4/) along with [splinter](https://pypi.org/project/pytest-splinter/) to find a website and scrape the HTML elements. The website I scraped is the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html), which is a site with articles pertaining to the planet Mars. I was able to find all the articles on the first page. Then I extracted all the titles and the article previews while simultaneously storing them in a list of dictionaries. 

## Part Two
I once again used [Beautiful Soup](https://pypi.org/project/beautifulsoup4/) along with [splinter](https://pypi.org/project/pytest-splinter/) to scrape Mars temperature data from [here](https://static.bc-edx.com/data/web/mars_facts/temperature.html). I looped through the table elements and pulled each row into a list of lists. Then, I created a [pandas](https://pypi.org/project/pandas/) DataFrame with that. With the DataFrame complete, I was able to analyze the average minimum temperature and the average pressure on Mars per month. I then plotted that data into charts. Lastly, I plotted all the minimum temperature data over time to calculate a rough estimate of a Martian year. 
