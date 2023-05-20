# N-Gram-Language-Model

## Part 1: Build an n-gram language model

In this part, you need to develop an n-gram model that can handle any order of n-gram. The task involves building two language models:

1. **Language Model from Training Data (LM_1_Corpus.zip):**
   - Build a language model using the provided training data.
   - The model should be capable of handling bigrams and trigrams.
   - For words with zero probability, utilize the technique described in the class and the book.

2. **Language Model from The Berkeley Restaurant Project (BeRP):**
   - Utilize the functions provided in the NLTK Corpora, specifically for the BeRP.
   - These functions should take a sentence formatted the same way as the training data.
   - Return the probability assigned to that sentence by your model.

## Part 2: Implement Sentence Generation

In this part, you'll implement sentence generation for both language models using two methods:

1. Simple Probability Method:
   - Generate sentences based on the probabilities assigned by the language model.

2. Shannon’s Method:
   - Implement sentence generation using Shannon's method as discussed in class.

## Part 3: Create an Out-of-Domain Test Set and Measure Performance

In this part, you need to find or curate an out-of-domain test set consisting of 100 sentences. Ensure that the sentences are formatted consistently with the provided test set. Then, use your favorite Python library to calculate the performance metrics for the language models on this out-of-domain test set.
