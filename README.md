# aragog
Spider Crawler, crawls the hell out of the web
Aragog is a web crawler built using scrapy.

Edit aragog.properties to configure your crawl
allowedDomains : focus crawl on set of domains
seeds          : start the crawl from set of URLs
pagesToCrawl   : Limit the crawl to certain number of results
allowPattern   : Regex to match URL when recursively crawling
denyPattern    : Regex to avoid URL when recursively crawling

How to run aragog : 
#cd ARAGOG_INSTALL
#scrapy crawl aragog


