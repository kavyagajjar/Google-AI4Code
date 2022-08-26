**Kaggle Competition**

**Google AI4Code: Understand the relationship between the code and markdown cells in python notebooks**

The goal is to use NLP based model to predict the correct order of code and markdown cells based on the source text present in the cells.
In this given competition, the code cells are in correct order, while the markdown cells are unordered. 

We have implemented five variations of the models:
- Baseline XGBoost Ranker using Tfidf vectors
- Cosine Similarity on Fasttext Word embeddings 
- Pre-trained DistillBERT model
- Pre-trained Roberta Model
- Pre-trained XLNet Model

Additionally we have implemented three variations of ensemble models:
- Ensemble of equal weightage to DistillBERT, Roberta and XLNet Model
- Ensemble of different weightage to DistillBERT, Roberta(50%) and XLNet Model
- Ensemble of equal weightage to DistillBERT and Roberta Model

We were able to achieve the score of 0.84 using the Ensemble model of DistilBert and Roberta Models.

To access the data visit the link: https://www.kaggle.com/competitions/AI4Code/data
