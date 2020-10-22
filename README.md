# Ecommerce Spiders
The repository consists of ecommerece spiders based on python **scrapy** framework.

## 1- Surfstitch
Surfstitch is one of the Australia's largest fashion retailers with an emphasis on surfing culture.

surfstitch_spider.py is a spider for surfstitch website which extracts data for men's, women's and kid's clothing.

#### Usage
Run the spider with the following command: scrapy crawl SPIDER_NAME -o output.json

where:

1. **SPIDER_NAME:** is the name of spider mentioned in spider code.

2. **-o output.json:** file containing all scraped items, serialized in JSON.
 
