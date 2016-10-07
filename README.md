# inverted-index
Implemented a inverted index and used various retrieval models to compare their performance

1. A tokenizer and indexer
  a . Index should be able to handle large numbers o documents and terms without using excessive memory or disk I/O.
2. A Ranking system implementing the various state-of-the-art techniques
  a. Okapi TF
  b. TF-IDF
  c. Okapi BM25
  d. Unigram LM with Laplace smoothing
  e. Unigram LM with Jelinek-Mercer smoothing
3. Implemented Proximity search
