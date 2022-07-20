**Kaggle Competition**
**Google AI4Code: Understand the relationship between the code and markdown cells in python notebooks**

The goal is to use NLP based model to predict the correct order of code and markdown cells based on the source text present in the cells.
In this given competition, the code cells are in correct order, while the markdown cells are unordered. 

We have implemented four variations of the models:
- Baseline XGBoost Ranker using Tfidf vectors
- Cosine Similarity on Fasttext Word embeddings 
- Pre-trained DistillBERT model
- Pre-trained Roberta Model

To access the data visit the link: https://www.kaggle.com/competitions/AI4Code/data
