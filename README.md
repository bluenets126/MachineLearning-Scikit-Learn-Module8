# MachineLearning-Scikit-Learn-Module8
Machine Learning Scikit-Learn Summary Lab

Code setup:
KNN EDA and data prep
Recommendation EDA and data prep
Cluster EDA and data prep
KNN implementation
Recommendation implementation
Cluster Implementation
More Recommendations


Recommendation System:

As I mentioned during class, I was struggling with the recommendation system as the instructions weren't very clear or didn't make exactly perfect sense as the best way to create the recommendation system.
Therefor, I created multiple recommendation systems.  As you go through the code, you will see a chicken feed recommendation, but there are more recommendation models at the bottom.
Using the cosine similarity with only 1 PCA component makes all of the results either a 1 or -1 value.  Similar or not similar.  So I put together multiple implementations.
Some implementations do not use PCA at all, one of them uses 2 components, and one of them combine 1 PCA for all data except weight and use weight scaled as the other part of the cosine similarity.
There is also a recommendation system that uses the 1 PCA component and Euclidean distance instead of Cosine similarity.


