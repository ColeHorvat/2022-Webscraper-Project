# ShopHopper Webscrapers

## Lightspeed

### Instructions to Run Scraper

**1.** Go to root folder in terminal and execute `npm install` to install all required packages and libraries.

**2.** Change directory to the lightspeed folder using `cd Lightspeed`. 

**3.** Execute `node index.js` to execute the scraper.

### Feedback Guide

**Mid-Execution**

**URL:** This is the base URL that is currently being parsed.

After `URL:` are all the individual `.ajax` product urls that are scraped from that url.

**Post-Execution**

After execution, a small part of the results will be displayed in the terminal, as well as the amount of items scraped and the execution time in milliseconds.

The full output of the scraper is written in `lightspeedOutputJson.json` in the `Lightspeed` folder.

### Packages and Versions (April 4th, 2022)

cheerio - ^1.0.0-rc.10<br />
node-fetch - ^2.88.2<br />
request: ^2.88.2<br />
request-promise - ^4.2.6<br />
