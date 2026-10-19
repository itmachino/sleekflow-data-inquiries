# Customer Service Report (Machino)

A single web page (`index.html`) that shows what customers ask Machino's WhatsApp bot and customer service team: totals, bot vs human handling, and charts over a date range.

**Live page:** https://itmachino.github.io/sleekflow-data-inquiries/

Pick a date range with the page's date boxes, or put it in the link: `?from=YYYY-MM-DD&to=YYYY-MM-DD`.

## How it works

- The page reads data that is published from Machino's Google Sheet (the ENQUIRY LOG tab) and draws the charts in the browser.
- There is no server and nothing to install. The whole page is the one file `index.html`.
- It only reads data. It never sends messages or changes anything in SleekFlow or the Sheet.

## Updating the live page

1. Edit `index.html`.
2. Commit and push to `main`.
3. GitHub Pages republishes in 1-2 minutes. Refresh the link to check.

## Notes

- This repo is public. Never put API keys, customer names, phone numbers or private links in it.
- Maintained by Machino IT (it@machino.com.my). The design notes and tests live in Machino's internal project folder, not here.
