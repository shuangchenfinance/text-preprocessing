# text-preprocessing
This is a function I use to preprocess texts before using them as data.

# Steps:
1. change to lowercase, replace contractions with their corresponding complete versions
2. remove \n or \\n, which are typical redundant characters in webpage texts, 
3. remove characters that are not alphanumeric or punctuations,
4. remove other typical redundant characters in webpage texts.
5. remove characters that are not alphanumeric.
6. remove numbers
7. tokenize the words
8. lemmatize the words, which may not be necessary and could be replaced with stemming.
9. remove stopwords
