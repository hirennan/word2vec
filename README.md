# Basic implementation of word2vec

Implementing this algo over text8 corpus, which is the first billion characters in wikipedia dump. Iterates over the first 10000 character which is 1603 words and builds the embedding matrices C, W using SGNS.

- has a helper function to fing top k closest words and visualise

## Plan is to (going forward):

- Go over the entire corpus
- Vectorise it maybe
- increase negative samples size?
- batching for efficiency