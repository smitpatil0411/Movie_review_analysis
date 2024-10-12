DATA SET LINK:- https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

" Movie_review_analysis" 
This project  develops a machine learning model for sentiment analysis on movie reviews, with the goal of automatically classifying reviews as positive or negative based on the sentiment expressed in the text. The project involves:

Data Collection: Gathering data from sources such as IMDB or Rotten Tomatoes or any other sources.
Text Preprocessing: Cleaning the text data by removing noise and normalizing the text.
Model Selection and Training: Choosing and training machine learning models such as Logistic Regression or Support Vector Machines.(we chose logistic regression)
Performance Evaluation: Assessing model performance using metrics like accuracy and F1-score.
The deployed model will provide insights into audience sentiment towards movies, benefiting filmmakers, studios, and review websites by informing decision-making processes and enhancing the understanding of audience preferences.
Data Preprocessing: Loaded the dataset, cleaned reviews by removing special characters, converting to lowercase, tokenizing, and removing stopwords to prepare text for modeling.

Label Mapping: Converted sentiment labels to binary format, mapping 'positive' to 1 and 'negative' to 0.

Text Vectorization: Used CountVectorizer to convert the cleaned reviews into a matrix of token counts for machine learning.

Train-Test Split: Split the dataset into training (80%) and testing (20%) sets to evaluate model performance on unseen data.

Logistic Regression Model: Trained a logistic regression classifier using the vectorized training data to predict binary sentiment labels.

Evaluation: Predicted sentiments for test data, then calculated accuracy and F1 score to measure model performance.

Prediction: Tested the model on new sample reviews, processed them similarly, and predicted whether they are positive or negative based on the trained model.
