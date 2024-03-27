# ML-assignment-3
Machine Learning Decision Trees

This is a practice lab of classifying whether a mushroom is edible or poisonous using decision trees in machine learning. 

Firstly, we need a dataset to help identify what kinds of mushrooms be edible. In this case, we have loaded a dataset collected three features of mushrooms: cap color, stalk shape and solitary. For ease of implementation, we have one-hot encoded the features (turned them into 0 or 1 valued features).

After that, we can build a decision tree based on the dataset. To make the purity maximize, we calculate the entropy to choose what feature to split on at each node and calculate the information gain to choose a split on each of the features. These are the key steps in decision tree learning to make the decision effectively.

Finally we get the best feature to split on by computing the information gain from each feature as we did above and returning the feature that gives the maximum information gain. As we can see in the lab, the function returns that the best feature to split on at the root node is feature 2 ("Solitary").

In conclusion, decision trees can work well on structured data but are not recommended for unstructured data such as images, audio and text compared to the neural networks.
