# Exploring the 2023 Nigerian Presidential Election through Tweets

### This is just a fun little project to explore the relationship between the Twitterverse and the 2023 Election in Nigeria. It was a good pretext for experiment with transformers-based sentiment analysis tools.

## Methods

### Tweets were filtered based on whether they contained the name of a single candidate. Tweets were analyzed for sentiment using the model "finiteautomata/bertweet-base-sentiment-analysis" available via a HuggingFace pipeline.

## Analysis

### There were four main candidates in Nigeria's 2023 election - Obi, Abubakar, Tinubu, and Kwankwaso. Of these candidates, Obi was by far the most discussed on Twitter, followed by Tinubu.

![alt text](https://github.com/s-cafferty-nlp/NigerianElections2023/blob/main/data/count.png)

### Despite having high net-positivity on Twitter, Obi lost the election while Tinubu won with a lower ratio of 'positive' Tweets.

![alt text](https://github.com/s-cafferty-nlp/NigerianElections2023/blob/main/data/net_positivity.png)

### Net positivity varied by region. Abubakar was tweeted about most positivly in Abuja while Obi was tweeted about most positively in Lagos and abroad. Most notable, Tinubu was particularly unpopular abroad with a negative net positivity.

![alt text](https://github.com/s-cafferty-nlp/NigerianElections2023/blob/main/data/location.png)

## Conclusion

### Tinubu won the election, despite being less popular on Twitter. Moreover, Tinubu's lack of popularity on Twitter often originated from accounts based abroad, likely from Nigerian expats. Indeed, Twitter is not the real world. Even so, such approaches to NLP for social science are excellent tools for understanding the media ecology of political participation.
