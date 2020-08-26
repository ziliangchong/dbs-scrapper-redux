# dbs-scrapper-redux
# Scrapes DBS press releases using selenium and requests

DBS - a prominent Singapore bank - keeps a public online record of all its press releases, which can be easily accessed in `xml` format <a href='https://www.dbs.com/media/news-list.page'>here</a>.

 This is a simple `jupyter notebook` that uses `BeautifulSoup` to extract the relevant information.

 ## Output

 - Press release title
 - Date released
 - Press release URL
 - Country of released
 - Text of press release

 ## Where's my data?
 The final command in the `jupyter notebook` saves the output to a `csv` file.

 ## Requirements
 - `Python`
 - `Selenium`
 - `Requests`
 - Being really into DBS. That, or you're a business journalist or corporate communications professional in the financial sector.
