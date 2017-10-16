In this assignment, you'll work on transparency of Bernoulli naive Bayes. You need a "binary classification" dataset (two classes), and you need all features to be either already binary or you need to binarize them yourself. Do NOT use the "binarize" field in the constructor of BernoulliNB. Each continuous feature should be binarized based on whether it is larger or smaller than its mean. Categorical features that have more than two possible values should use one-hot encoding.  The new features should have proper names according to the binarization.

Choose a binary classification dataset. (The same rules in Assignment 3 applies, except there is one additional rule this time: it has to be a classification dataset).

Create a Jupyter notebook. Name it assignment8. It should have several sections. The first section should describe the dataset. The second section should load the dataset. The third section should binarize all the features.
If the dataset already comes in train-test split, great. If not, create a train-test split, using 2/3 for train and 1/3 for test.

Train a BernouilliNB classifier on the train split; use the default parameters.

For the following types of objects, create a section, and print a) the total positive log-evidence,  b) the total negative log-evidence, c) probability distribution, d) top 3 features values that contribute most to the positive evidence, e) top 3 feature values that contribute the most to the negative evidence. Print this information on the following object types:

1) The most positive object with respect to the probabilities.
2) The most negative object with respect to the probabilities.
3) The object that has the largest positive evidence.
4) The object that has the largest (in magnitude) negative evidence.
5) The most uncertain object (the probabilities are closest to 0.5)
