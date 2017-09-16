This is the Decision Trees - Transparency assignment. As discussed in class

Choose a dataset that you like. The datasets that you and your classmates submitted are available here: 
https://goo.gl/gsg8QB 
It could also be a new dataset. Choose a dataset where you can understand what the individual features mean; do not choose an image dataset. Your dataset should have at least 100 objects. For this project, choose a dataset that is easy to parse. NOTE: THE DATASETS THAT ARE ALREADY AVAILABLE ON SCIKIT-LEARN ARE NOT ACCEPTABLE. THE DATASETS THAT ARE AVAILABLE AT http://scikit-learn.org/stable/modules/classes.html#module-sklearn.datasets ARE NOT ACCEPTABLE EVEN IF THEY ARE LISTED ON THE GOOGLE SHEET. 

Create a Jupyter notebook. Name it assignment3. It should have several sections. The first section should describe the dataset. The second section should load the dataset.

If the dataset already comes in train-test split, great. If not, create a train-test split, using 2/3 for train and 1/3 for test.

In the next three sections, train a decision tree of at most depth = 1, 2, 3. If your task is classification, use http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier. If your task is regression, use http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html#sklearn.tree.DecisionTreeRegressor. Both have a max_depth parameter. Use it to set the maximum depth. For each depth, train the tree, visualize it, test it on train, and test it on test.

In the next three sections, follow the same instruction above, except, experiment with depths of 4, 5, and 6. Do not visualize the data.

In the last section, discuss the results. How does the tree change from one depth to another? Do the trees make sense to you? How does the performance on the train set change as a function of depth?  How does the performance on the test set change as a function of depth? Any other observation you'd like to add?
Upload the notebook to your github repository.

Submit the link to your notebook as your assignment.

Feel free to update the notebook until due date. DO NOT UPDATE THE NOTEBOOK PAST DUE DATE. OTHERWISE, YOU'LL GET A ZERO.
