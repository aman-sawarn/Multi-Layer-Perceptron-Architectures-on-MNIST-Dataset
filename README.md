### Please note: All of the codes below can be run in this folder using Google Collaboratory.
I encourage you to copy the code, make changes, and experiment with the networks yourself as you read this article.

#### Although neural networks have gained enormous popularity over the last few years,
#### for many data scientists and statisticians the whole family of models has (at least) 
#### one major flaw: the results are hard to interpret. 

##### Neural networks frequently have anywhere from hundreds of thousands to millions of weights that are individually tuned 
##### during training to minimize error. With so many variables interacting in complex ways, it is difficult to describe 
##### exactly why one particular neural network outperforms some other neural network.This complexity also makes it hard to
##### design top-tier neural network architectures.

##### Training data is the data our model learns from.

##### A loss function is a function to quantify how accurate a model’s predictions were.
##### An optimization algorithm controls exactly how the weights of the computational graph are adjusted during training

##### Here< I have worked through a series of simple neural network architectures and compare their performance on 
##### the MNIST handwritten digits dataset. The goal for all the networks we examine is the same: take an input
##### image (28x28 pixels) of a handwritten single digit (0–9) and classify the image as the appropriate digit.
