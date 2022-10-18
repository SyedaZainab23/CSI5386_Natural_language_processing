CSI5386: Natural Language Processing

Assignment 1

Part 1: Corpus processing (legal text): tokenization and word counting [50 points] 
Implement a word tokenizer that splits texts into tokens and separates punctuation marks and other symbols from the words. Please describe in your report all the decisions you made relative to pre-processing and tokenization.  Implement a program that counts the number of occurrences of each token in the corpus. 
You can use any tools for tokenization, and write programs only if you need to put the data in the right format or to compute additional information. There are many NLP tools that include tokenizers.

It contains 510 files with full text contracts (a collection of TXT files of the underlying contracts). Each file is named as “[document name].txt”. These contracts are in a plaintext format and are not labeled. You will need to concatenate all the text files to form a corpus.
 

Provide in your report the following information about the corpus:

a)    Submit a file output.txt with the tokenizer’s output for the whole corpus. Include in your report  the first 20 lines from output.txt.
b)    How many tokens did you find in the corpus? How many types (unique tokens) did you have? What is the type/token ratio for the corpus? The type/token ratio is defined as the number of types divided by the number of tokens.
c)    For each token, print the token and its frequency in a file called tokens.txt (from the most frequent to the least frequent) and include the first 20 lines in your report.
d)    How many tokens appeared only once in the corpus?
e)    From the list of tokens, extract only words, by excluding punctuation and other symbols, if any. Please pay attention to end of sentence dot (full stops). How many words did you find? List the top 20 most frequent words in your report, with their frequencies. What is the type/token ratio when you use only words (called lexical diversity)?
f)    From the list of words, exclude stopwords. List the top 20 most frequent words and their frequencies in your report. You can use this list of stopwords (or any other that you consider adequate). Also compute the type/token ratio when you use only word tokens without stopwords (called lexical density)?
g)    Compute all the pairs of two consecutive words (bigrams) (excluding stopwords and punctuation). List the most frequent 20 pairs and their frequencies in your report.


Part 2: Evaluation of pre-trained sentence embedding models  [50 points]

Word embeddings are dense representations of the meaning of words, build via neural language models. Sentence embeddings are dense representations of sentences, that can be composed by averaging the word vectors or sentence representations can be learned directly.
Chose at least 5 pre-trained sentence embeddings. If they have different parameters, you can experiment with them, but choose one for your report. Also make sure to include doc2vec (Le and Mikolov 2014, https://cs.stanford.edu/~quocle/paragraph_vector.pdf ) and SBERT (Reimers and Gurevych, 2019, https://aclanthology.org/D19-1410/) (https://www.sbert.net/) in addition to other pre-trained language model that can represent sentences.
