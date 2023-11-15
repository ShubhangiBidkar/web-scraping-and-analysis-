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

Minimum Temperature by Month 

![image-1](https://github.com/ShubhangiBidkar/web-scraping-and-analysis-/assets/38162670/d7c28bba-8959-468a-b92c-5c562b78baca) 

Atmospheric Pressure by Month 

![image](https://github.com/ShubhangiBidkar/web-scraping-and-analysis-/assets/38162670/f5683673-9fa2-4d27-80e6-bc1b5f600394)

Minimum Temperature Over Time   

![image-3](https://github.com/ShubhangiBidkar/web-scraping-and-analysis-/assets/38162670/f70fdd38-7303-43b1-b2ea-c3776dfe8dd7)

Earth Day Calculation 
 
![image-4](https://github.com/ShubhangiBidkar/web-scraping-and-analysis-/assets/38162670/c23173b6-74b1-4fb8-86b7-cddf6cbf0755)


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
