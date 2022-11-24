# Nowcasting Unemployment Rate Using Twitter Data: The Case of South Africa

This repository includes the dataset of our manuscript:

ZM Nia, A Asgary, N Bragazzi, B Mellado, J Orbinski, J Wu, J Kong (2022) Nowcasting Unemployment Rate Using Twitter Data: The Case of South Africa, Frontiers in Public Health, doi: 10.3389/fpubh.2022.952363

This dataset includes 1182632 tweet IDs, their sentiment classes, and their sentiment scores: 

- TweetID: every tweet has a unique ID that could be used by Twitter API to retrieve the the text and other metadata.
- Sentiment: indicates whether the tweet has a positive, neutral, or negative sentiment.
- Score: gives a number between [-1, 1] to the tweet based on its sentiment. Tweets with positive, neutral, and negative sentiments have a score close to 1, 0, and -1, respectively.

In compliance with [Twitter developer's term of use and privacy policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy), only the tweet IDs are shared with public. To find other meta-inforamtion such as date, geo-information, and author-information, the tweets need to be hydrated.

Since the dataset is very large, it is divided into three files:

- dataset1.csv: includes 394210 tweets posted from June 8, 2010 to February 22, 2017.
- dataset2.csv: includes 394210 tweets posted from February 22, 2017 to October 22, 2019.
- dataset3.csv: includes 394212 tweets posted from October 22, 2019 to December 23, 2021.

If you use this dataset for your work, please kindly cite our article:

ZM Nia, A Asgary, N Bragazzi, B Mellado, J Orbinski, J Wu, J Kong (2022) Nowcasting Unemployment Rate Using Twitter Data: The Case of South Africa, Frontiers in Public Health, doi: 10.3389/fpubh.2022.952363
