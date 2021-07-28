# olympics-tokyo-2021-schedule-scraper
A puppeteer based web scraper for olympics event schedule

#### Usage

````bash
npm install -g olympics-tokyo-2021-schedule-scraper

olympics-2021-scraper <date-to-parse> <output-dir>

# e.g. olympics-2021-scraper 2021-08-01 ./schedules

# NOTE: <date-to-parse> format must be YYYY-MM-DD
# JSON files will be written in specified {output-dir} with the name format 'olympics-schedule-{date-to-parse}.json'
````

**Tip:** You can also use this utility without installing the package

````bash
npx olympics-tokyo-2021-schedule-scraper <date-to-parse> <output-dir>
````


**Disclaimer:**
- This tool uses puppeteer to load web pages from olympics.com to scrape schedule data.
- Make sure to sensibly use this tool if used in automation, and not overwhelm the web servers.
- YOU (user) will be completely responsible for usage of this tool. The developer CAN'T be blamed for the abuse of this tool.