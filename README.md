# Web Scraping Challenge

This project scrapes data about Mars from two websites and analyzes the temperature data

## Instructions

#### Part 1: Scrape Titles and Preview Text from Mars News

Using the Mars news site,
https://static.bc-edx.com/data/web/mars_news/index.html,
and do the following:

- Using Beautiful Soup, extract the titles and preview text of the news articles.
- Store this data in dictonary format and export it to a file.

#### Part 2: Scrape and Analyze Mars Weather Data

5. Analyze your dataset by using Pandas functions to answer the following questions:

Using the Mars temperature data site,
https://static.bc-edx.com/data/web/mars_facts/temperature.html,
do the following:

- Using Beautiful Soup, extract the table data and put it in a pandas dataframe.
- Convert the data into datetime, int, float formats to be able to perform analysis.
- Export the data to a csv file
- Analyse the data as follows:
  - Determine how many months exist on Mars.
  - Determine how many Martian (and not Earth) days worth of data exist in the scraped dataset.
  - Use a bar chart to determine the coldest and warmest months.
  - Use a bar chart to determine which months have the lowest and the highest atmospheric pressure.
  - Using a plot of all the minimum termperature over time, estimate how many terrestrial (Earth) days exist in a Martian year.
  - Determine the actual number of terrestrial (Earth) days in a Martian year.

## Results

| Minimum Temperature by Month                          | Atmospheric Pressure by Month                         |
| ----------------------------------------------------- | ----------------------------------------------------- |
| <img src="image-1.png" alt="Your Image" width="300"/> | <img src="image-2.png" alt="Your Image" width="300"/> |

| Minimum Temperature Over Time                         | Earth Day Calculation                                 |
| ----------------------------------------------------- | ----------------------------------------------------- |
| <img src="image-3.png" alt="Your Image" width="300"/> | <img src="image-4.png" alt="Your Image" width="300"/> |

### Tools

- Python,JyupterNotebooks

- Python Modules
  - matplotlib
  - pandas
  - json
  - splinter
  - bs4 , BeautifulSoup4

#### Notes

exports folder contains the files exported a part of the solutions

- mars_news_all_text_elements.json contains the optional export from Part 1 with json data for the text data of the news articles.
- mars_weather.csv contains the dataframe export of the table scraped in Part 2
