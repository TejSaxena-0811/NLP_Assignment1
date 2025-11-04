Name: Tej Saxena

Roll Number: 2301730297

Course: B.Tech CSE(AI-ML)

Section: E

Semester: 5



-----------------------------------------------------------------------------------------


**ASSIGNMENT 1:**

This project demonstrates basic Natural Language Processing (NLP) text preprocessing using Python and NLTK. The goal is to clean and prepare raw text by breaking it into words, removing unnecessary terms, and converting words to their root/base form for further analysis or machine learning tasks.

*Tokenization*
Splits a sentence/paragraph into individual words or tokens.
Example: "Climate change is real" → ["Climate", "change", "is", "real"]

*Stopword Removal*
Removes commonly used words that don't add much meaning.
Example: remove words like the, is, and, of

*Stemming (PorterStemmer)*
Reduces words to their root form by chopping off endings (rule-based).
Example: running → run, studies → studi

*Lemmatization (WordNetLemmatizer)*
Converts words to their meaningful base/dictionary form.
Example: running → run, better → good


------------------------------------------------------------------------------------------


**ASSIGNMENT 2:**

This project performs Sentiment Analysis on customer reviews using NLP and Machine Learning. The goal is to classify text as positive or negative by cleaning the text, converting it to numerical features using TF-IDF, and training a Naive Bayes classifier for prediction.

**Key Steps**

*Tokenization*
Splits each review into individual words for processing.

*Stopword Removal*
Removes common words (like the, is, and) that do not add meaning to sentiment.

*Stemming (PorterStemmer)*
Reduces words to their root form to normalize text.
Example: loved → love, working → work

*TF-IDF Vectorization*
Converts text into numerical features based on word importance in the dataset.

*Naive Bayes Model*
A probabilistic classifier used to detect sentiment from processed text.

**Output**

Cleaned text column

Sentiment classification accuracy

Confusion matrix heatmap

Classification report (precision, recall, F1-score)

Sample sentiment predictions



