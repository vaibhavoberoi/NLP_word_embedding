# NLP_word_embedding

Word embedding is defined as the collective name for a set of language modeling and feature learning techniques in NLP where words or phrases from the vocabulary are mapped to vectors of real numbers. It involves a mathematical embedding from a space with many dimensions per word to a continuous vector space with a much lower dimension.

We implement 2 techniques of Word embedding in this repo:

-The CBOW model : It tries to predict the current target word (the center word) based on the source context words (surrounding words).

-Skip-gram model : It tries to achieve the reverse of what the CBOW model does, i.e. it tries to predict the source context words (surrounding words) given a target word (the center word).
