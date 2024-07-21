## 1_DynamicWebsiteParsing
**Description:** Parsing data from a [dynamic website](https://auto.ria.com/)
**Tools:** Python, Selenium, BeautifulSoup

## 2_ImagePDFSaving
**Description:** Saving images and converting to PDF using the img2pdf library.
**Tools:** Python, Requests, img2pdf

## 3_HotelListingsSite
**Description:** Scraping hotel data from a [website](http://tury.ru/)
**Tools:** Python, BeautifulSoup, Requests

## 4_JSON_CSVProcessing
**Description:** Saving pages to disk, parsing JSON and CSV data.
**Tools:** Python, Requests, JSON, CSV

## 5_TireListingsSite_JSON
**Description:** Extracting and parsing complex JSON structures from a [tire listings site](https://roscarservis.ru/catalog/legkovye/?form_id=catalog_filter_form&filter_mode=params&sort=asc&filter_type=tires&arCatalogFilter_458_1500340406=Y&set_filter=Y).
**Tools:** Python, Requests, JSON

## 6_CSV_JSON_Usage
**Description:** Scraping a site and utilizing CSV and JSON modules for [data storage](https://www.labirint.ru/genres/2308/?display=table&page=1)
**Tools:** Python, Requests, JSON, CSV

## 7_AsyncWebScraping
**Description:** Scraping a book [listings site using asynchronous programming](https://www.labirint.ru/genres/2308/?display=table&page=1)
**Tools:** Python, aiohttp, asyncio, BeautifulSoup

## 8_ExceptionHandling
**Description:** Demonstrating the use of try-except blocks in web scraping.
**Tools:** Python, BeautifulSoup, Requests

## 9_JSON_ImageDownloading
**Description:** Downloading JSON data and images, organizing them in [separate folders](https://www.landingfolio.com/)
**Tools:** Python, Requests, JSON, os

## 10_CategoryScraping_AIOHTTP_ASYNCIO
**Description:** Scraping categories from Ozon using AIOHTTP and ASYNCIO.
**Tools:** Python, aiohttp, asyncio, BeautifulSoup

## 11_BankWebsiteScraping
**Description:** Collecting card data from all pages and saving results in a CSV file with headers https://reprobank.ru/bank-donorov/katalog-donorov-spermi/ 
**Tools:** Python, BeautifulSoup, Requests, CSV

## 12_AudiobookListingsSite_v1
## 12_AudiobookListingsSite_v2
**Description:** Scraping over 2k pages and 60k [audiobook cards, saving data in JSON format](https://knigorai.com/)
**Tools:** Python, BeautifulSoup, Requests, JSON

## 13_ProxyListingsSite
**Description:** Parsing proxy data from a website https://hidemy.name/ru/proxy-list/ 
**Tools:** Python, BeautifulSoup, Requests

## 14_TurkishHotelsListings
**Description:** Scraping Turkish hotel listings https://turk.estate/ 
**Tools:** Python, BeautifulSoup, Requests

Parser for Turk.estate

This parser collects information about real estate listings from the Turk.estate website. The data is saved in a .csv file with a semicolon separator.

Columns:

- Site
- Name
- Price
- City
- District
- Region
- Type
- Rooms
- Living Space
- Distance to Sea
- Distance to City Center
- Location
- Features
- Indoor Facilities
- Outdoor Features
- Property Description
- Date
- URL

### Libraries Used:
- random
- fake_useragent
- bs4
- datetime
- requests
- os

Installation Instructions:

To install the necessary libraries, open the command line (Win+R -> type "cmd" -> press Enter) and run:

sh

_(copy code)_
pip install beautifulsoup4
pip install fake-useragent
pip install lxml
pip install pysocks

Proxy Configuration:

Fill the file proxies_IPv4_socks5.txt with your proxies following the example format. If your proxy does not require a username and password, use the format ip:port.

Free proxies can be found here: Free Proxy List

Errors related to proxies are logged in reports.txt.

## 15_TelegramChannelScrapper
**Description:** Collecting all messages from Telegram channels, saving each message in a separate folder along with metadata and media.
**Tools:** Python, Telethon, os, JSON, logging

## 16_StartupProfiles_Slush
**Description:** Collecting data using Selenium to simulate user [interactions due to partial data loading](https://platform.slush.org)
**Tools:** Python, Selenium

### Contacts:
- Telegram: ***@ybezginova***
- Email: ***ybezginova2022@gmail.com***
