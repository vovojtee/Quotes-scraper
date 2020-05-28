# Easy crawler program that
 scrapes quotes of famous people from website defined in spiderweb/spiders/quotes_spider <br>
 crawls site all (10) pages through <br>
 crawls also author's info <br>
 handles duplicates <br>
 saves (if not already it creates one) to SQLite via SQLAlchemy as nice looking and usable dataset<br>

## how to scrape with default settings:

 install scrapy into /spiderweb/spiders <br>
 
 cd .../spiderweb/spiders <br>
 scrapy crawl quotes
