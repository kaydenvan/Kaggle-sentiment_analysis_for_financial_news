# Kaggle Exercise
This repository contains the code for a Kaggle exercise, [Sentiment Analysis for Financial News](https://www.kaggle.com/ankurzing/sentiment-analysis-for-financial-news)

### First submission
By referring the ground work done by Movie review sentiment analysis, Bi-directional GRUs have been used with Embedding, Flatten, BatchNormalization, Dense and Dropout layers. As again, two testings have been done before the code published. (1) word cleansing vs (2) no word cleansing. Model with no word cleansing provides a fairly higher accuracy and model with fuzzy word cleansing does not perform well.<br>
Overall, the model can achieve 74% accuracy rate in testing dataset. <br>
**Learning**: Although Adam can tune the learning rate automatically, applying learning rate scheduler to limit the maximum learning  rate could provide a very good training with limited resource.<br>
**Learning**: Checkpoint has been used in this model to extract the optimal model result. This could facilitate continuous delivery and training. <br>
