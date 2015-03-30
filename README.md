# Multidimensional-Index-Structure-using-LSH

Dimensionality curse is significant problem while dealing with high dimensional data. At very high dimensions data become very sparse and hence its loses its statistical significance. Indexing and performing search operations with such high dimension data is not very effective and many of information retrieval, data mining, machine learning algorithms do not perform well with high dimensional data. Hence there is a need for dimensional reduction techniques to find out the inherent dimensions of the data and to cut down less significant ones.

Locality Sensitive Hashing(LSH) technique is used construct multidimensional index structure to index multidimensional data with many dimensions so that most similar objects can be retrieved with high probability and find out nearest neighbors for a given query.

Time to compute hash function is O(r) where r in the number of dimensions. Query cost is time to compute K*L hash functions which is O(rKL) + time to search linearly in L buckets.(one bucket per hash table).
