This repo consists of a spark application written in scala
which read tweets from a kafka server, performs sentiment analysis
[with the code written in python].
The spark job written in scala, calls python code and return
the sentiment analysis of the tweets and store the output and plots
in S3.