# olympics-tokyo-2021-schedule-scrapper
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