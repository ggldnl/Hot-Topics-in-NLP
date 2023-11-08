In implicit representations the number of dimensions of the representation is smaller, not readable. Once we decie how big the vector will be, it is a neural network that during the training process will create it, we have no control over it.
In explicit representations the number of dimensions of the representation is larger, normally given by the size of the vocabulary.
Explicit representation can be created either from words or senses.


ppMI(w, w') = log((P(w, w'))/(P(w)P(w'))) if P(w, w') > 0 else 0