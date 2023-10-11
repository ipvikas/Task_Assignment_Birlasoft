Next word prediction using 'Bidirectional LSTM' architecture

**Steps are:**
#Step 1: Import necessary libraries and packages

#Step 2: upload Dataset: Currently we are considering dataset consists of sms text and whether that is a spam sms or non-spam sms
    #Task 1: Show total number of rows and columns as number of records and fields resp
    #Task 2: Show the contents under 'sms' column
    #Task 3: Any dataset, scraped from html contains a number of \xa0 unicode.
    #This non-breaking space in Latin1 (ISO 8859-1) needs to be replaced with a space

#Step 3: Tokenization and indexing each word:
    #Tokens can be words, paragraphs, sentences, punctuations, etc.
    #"Low-level tokens" are the unigrams in these words which doesn’t make sense while "High-level tokens" are the complete words

#Step 4: Transforms each text in texts to a sequence of integers.

#Step 5: pad sequences: To make length of every title same

#Step 6: Create features and label. Last element of all sequences as a label and then perform onehot encoding
    ##Multi-class classification

#Step 7: Plotting model accuracy and loss
