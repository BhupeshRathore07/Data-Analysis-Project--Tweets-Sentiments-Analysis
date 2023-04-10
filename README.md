# IPL-Tweets-Sentiments-Analysis-Jio-Cinema-App

> On 31st March 2023, IPL 2023 started streaming on the Jio Cinema app for the first time ever, and it was trending on Twitter under the hashtag #jiocinema. As an emerging data scientist, I conducted a sentiment analysis of the tweets related to #jiocinema to understand the overall sentiment of the users.

> Initially, I expected to see a lot of negative tweets due to app buffering and crashing issues, but the results of the sentiment analysis were surprising. Out of the total tweets analyzed, 52.1% were neutral, 30.7% were positive, and only 17.2% were negative tweets. This indicates that the overall sentiment of the users was not as negative as I initially thought.

> Further analysis of the data revealed that the positive sentiment was mainly due to the return of MS Dhoni after a long time and the fact that IPL was happening after a long gap. The users were excited to see their favorite cricketer back in action, and this reflected in their tweets.

> Another positive aspect was the availability of commentary in multiple languages, including Bhojpuri. The tweets related to Bhojpuri commentary were particularly hilarious, and this added to the overall positive sentiment.

> It is important to note that this sentiment analysis is based on the tweets from 31st March to 1st April noon only. The sentiment might change as the tournament progresses, and it would be interesting to conduct a sentiment analysis of the overall tournament to see how the sentiment evolves over time.

## PROCESS:

- To conduct the sentiment analysis of #jiocinema tweets, I utilized various techniques and tools. Firstly, I did not use the Twitter API to scrape tweets; instead, I used the **"snscrape"** library, which is a featureful and user-friendly Python library for scraping tweets. This library provided me with the flexibility to specify various search criteria, such as hashtag, language, date range, and more.

- Secondly, I used the Natural Language Toolkit (nltk), which is a powerful and easy-to-use Python library for natural language processing. I used nltk to preprocess the text data, which included tasks such as tokenization, stopword removal, stemming, and more. This helped in cleaning the tweets and extracting meaningful insights from them.

- Additionally, I used the TextBlob library, which is a Python library for processing textual data. TextBlob helped me in determining the polarity and subjectivity of the tweets, which was crucial for the sentiment analysis.

- To visualize the results, I used the WordCloud library, which is a Python library for creating word clouds. The word cloud helped in highlighting the most frequently occurring words in the tweets. Finally, I used the Matplotlib library to create visualizations such as pie charts and bar graphs to represent the sentiment distribution.

- In conclusion, the use of snscrape, nltk, TextBlob, WordCloud, and Matplotlib helped me in conducting a comprehensive sentiment analysis of #jiocinema tweets related to IPL 2023. These tools provided me with the necessary flexibility, accuracy, and visual representation to derive meaningful insights from the data.


## OUTCOMES (GRAPHS):
- **Bar Graph**

![Bar](https://user-images.githubusercontent.com/70787869/229276750-8df13163-8dbe-438f-9c75-19d5e8d9f169.jpg)


- **Pie Chart**

![Pie](https://user-images.githubusercontent.com/70787869/229276826-1684b61c-f623-4e5e-993a-327a4b98e559.jpg)


- **Positive Word Cloud**

![Positive](https://user-images.githubusercontent.com/70787869/229276758-ecdae96a-cc83-4d95-8fb1-9da607e28de1.jpg)


- **Negative Word Cloud**

![Negative](https://user-images.githubusercontent.com/70787869/229276754-a2cab719-3fdd-4ad0-9220-e321a5451a2b.jpg)


## CONCLUSION:

> In conclusion, the sentiment analysis of #jiocinema tweets related to IPL 2023 revealed that the overall sentiment was not as negative as initially expected, and the positive sentiment was mainly due to the return of MS Dhoni and the availability of commentary in multiple languages.

Enjoy Data Science 'n' Coding 🐍😉
