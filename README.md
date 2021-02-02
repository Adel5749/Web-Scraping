# Web-Scraping
This is a python module to periodically scan and parse news from newswire website. 
https://www.prnewswire.com/news-releases/news-releases-list/
it Keeps track of the already parsed news: 
For all unparsed news, scan the content of the news to find a stock symbol.
e.g. (TSX:SHOP)
Scan the yahoo finance for the stock symbol appeared in the news. 
- Get the stock price and volume of last 5 days.
Prepare a nice visualization showing the News headline and Stock prices of last 5 days. 
- visualization is a plot (time - series) for:
- Volume
- Daily Close Price
