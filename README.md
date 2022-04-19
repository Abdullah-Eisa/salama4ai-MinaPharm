the assessment needs
```
 ********* ML Engineer Technical Assesment:

Objective:

You are provided with a medical related dataset, containing 5k articles. You are required to demonstrate your NLP, data-mining & topic extraction skills to extract the topics that are included within the dataset along with mapping each article to the corresponding topic names. Each document should be matched to the top three most relevant topic names including the matching probability score.

Kindly, mention how you came up with the optimum number of topics extracted and a final evaluation statement of your work.

 

Requirements:

• It is recommended to use Python/R + LDA for topic name extraction. If you use other technology, you must mention your reasoning for your choice.

• Document your code and communicate your overall evaluation of the problem at hand

• You are expected to include along with your solution a report explaining:

    Tools used
    All performed steps, reasoning and outcomes
    How you can further improve the results
    How to further clean & optimize the data-sets to improve the performance of the LDA algorithm
    Metrics used or to use if any to measure/ improve quality of results?

Dataset 
Pubmed5k.rar
```
## What is topic-modelling?

In machine learning and natural language processing, a topic model is a type of statistical model for discovering the abstract "topics" that occur in a collection of documents. Topic modeling is a frequently used text-mining tool for discovery of hidden semantic structures in a text body. Intuitively, given that a document is about a particular topic, one would expect particular words to appear in the document more or less frequently: "dog" and "bone" will appear more often in documents about dogs, "cat" and "meow" will appear in documents about cats, and "the" and "is" will appear equally in both. A document typically concerns multiple topics in different proportions; thus, in a document that is 10% about cats and 90% about dogs, there would probably be about 9 times more dog words than cat words.

The "topics" produced by topic modeling techniques are clusters of similar words. A topic model captures this intuition in a mathematical framework, which allows examining a set of documents and discovering, based on the statistics of the words in each, what the topics might be and what each document's balance of topics is. It involves various techniques of dimensionality reduction(mostly non-linear) and unsupervised learning like LDA, SVD, autoencoders etc.

