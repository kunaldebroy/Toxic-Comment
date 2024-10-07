This experiment sought to compare the effectiveness of LSTM and CNN models in identifying hazardous remarks. "Which model, LSTM or CNN, performs better in terms of precision, recall, and accuracy for toxic comment classification?" was the study topic motivating this analysis. I used machine learning techniques on a dataset from the Toxic Comment Classification Challenge ("https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge") to answer this topic.


Model Selection Rationale: LSTM models are ideal for text as they handle sequences effectively, capturing long-term dependencies crucial for understanding context in comments. CNN models excel at identifying local patterns like specific toxic phrases, using filters to capture key features in text data.


Data and Experimentation: The study utilized the Toxic Comment Classification Challenge dataset from Kaggle, with preprocessing to prepare text for modeling. Both LSTM and CNN were trained and evaluated to detect toxic comments.


Performance Evaluation: The models were assessed based on precision, recall, and accuracy. These metrics help determine which model is more effective at identifying and classifying toxic comments accurately and with fewer errors.


Key Achievement: Acquired a precision in CNN of 95% which is same as LSTM , Recall of 98% which is 4% more than LSTM and F1-score of 97% which is 2% more than LSTM.
