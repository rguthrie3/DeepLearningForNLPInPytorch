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
4. Optimization and Training
5. Creating Network Components in Pytorch
  * Example: Logistic Regression Bag-of-Words text classifier
6. Word Embeddings: Encoding Lexical Semantics
  * Example: N-Gram Language Modeling
  * Exercise: Continuous Bag-of-Words for learning word embeddings
7. Sequence modeling and Long-Short Term Memory Networks
  * Example: An LSTM for Part-of-Speech Tagging
  * Exercise: Augmenting the LSTM tagger with character-level features
8. Advanced: Making Dynamic Decisions
  * Example: Bi-LSTM Conditional Random Field for named-entity recognition
  * Exercise: A new loss function

# References:
* I learned a lot about deep structure prediction at EMNLP 2016 from [this](https://github.com/clab/dynet_tutorial_examples) tutorial on [Dynet](http://dynet.readthedocs.io/en/latest/), given by Chris Dyer and Graham Neubig of CMU and Yoav Goldberg of Bar Ilan University.  Dynet is a great package, especially if you want to use C++ and avoid dynamic typing.  The final BiLSTM CRF exercise and the character-level features exercise are things I learned from this tutorial.
* A great book on structure prediction is [Linguistic Structure Prediction](https://www.amazon.com/Linguistic-Structure-Prediction-Synthesis-Technologies/dp/1608454053/ref=sr_1_1?ie=UTF8&qid=1489510387&sr=8-1&keywords=Linguistic+Structure+Prediction) by Noah Smith.  It doesn't use deep learning, but that is ok.
* The best deep learning book I am aware of is [Deep Learning](https://deeplearningbook.org), which is by some major contributors to the field and very comprehensive, although there is not an NLP focus.  It is free online, but worth having on your shelf.
