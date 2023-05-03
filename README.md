# Project Title - Web Scraping and Mars Data Analysis

## Project Description

### Part 1: Scrape Titles and Preview Text from Mars News
Web scraping of a Mars news website to gather news article data.

### Requirements

*part_1_mars_news.ipynb*

*https://static.bc-edx.com/data/web/mars_news/index.html*

### Analysis

**Mars News Site Analysis**

1. Use automated browsing to visit the Mars news site & inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures.
4. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file.

### Part 2: Scrape and Analyse Mars Weather Data
Web scraping and analysis of a Mars weather data site.

### Requirements

*part_2_mars_weather.ipynb*

*https://static.bc-edx.com/data/web/mars_facts/temperature.html*

### Analysis

**Mars Weather Data Analysis**

1. Use automated browsing to visit the Mars weather data site & inspect the page to identify which elements to scrape.
2. Use Beautiful Soup to scrape the data in the HTML table.
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
4.  Examine the data types that are currently associated with each column. If necessary, convert the data to the appropriate datetime, int, or float data types.
5. Analyse your dataset by using Pandas functions to answer the following questions:

        How many months exist on Mars?
        How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        Find the average minimum daily temperature for all of the months.
        Plot the results as a bar chart.

        Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
        Find the average daily atmospheric pressure of all the months.
        Plot the results as a bar chart.

        About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
        Consider how many days elapse on Earth in the time that Mars circles the Sun once.
        Visually estimate the result by plotting the daily minimum temperature.

 6. Export the DataFrame to a CSV file.  

### Dependencies

* Python
* Pandas
* Splinter
* Beautiful Soup
* Json
* Matplotlib

### References
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars News website in November 2022. Images are used according to the JPL Image Use Policy, courtesy NASA/JPL-Caltech.
