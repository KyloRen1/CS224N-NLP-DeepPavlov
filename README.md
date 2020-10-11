# CS_224N_NLP-Course

This repository contains homework and the final project of DeepPavlov Deep Learning for the NLP course.

## Homework 1
The purpose of this assignment was to get familiar with the PyTorch library. The first sub-part was to implement the flatten function of an input tensor. Meaning given an input tensor of shape N x C x H x W we want to return N x (C x H x W). The second sub-part was to implement a forward pass of the two-layer fully-connected ReLU network. And the third part was to explore different types of PyTorch Module API


## Homework 2
Assignment 2 involved the exploration of the Word2Vec model on our choice (CBOW in my case). After 10 epochs my Negative Log-Likelihood loss was around 6706. Below is a visualization of 300 words vector representations. 

<p align="center">
  <img src="./assets/word2vec.png" />
</p>

## Homework 3
The task was to code and to train our models with different character-based language model with recurrent (GRU) neural network architecture.
