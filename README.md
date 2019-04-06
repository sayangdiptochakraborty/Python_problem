# TweetMiner
A python script which can fetch all the tweets(as many as allowed by Twitter API) 
done by  @midasIIITD twitter handle and dump the responses into JSONlines file.


The other part of the script parses the JSONline files to display the
following for every tweet in a tabular format: 
- The text of the tweet.
- Date and time of the tweet.
- The number of favorites/likes.
- The number of retweets.
- Number of Images present in Tweet. If no image returns None.

Libraries Used:
- Tweepy
- Pandas
- JSONlines

Issues:
- Couldn't display the number of images present. However located it in 'entities' column under 'media' and 'type'='photo'
