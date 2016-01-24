# Kaggle Competition of CrowdFlower

The goal of this competition was to create an open-source model to measure the relevance of search results. Given the queries and resulting product descriptions from leading eCommerce sites, this competition asked us to evaluate the accuracy of their search algorithms.

I used many algorithms. I used scikit-learn tfidf vectorizer to determine features and calculates the quadratic weighted kappa which is a measure of inter-rater agreement between two raters that provide discrete numeric ratings. Then I used scikit-learn SVM (support vector machine) to predict output of each search article.

I implemented a pipeline including tfidf, truncated SVD, scikit-learn standard scaler and SVM to improve the prediction accuracy.
