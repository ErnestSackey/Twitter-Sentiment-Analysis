# Twitter-Sentiment-Analysis

This is an NLP project to analyse data obtain from twitter. 
The data included a train, test, and sample data.
The train and test data were concatinated so both can be cleanse together: A new column (Dateset) created to indicate where each row belongs.

During the cleaning, some of the activities involved were:
1. Removing Twitter Handles (@user) and Hashtag tags
2. Removing Punctuations, Numbers, and Special Characters
3. Removing short words
4. Changing everything to a lower case
5. Splitting every word in the tweets to form a single list

The python library SpaCy was used in cleaning the manipulating the data as well.
Created a column which contains the filtered tweets of the words that are needless.

- Text-Preprocessing with spaCy
- Tokenization with SpaCy

TF-IDF Features were used (Term frequency - Inverse Document frequency)
