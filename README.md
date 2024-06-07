# NLP-in-Insurance-Industries  

This project classifies the Claim Insurance description given by the clients into separate buckets, making it easier for further analysis of the actuary teams.

We begin by importing the libraries and our files. WordCloud is created to show us the main words that keep on repeating in the dataset.  
We have preferred to use the Spacy library instead of NLTK since it is more advanced than NLTK and requires fewer codes. The data is preprocessed to remove all the unnecessary words that add no value to our model.

Here also, we have gone with 2 sets of models.
1. Using Standardisation of the data.
2. Without using Standardisation of data.

Grid Search was mainly applied to Random Forests, Support Vector Machines, and Logistic Regression to find the best HyperParameter/Estimators. The Accuracy Scores of all the models were compared and Support Vector Machines and Random Forests with the best Parameters seemed to show the best results.
To give a taste of the result, a table is also shown at the end of the actual claim description data, the actual predictions separating them into the buckets and then our models of Random forest and SVM showing their predictions.
