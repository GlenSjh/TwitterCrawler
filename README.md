# TwitterCrawler
crawler for twitter (without using api)

## Usage
use the prodived jar file to crawl twitter<br>
infoCrawler.jar is used to crawl user meta information, following and followers' screen name<br>
tweetsCrawler.jar is used to crawl user's tweets(include retwees, some video tweets may be lost, maintaining)<br>

## Configuration
file personToCrawl.txt is used to specify users to crawl (screen name should be used)
also, proxy should be added to crawl twitter, the program reads https proxy at 127.0.0.1:1080, map your proxy to local mode.

## Output
The output of the program will be a folder named "Twitter", all user infomation are stored in sub folder named by screen name.



