# SMS-Email-spam-classifier

The dataset used for training the classifier consists of approximately 10,000 to 11,000 data points, scraped from Kaggle and Google Cloud.

# Steps

data preprocessing steps, which include cleaning, exploratory data analysis (EDA), text pre-processing, modeling, evaluation, and deployment.

# Implementation

Exploratory Data Analysis (EDA) reveals that the dataset contains a mix of spam and non-spam messages, with around 80% being non-spam and 20% spam.
Further analysis showed correlations between different features in the dataset, aiding in understanding its characteristics.

Data preprocessing involved steps like converting text to lowercase, tokenization, removal of stop words and punctuation, and stemming.
Word frequency analysis helps in identifying key words associated with spam and non-spam messages.
Ham and spam messages will be showcased on the website for testing predictions.
The model successfully predicts spam messages based on provided samples.

# models

Text preprocessing steps included converting text to lowercase, tokenizing, removing special characters and stopwords, and applying stemming to reduce words to their root form.
# Model Building

Text data is converted into numerical features using TF-IDF vectorization.
The dataset is split into training and testing sets.
Three different Naive Bayes classifiers (Gaussian Naive Bayes, Multinomial Naive Bayes, and Bernoulli Naive Bayes) are trained and evaluated for spam classification.
Model performance metrics such as accuracy score, confusion matrix, and precision score are calculated for each classifier.
The TF-IDF vectorizer and the best-performing Multinomial Naive Bayes classifier are saved using pickle.
