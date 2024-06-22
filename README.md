# Email-Spam-Detection
Email spam detection is a crucial cybersecurity process that identifies and filters out spam from legitimate emails, thereby improving email security and user experience.

This project involves detecting spam emails using machine learning techniques. The aim is to preprocess email data, extract relevant features, and build a model that can accurately classify emails as spam or not spam.

### Data Preprocessing
The data preprocessing steps are crucial for cleaning and preparing the data for model training. The following steps are involved:

1. Use Lemmatizer to reduce words to their base or root form.
2. Use NLTK's POS tagger to get the POS tag of a word.
3. Convert to lowercase.
4. Remove punctuation.
5. Remove non-ASCII characters.
6. Remove numeric values.
7. Tokenize and remove stop words.
8. Remove duplicates.

### Feature Extraction
convert the text data into numerical features using TF-IDF
### Building the model
1. Split Dataset into Training and Testing Sets
2. Train a machine learning model on the features. A Naive Bayes classifier was used, achieving an accuracy score of 98%.

### Model Evaluation
The model is evaluated using various metrics to ensure its accuracy and reliability. Key metrics include:
1. Accuracy
2. Precision
3. Recall
4. F1 Score
### Final Steps
1. Save the trained model.
2. Implement a GUI for spam detection.
