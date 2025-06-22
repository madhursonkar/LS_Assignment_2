In problem 3, the manually calculated tfidf results were different from that calculated using tfidfvectorizer because sklearn 
normalizes TF-IDF vectors (usually L2 norm), which shrinks the values but maintains relative proportions.
