# STOCK Act data in json format

* `doc-raw` folder contains all documents processed by tesseract-ocr
* `reports` contains all stock related reports from https://efdsearch.senate.gov/ portal
* `reports/all.json` contains all data from `reports` folder

## How often is data updated?

All data is automatically generated on hourly basis from https://github.com/cryptoratsdev/senate-disclosures-to-json repository.


## Do I need to download the data?

Not really. Simplest way to consume all reports would be by getting json from [Github](https://raw.githubusercontent.com/cryptoratsdev/senate-disclosures/main/reports/all.json)
