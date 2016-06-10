# drill_demo_data
Example retail sales and social media scenario for using Apache Drill.

The following files are a part of this (fictional) collection of retail sales from an online retail store.
* customers.all.csv - A database of customer information, including name, address, and other important info, in CSV format
* tweets/tweet_60.json - 60 days of Twitter data relating to the site, in JSON format
* tmp/*.drill - pre-built Drill views of the data
* products/products.csv - a database of products, in CSV format
* orders/month*.log.csv - monthly order records, in CSV format
* nested/clicks/*.json - clickstream data, in JSON format, with embedded JSON in the fields.  The 'campaign' file contains an additional field, 'campaign', which indicates the specific retail campaign that drove that customer to the site.

