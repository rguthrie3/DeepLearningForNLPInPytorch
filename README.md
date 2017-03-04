# What is this tutorial?
I am writing this tutorial specifically for a Natural Language Processing class at Georgia Tech, to ease into a problem set I wrote for the class on deep transition parsing.
The problem set uses some advanced techniques.  The intention of this tutorial is to cover the basics, so that students can focus on the more challenging aspects of the problem set.

There are plenty of other tutorials out there, but they all seem to have one of two problems, which is why I am writing my own:
* They have a lot of content on computer vision and conv nets, which is irrelevant for our class and might just confuse students
* Pytorch is brand new, and so many deep learning for NLP tutorials are in older frameworks, and usually not in dynamic frameworks like Pytorch, which have a totally different flavor.

# Table of Contents:
1. Introduction to Torch's Tensor Library
2. Computation Graphs and Automatic Differentiation
3. Deep Learning Building Blocks: Affine maps, non-linearities, and objectives
4. Word Embeddings: Encoding Lexical Semantics
5. Training and Optimization
6. Creating Network Components in Pytorch
7. Making Decisions
8. Sequence modeling and Long-Short Term Memory Networks

My intention is for the tutorial to contain several fully working examples and exercises for students.  They will be:

* An N-Gram language modeler using an MLP
* A language modeler using an LSTM
* A more complicated LSTM example: something with part of speech tagging
* CBOW
* Something with the network architecture depending on the sentence (probably a POS tagger with a viterbi decoder)
* Something where you use an LSTM one step at a time (like a Stack LSTM, but not that because that is in the pset)
