## WORD EMBEDDINGS
This project is about creating word embeddings for given data using word2Vec.
# DATASET
 Final_dataset.txt is a text file containng the news article in various domains like sports , politics, bussiness and entertainment.
 I have used this file as text input to generate word embeddings.
 
 # PREPROCESSING
 In the preprocessing i have removed all the noise from data such as numbers or punctuation marks.
 In the remove_stopwords function i have used nltk to remove all the stopwords such as ["am","i","are"...].
 
 Read more about stopwords here https://www.geeksforgeeks.org/removing-stop-words-nltk-python/
 
 # TRAINING
 I have used gensim to train word2Vec model for my text input.
 After training we get our word embedding which a 32 dimensional vector for each word.
 # DIMENSIONALITY REDUCTION
 In this part we are converting our 32 dimensional vector to a 2 dimenstional vector using PCA so it is easier for us to visualize it.
 # PLOTTING THE WORD EMBEDDINGS
 I have used matplotlib to plow word embeddings using a scatter plot. Each point in vector space is a word embedding so now we can visualize the semantic similarity . We can have this takeaway that words having similar context lie close to each other and far away from words of different context. 
# BLOG ON NLP REPRESENTATION TECHNIQUES
 You can also refer to my blog on NLP REPRESENTATION TECHNIQUES for more information:
 https://medium.com/@shivambatra76/nlp-representations-techniques-part2-86b2fd4e04b9
 
