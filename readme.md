## Spam Detection Using TF-IDF
The Dataset used is provide by **UCI, Irvine** and can be downloaded from [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00228/).

The code uses TF_IDF from Scikit-learn's TfidfVectorizer() which can be imported from sklearn.feature_extraction.text. Then the extracted features are trained with Multinomial Naive Bayes. The trained model on 70-30 split gave 95%+ accuracy.