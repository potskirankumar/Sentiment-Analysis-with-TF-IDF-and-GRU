# Sentiment-Analysis-with-TF-IDF-and-GRU
The dataset I used here was downloaded from Kaggle. Link: https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

Sentiment Analysis in NLP.

Before we look at the code of the sentiment analysis, I want to give an overview of Natural Language Processing (NLP). 
Natural Language Processing:
In simple way, we can give the meaning of NLP as, the act of performing some operations (processing) on Natural Language. Okay, I know, you have doubts about Natural Language. Now, let’s talk about Natural Language. 
Natural Language is the language that human beings are using for communication. (Okay, what is language? We can add a simple definition, language is one of the means for communication). Natural Language is sometimes called as Human Language. The languages we know, for example English, Chinese, Korean, etc. they are Natural Languages. Again, we can also add Sign Language as Natural Language.
Let’s see the definition of NLP.
NLP is a rapid evolving area in Artificial Intelligence (AI). NLP focusses on interaction between machines and natural languages that are evolved for humans. It enables machines to understand natural languages that are used by humans.
Okay, now we know NLP is a field of AI that deals with human languages. So, it’s time to know Sentiment Analysis.

Sentiment Analysis:
Introduction:
With rise of technology, there are numerous social media sites, ecommerce sites, etc. The users give comments or reviews on a particular post or a product. However, we don’t know what they mean. They are just expressing their opinions. Those opinions are called sentiments. So, Sentiment Analysis is sometimes called Opinion Mining. 
For example, let’s say, you bought a car and your friends give you some opinions on your car. They are sentiments. But the sentiments can be positive, negative and neutral. 
Side Note: People sometimes have doubt between Sentiment Analysis and Emotion Analysis. Let me get you to the right place. Sentiment Analysis is just analyzing the polarity towards a text but Emotion Analysis is a step deeper than the former. Emotion Analysis requires the understanding of feelings, modes, etc. behind a text. We can say, Emotion Analysis is an advanced Sentiment Analysis.


What is Sentiment Analysis?
Sentiment Analysis is a task of NLP that involves identifying the opinions that textual data hide.

Now, let’s build a Sentiment Analysis system.
In this system, I used both Scikit-Learn and Tensorflow. As a brief, I experimented using TF-IDF (Term Frequency – Document Inverse Frequency) and train GRU (Gated Recurrent Unit). However, you can use Word2Vec, Glove and FastText for deeper understanding of tokens. TF-IDF is for converting the cleaned text data into numerical forms because Machine Learning (ML), when I say ML I included Deep Learning (DL) too because DL is a subfield of ML just using Neural Network, algorithms don’t understand text data. And then, I reshape the data into GRU compatible format. 


For more explanation please prefer medium blog on my account.
