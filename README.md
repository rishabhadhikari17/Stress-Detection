# Stress-Detection
Using Natural Language Processing to detect the presence of Stress in the text. Executed CountVectorizer and TfidfVectorizer along with Multinomial and Bernoulli Naive Bayes to compare their accuracies.

Steps followed :
# Importing libraries 
Imported essential libraries such as pandas,seaborn, numpy, matplotlib.pyplot, nltk

# Loading the dataset
Loaded the dataset which was in .csv format

# Basic EDA
Performed basic EDA such as data information, shape of data, data-types of the columns, checking for duplicates and null values.

# Data Cleaning
Following steps were executed for textual data cleaning:
1. Lower Casing all the words
2. word Tokenization
3. Special Characters Detection
4. Removal of Stop words and punctuatuion
5. Porter Stemming the tokens

# Basic Visualization
1. Word Cloud for the cleaned data.
2. Bar plot to demonstrate the distribution of Labels

# Feature Extration
Executed CountVectorizer and TdidfVectorizer for feature extraction

# Model Training
Applied Multinomial and Bernoulli Naive Bayes Algorithm and compared their accuracies.
   
