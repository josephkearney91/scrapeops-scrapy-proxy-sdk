ScrapeOps middleware for Scrapy (http://scrapy.org/)
=======================================================

Processes Scrapy requests using ScapeOps


Install
--------

Checkout the source and run

    python setup.py install


settings.py
-----------

SCRAPEOPS_API_KEY = 'YOUR_API_KEY'
SCRAPEOPS_PROXY_ENABLED = True

DOWNLOADER_MIDDLEWARES = {
    'YOUR_PROJECT_NAME.middlewares.ScrapeOpsScrapyProxySdk': 725,
}

NOTE: Remember to swap the YOUR_PROJECT_NAME for the name of your project (BOT_NAME in your settings.py file)