# M4 | Optimisers_101

This project is a part of ApScript Hackathon.

## Problem statement

> **_Sentiment Analysis from text feedback._**

Sentiment analysis from text feedback is used by an ever increasing number of people, and organisations to automatically classify feedback in the form of comments or chats. It could be people commenting on a Youtube video, ratings for an app on an app store, or chats with a virtual assistant. It is impossible for a single person to go through the entire length of comments/chats and so machine learning solutions to this would be very useful.

## Problem Approach

Sentiment analysis is an area of Natural Language Processing (NLP) that focuses on understanding human emotion in text.

Knowing whether a review or a comment is positive or negative goes a long way when looking for some feedback to improve services and applications. Our model is currently capable of taking a sentence and classifying its intent as either positive or negative.

The steps are listed below for explaining the working:

**Pre-Processing** - Preprocessing is a common stage in any task involving Twitter data because of the language irregularities that are present in tweets. 

**Pre-trained word vectors** - Learning word representations from massive unannotated text corpora have recently been used in many NLP tasks. Leveraging large corpora for unsupervised learning of word representations enables capturing of syntactic and semantic characteristics of words.

**DCNN Model** - CNNs with pooling operation deal naturally with variable length sentences and they also take into account the ordering of the words and the context each word appears in.

**Tokenization** - Tokenization describes the general process of splitting the text of a document into a series of tokens in order to identify all words in a given document for further processing,especially to create term document matrix.

**Train Embedding Layer** - A word embedding is a way of representing text where each word in the vocabulary is represented by a real valued vector in a high-dimensional space. The vectors are learned in such a way that words that have similar meanings will have similar representation in the vector space (close in the vector space).

## Dataset

We have chosen to use “Sentiment140 dataset with 1.6 million tweets” as our Training and Testing dataset.

The training and testing datasets are added [here](https://drive.google.com/drive/folders/1iyK4_MgVgjsJFip6nrkFi32slSgXsL8K?usp=sharing).

## Team Members

Keerti Chaudhary ([@keerti2001](https://github.com/keerti2001)) <br />
Ameya Deshpande ([@ameyanrd](https://github.com/ameyanrd)) <br />
Aditya Sohoni ([@adityasohoni](https://github.com/keerti2001)) <br />
Shumbul Arifa ([@shumbul](https://github.com/shumbul))

## Presentation Slides

The project presentation slides are [here](https://docs.google.com/presentation/d/1i9SlO2Ic-1wflwU0YZ39pbVTKw2APppR7W4Vxhjuqew/edit?usp=sharing).

## Sentify Demo Video
 Video link [here](https://drive.google.com/file/d/18ntSTxPYw63KV42UEi0WnLV-VhF6GaRQ/view?usp=sharing).

