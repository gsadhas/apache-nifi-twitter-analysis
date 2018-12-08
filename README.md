Analyzing twitter stream data using,
- Apache nifi
- Power BI streaming dataset
- HDFS
- Apache Hive

Tweets collected from Twitter Stream using Apache nifi and sent to dashboard created on Microsoft Power BI streaming dataset. In addition, tweets collected and stored for historical analaysis in HDFS. You can find more detalied information in this blog post https://blog.gsadhas.com/2018/11/twitter-streaming-analysis-using-apache.html

## How to run
Please check the blog post

## Dashboards
The following reports were created using Power BI streaming dataset

Tweets report 
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/tweets.png)

Twitter users and tweets source
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/user_sources.png)

Search tweets
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/search.png)

## Hive table
Tweets stored in HDFS for further analysis. I built Hive table on top of HDFS files.
![alt text](https://github.com/gsadhas/apache-nifi-twitter-analysis/blob/master/images/hive_table.png)
