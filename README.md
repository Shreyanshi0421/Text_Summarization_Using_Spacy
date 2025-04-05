Text Summarizer using python library Spacy (designed especially for solving NLP problems).

What is spaCy?
spaCy is a free, open-source advanced natural language processing library, written in the programming languages Python and Cython. spaCy mainly used in the development of production software and also supports deep learning workflow via statistical models of PyTorch and TensorFlow.


Why spaCy?
spaCy provides a fast and accurate syntactic analysis, named entity recognition and ready access to word vectors. We can use the default word vectors or replace them with any you have. spaCy also offers tokenization, sentence boundary detection, POS tagging, syntactic parsing, integrated word vectors, and alignment into the original string with high accuracy.


There are two categories of text summarization:
#Extractive Summarization : These methods rely on extracting several parts, such as phrases and sentences, from a piece of text and stack them together to create a summary. Therefore, identifying the right sentences for summarization is of utmost importance in an extractive method.

#Abstractive summarization : These methods use advanced NLP techniques to generate an entiely new summary. Some parts of this summary may not even appear in the original text.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Steps that I have followed to make a text summarizer using SpaCy are:**
1. Importing the necessary libraries and uploading the content that needs to be summarized.
   #There are two ways of uploading the content
   1. Which I have done that is directly uploading the content in the code
   2. Using the command - doc = nlp(doc)

2. Filtering the tokens - two lists are created for parts-of-speech and stop words to validate each token followed by filtering of the necessary tokens and save them in the keywords list.
3. Normalization - The frequency can be normalised for better processing and it can be done by dividing the token’s frequencies by the maximum frequency.
4. Weighing the sentences
5. Summarizing the String

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Text Summarizer can also be done using the Gensim library but Spacy is more efficient in summarizing task then Genism.**
