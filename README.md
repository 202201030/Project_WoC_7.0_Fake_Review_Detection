# Project_WoC_7.0_Fake_Review_Detection

**-> Load the Dataset :**
Import the dataset (fakeReviewData.csv) using Pandas for preprocessing.

**-> Handling Missing Values :**
Removed rows with missing or NaN values to ensure clean data.

**-> Removed Duplicates :**
Eliminated duplicate rows to prevent redundant processing.

**-> Normalized Text :** 
Converted text to lowercase and remove punctuation, special characters, and numbers.

**-> Tokenization :**
Split text into individual words (tokens) using NLTK's tokenizer.

**-> Remove Stopwords :**
Filter out common stopwords (e.g., "the", "and") to focus on meaningful words.

**-> Lemmatization :**
Reduced words to their base or root form for uniformity using WordNet lemmatizer.

**-> Train Word2Vec Model :**
Train a Word2Vec model on the tokenized corpus to generate word embeddings ( vector size 100 ).

**-> Compute Sentence Vectors :** 
Calculated sentence vectors as the average of word embeddings for each tokenized sentence.

**-> Saved Processed Data :**
Exported the processed data with sentence vectors to a CSV file for further use.

**-> Download Processed Data :**
Download the saved processed file (processed_fake_review_data.csv) for analysis.
