# Python-recommender-101
Going off from Kaggle's recommendation system tutorial. This is an overview of an actual python recommendation system based on news sharing and user interactions 

# Recommender Techniques
3 types of recommender techniques were built and tested:
1. Content based filtering
2. Collaborative filtering
3. Hybrid approach 

# Baseline
Basedline was created using popularity recommender but this doesn't have any personalization

# Recommender Evaluation
The common recommender evaluation criteria includes:
1. Top N metrics
2. **NDCG@N** 
3. **MAP@N**

# Cross Validations
The tutorial covers the simple 80/20 split between train and test.
However, to model what the recommender would produce in production, the timestamp based split should be used to model what the recommender would spit out on a particular date
