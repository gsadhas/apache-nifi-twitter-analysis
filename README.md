Analyzing twitter stream data using,
- Apache nifi
- Power BI streaming dataset
- Apache Hive

Tweets collected from Twitter Stream using Apache nifi and sent to dashboard created on Microsoft Power BI streaming dataset. In addition, tweets collected and stored for historical analaysis in HDFS. You can find more detalied information in this blog post https://blog.gsadhas.com/2018/11/twitter-streaming-analysis-using-apache.html

## How to run
Please check the blog post

The following report was created using Power BI streaming dataset

## Report on tweets
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/tweets.png)

## Twitter users and tweets source
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/user_sources.png)

## Search tweets
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/search.png)

## Hive table
Tweets stored in HDFS is accessed via Hive queries
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/hive_table.png)
