# jioscrape
 
A web scraping project, which scrapes the data from JioMart website specifically the vegetables and grocery section.
![jiomart](https://user-images.githubusercontent.com/46810093/208141610-e005bfab-de7b-45e5-8159-9608bd77393e.png)



The folder structure of the project:

![folder tree](https://user-images.githubusercontent.com/46810093/205482778-eeafcfa9-53ce-4bb4-93ba-3f73aa163b73.png)

To start scraping right away type the following commands

```
# enter the directory
cd jioscrape

# To install required dependencies
pip install -r requirements.txt 

# It will start fetching the given url and store the desired results in mart.csv file
scrapy crawl jio -O mart.csv 
```

You can view and modify the source code in /jioscrape/spiders/jiospyder.py
>It won't work for dynamic websites, for that you will need scrapy-splash setup in your scrapy folder

here is a sample output of our project:

![scrape excel](https://user-images.githubusercontent.com/46810093/205484146-05da6d87-a2ae-4494-8c0c-f29c24b73a64.png)
