# Toxic-Comment-Classification
fter we have loaded our test and drain data.
Our data features aren’t complicated and few which are:
 [‘id', 'comment_text', 'toxic', 'severe_toxic', 'obscene', 'threat', 'insult', 
'identity_hate'] 
We have decided to do our feature selection manually with Train.drop function 
So, we have removed the un unnecessary columns which are
[‘id', 'comment_text'] 
And then we have done a Dataframe made up of category and total number of 
comments. 


• remove_special_chars: replacing specific char with a given one.
• to_lowercase: transform chars into lowercases. 
• remove_punctuation: Remove punctuation from list of tokenized 
words
• replace_numbers: Replace all interger occurrences in list of toke
nized words with textual representation.
• remove_whitespaces: Removes white spaces
• remove_stopwords: Removes stop-words
• stem_words: Stem words in text
• lemmatize_words: Lemmatize words in text
• lemmatize_verbs: Lemmatize verbs in text
• text2words: Return word_tokenize
• clean_text: Call the previous functions and apply them
