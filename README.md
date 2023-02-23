# Mission to Mars
The aim of this study is to scrape data from NASA website to study the planet Mars Weather and News. For this purpose a python code is written to extract the data from the html file of the website.

## Overview of the analysis
The first part of this study is dedicated to data scraping from NASA website to find planet Mars recent news. The website address is https://redplanetscience.com. Our code use automated browsing to visit and look for the titles and preview of the information in the HTML file of the website. These results are then exported to a MongoDb database and is saved as a Json file for further studies.

![Mars_News_Website](Resources/articles_website.PNG)

The next part of this study is extracting wheather data from https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html. Similarly, automated browsing is used to access the website and scrape the data from the table that is provided in the website.

![Mars_News_Website](Resources/Wheather_data_website.PNG)

## Results
