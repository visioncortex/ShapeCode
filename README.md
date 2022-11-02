# ShapeCode - Shape Encoding and Symbolic Recognition

> This is unpublished research, I have been procrastinating for several years. It will probably never be published, but at least can serve as a memoir

Basically we developed and experimented with a shape encoding algorithm that has very interesting property:

+ translation / scale invariant
+ rotational invariant under a normalization scheme
+ *the similarity of two symbols is a linear function of the weighted Hamming distance between the two encoded bitstrings*

The algorithm is particular effective in searching a symbol from a database of symbols, and the experimental results on Chinese / Korean OCR shown great results. It can definitely be generalized to more complex graphics, i.e. colored signage
