# Sentiment Analysis of Joe Biden's and Donald Trump's Tweets
<img src="https://ichef.bbci.co.uk/news/410/cpsprodpb/9665/production/_113810583_index_promo_poll_tracker_bw_976.png" style="float:right" alt="My cool logo"/>

As you know, there are less than 60 days left for the 2020 election. And it would not be an exaggeration to say that this election is way more important for USA comparing to other elections, as well as for the rest of the world. So I wondered how positive or negative the candidates of this election, Donald Trump and Joe Biden, are spreading their messages. I chose Twitter because both candidates are heavily using Twitter and I get the tweets and retweets from their accounts via Tweepy. After cleaning datafiles, I applied TextBlob to see the polarity and WordCloud to see which words were used most by them.

**Note**: While I was using Tweepy, I couldn't manage to withdraw the amount of tweets I wanted. For example, when I wrote "counts=150" it came back with 80 and sometimes 20. After trying a couple of times, I decided to analyze the last 121 tweets of both candidates.

