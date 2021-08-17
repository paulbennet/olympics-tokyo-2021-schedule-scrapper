# olympics-tokyo-2021-schedule-scraper
A puppeteer based web scraper for olympics event schedule

#### Usage

````bash
npm install -g olympics-tokyo-2021-schedule-scraper
````

````bash
#Options:
#  -o --output-dir <output-dir>  Output directory path
#  -d --date <date-to-parse>     Date to fetch game schedules
#  -m --medals                   Fetch medal standings

# 1. [SCRAPE] Fetch event schedules
olympics-2021-scraper --date=<date-to-parse> --output-dir=<output-dir>

# e.g. olympics-2021-scraper --date=2021-08-01 --output-dir=./schedules

# 2. [SCRAPE] Fetch medal standings
olympics-2021-scraper --medals --output-dir=<output-dir>

# NOTE:
# 1. <date-to-parse> format must be YYYY-MM-DD
# 2. JSON files will be written in specified {output-dir} with the name format 'olympics-schedule-{date-to-parse}.json'
````

**Tip:** You can also use this utility without installing the package

````bash
# Fetch event schedules
npx olympics-tokyo-2021-schedule-scraper --date=<date-to-parse> --output-dir=<output-dir>

# Fetch medal standings
npx olympics-tokyo-2021-schedule-scraper --date=<date-to-parse> --output-dir=<output-dir>
````


**Disclaimer:**
- This tool uses puppeteer to load web pages from olympics.com to scrape schedule data.
- Make sure to sensibly use this tool if used in automation, and not overwhelm the web servers.
- YOU (user) will be completely responsible for usage of this tool. The developer CAN'T be blamed for the abuse of this tool.