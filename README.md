# NLP Assignment 1 – Sentence Embeddings and Vector Search

### Vector Search
Vector search works by turning text into numbers (vectors) that represent meaning. Then, when you search for something, it also turns your query into numbers and finds the most similar ones by checking which vectors are closest in space.

Example:
Text: "The cat sat on the windowsill" → becomes a vector like [0.3, -0.1, ...]

Query: "Where did the cat sit?" → also becomes a vector

Vector search compares the query vector to all text vectors and picks the ones that are closest (most similar in meaning), even if the wording is different.

It's like searching by meaning instead of exact words. FAISS helps find the most similar vectors to a given query vector. When you search, you give FAISS a vector (the query). FAISS then finds the most similar vectors in the index, which are the most relevant results.

