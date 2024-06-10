# Twitter-Sentimental-Analysis-Using-NLP-and-Python

# Objective: 
Developed a model to classify the sentiment of tweets (Positive, Negative, Neutral) using Natural Language Processing (NLP) techniques and machine learning.

# Data Operations:
Utilized Pandas for data manipulation and preprocessing.
Transformed the target variable from numeric to categorical (0: Neutral, -1: Negative, 1: Positive).
Conducted missing value analysis and removed null entries.

# Text Processing:
Cleaned text data by removing symbols, converting to lowercase, and eliminating punctuation and stop words.
Added a new column to capture the length of each tweet in terms of word count.
Performed one-hot encoding and added padding to standardize input lengths using TensorFlow.

# Model Building:
Built and compiled an LSTM model, specifying features, input length, vocabulary size, dropout layers, and activation functions.
Created dummy variables for the dependent variable.
Split the dataset into training and testing subsets.
Trained the model on the training dataset.

# Evaluation and Prediction:
Normalized predictions to match original categorical data.
Evaluated model performance using accuracy and classification reports.
Visualized data and model performance using Seaborn and Matplotlib.

# Outcome: Achieved accurate sentiment classification of tweets, providing valuable insights into public sentiment.
