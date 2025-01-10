# Project_WoC_7.0_Fake_Review_Detection
Data preprocessing for Fake Review Detection as part of Winter of Code 7.0 (NLP ).

**Preprocessing Steps**

**Loading the Dataset** : The raw dataset was loaded into a Pandas DataFrame for exploration and processing.

**Data Cleaning** : Removed duplicate entries to ensure unique data.

**Text Normalization** : Converted all text to lowercase.
Removed punctuation, special characters, and numbers.

**Tokenization** : Split the normalized text into individual words (tokens).

**Stopword Removal** : Removed common stopwords to retain only meaningful words.

**Stemming/Lemmatization** : Standardized word forms by applying either stemming or lemmatization.

**Text Vectorization** : Transformed text into numerical vectors using the Word2Vec method to represent the important words.

Saving the FInal Preprocessed Data : Saved the final  cleaned and transformed dataset as final_fake_review_data.csv
