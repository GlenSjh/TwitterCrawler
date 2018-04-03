# TwitterCrawler
crawler for twitter (without using api)

## Requirements
jre<br>
https proxy to crawl twitter

## Usage
use the prodived jar file to crawl twitter<br>
infoCrawler.jar is used to crawl user meta information, following and followers' screen name<br>
tweetsCrawler.jar is used to crawl user's tweets(include retwees, some video tweets may be lost, maintaining)<br>

## Configuration
file personToCrawl.txt is used to specify users to crawl (screen name should be used)
also, proxy should be added to crawl twitter, the program reads https proxy at 127.0.0.1:1080, map your proxy to local mode.

## Output
The output of the program will be a folder named "Twitter", all user infomation are stored in sub folder named by screen name.

## Notes
We seperate the program into two jars to increase the speed, due to crawler limitation, it costs much time to crawl user's all followers(about 20min for 20000 followers). The speeds to crawl user's tweets is about 15min for 20000 tweets.
Make sure you delete all contents in Twitter/ before you run new program (re-run the program will cause repeatition issue)



