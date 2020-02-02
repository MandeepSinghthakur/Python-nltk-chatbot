# Python-nltk-chatbot
Retrieval Based Chatbot

Steps: 
1) Import and load the Data. intents.csv (You can edit your own data and train it)
2) Preprocess the Data -
    Steps: lemmatization and stemming
    Lemmatization :
      Process of grouping together the diffrent inflected forms of the word so they can be analysed as a single item
      Example: rocks - rock, corpora - corpus
    Stemming:
      A processing interface for removing morphological affixes from the words. 
    
    Python library NLTK includes many methods for pre-processing as per below:
      nltk.
        fem2mase - feminine form to masculine form
        norm - normalize the word from plural form to the singular form
        pref - remove prefixes from the word's begining
        stem - word's stem based on ArLstem
        verb - stem the verb prefix and suffixes or both
 3) Create training and test data - convert the text to numerical values so that neural network/ computer can understand it
 4) Build the Sequential Model
 5) Predict the response
    
      
