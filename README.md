# webscrapingHTML
This is a full web-scraping and data analysis project.
I have learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
There will be two deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyse Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News
1. Inspect the page to identify which elements to scrape (https://static.bc-edx.com/data/web/mars_news/index.html)
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that I scraped
4. Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: 'title' and 'preview'. Store all the dictionaries in a Python list. And finally, print the list in the notebook.

## Part 2: Scrape and Analyse Mars Weather Data
1. Inspect the page to identify which elements to scrape (https://static.bc-edx.com/data/web/mars_facts/temperature.html).
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Use Beautiful Soup to continue sharpening your web scraping skills.
3. Assemble the scraped data into a Pandas DataFrame.
4. Examine the data types that are currently associated with each column. Cast (or convert) the data to the appropriate datetime, int, or float data types.
5. Analyse your dataset by using Pandas functions to answer the questions listing in the notebook.
6. Export the DataFrame to a CSV file.
