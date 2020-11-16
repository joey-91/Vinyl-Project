## Predicting Vinyl Record Prices

This project aims to build the best possible model for predicting record prices, given all the potential predictors I could find on Discogs.com

## Motivation

This was the final project of my General Assembly Data Science Immersive course. I wanted to build something a little more interesting than the datasets available on Kaggle, and a tool I could potentially use for myself.

## Methodology

### 1 - Scraping the data.
This was the most labour intensive part of the project. Using a combination of Selenium, Beautiful Soup and Regex (for the really stubborn problems), to extract and clean the data from it's HTML format to a structured table. Firstly scraping the ~30,000 most recent records from the search pages, with settings configured to view 250 records per page. Within the scraped HTML, were the HTTP links for each record, what you'd click on to take you to the next page. Within these pages were further datapoints on each record. One careful consideration I had to make while iterating through record pages was setting a sleep time, to avoid their servers blocking my IP address. Anything within a certain time frame considered to be a bot. 
  
###



