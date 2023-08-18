# Sentimental-Analysis
Sentiment Analysis of Aadhipurush Movie Tweets Using NLP.

I have downloaded the data from twitter Api and made the project. I have provode the same csv file  in my Git repository. please check. After uploading the csv file I have looked into the data what all the columns consists of.

I did some preprocesing  of te data like removeing the unwanted columns and duplicates etc.

Here are the few plots of no of tweets in a respective day. we have a different pictorial views of these tweets in a day.




![image](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/bd74595c-57cc-445b-832f-1980939cf59f)



![image](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/70027d7e-70da-4fe7-9282-db66fd6e6ab9)

![image](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/c285bdfa-c423-4708-a008-171fb7b8f7d4)

![image](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/165dad69-af88-4141-912b-52f6fff5579a)

![image](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/7988114b-be79-45be-a928-21962c04a9a9)

![image](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/d0fc547e-4629-4a00-9189-db4e8b924355)

After using lot of preprocessing techniques like Remove URLs, Remove hashtags, Remove mentions, Remove special characters except alphanumeric and spaces,Rremove leading and trailing whitespace from a string, Remove stopwords for English and Hinglish, Remove punctuation, Perform stemming, Tokenizing the tweets.

After that i had used VADER Module and Hugging faces transformers to analyse the sentiment of the Movie.

Below are the results of VADER's results

![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/2722a8f7-de92-4b44-9b31-013d4bafabaa)


![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/269e501f-5a66-4b8a-822d-bc83191dd216)


Below are the results of Hugging Face's results


![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/24fdcdcf-b033-42a5-bc1c-6b6b99905ccb)


![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/bca6b9a3-7433-4fc3-b89f-5494824bb075)

Below are the words that repeated mostly in all the tweets.

![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/c91fca26-b5ef-4e6f-86b5-f0a98adc3139)

Below are the words that repeated mostly in negative tweets.

![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/5074695d-9d04-470a-a8db-1e64b8adaaea)

Below are the words that repeated mostly in positive tweets.

![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/35d56462-91d2-419b-bcdd-f1bedae08bdd)

Below are the words that repeated mostly in Neutral tweets.

![download](https://github.com/MARCUS-MITc/Sentimental-Analysis/assets/123622512/5aebd22f-bb1c-4770-85b7-57c79e4714dc)

Then employed the Multinomial Naive Bayes algorithm from the scikit-learn library to train the model, achieving an impressive accuracy of 79%.

X is cleaned Tweets y is sentiments.


The Multinomial Naive Bayes algorithm is a probabilistic machine learning algorithm that is used for text classification. It is based on the Bayes theorem, which states that the probability of an event A happening, given that event B has already happened, is equal to the probability of event A happening times the probability of event B happening given that event A has already happened, divided by the probability of event B happening.

In the context of sentiment classification, the Multinomial Naive Bayes algorithm works by assuming that each word in a Tweet is independent of the other words. This means that the probability of a Tweet being classified as a certain class is equal to the product of the probabilities of each word in the document being in that class.

