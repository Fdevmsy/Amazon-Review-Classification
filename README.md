# CMPE 239 HW02 BasicsName: Shiyu MouRank & Accuracy: Top7 and 0.7819

## Overview and Goals:
The objective of this assignment are the following:
- Implement the Nearest Neighbor Classification algorithm- Handle text data (reviews of Amazon baby products)- Design and engineer features from text data.- Choose the best model, i.e., parameters of a nearest neighbor classifier, features andsimilarity functions

Implemented a k-Nearest Neighbor Classifier to predict the sentiment for 18506 baby product reviews provided in the test file (test.dat). Positive sentiment is represented by a review rating of +1 and negative sentiment is represented by a review rating of -1. In test.dat you are only provided the reviews but no ground truth rating. These data will be used for comparing your predictions.
Training data consists of 18506 reviews as well, provided in the file train.dat. Each row begins with the sentiment score followed by the text associated with that rating.## Methodology
Combined the trainning set and the test set together to build the dictionary Filtered short words that shorter than 4Built a sparse matrixUsed idf to decrease the importance of popular wordsNormalized the matrixComputed the cosine similarity between Ys and Xs     sims = Y.dot(X.T)Sort the matrix using np.argsort, pretty much faster than sorting a dictionary with sorted() Rank the top 100 neighbours and vote for the most labels.Give every test data a label with the most voted result.print to a txt file.                 