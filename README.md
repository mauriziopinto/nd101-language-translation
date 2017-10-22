# Language Translation

## Introduction

In this project, I trained a sequence to sequence model on a dataset of English and French sentences that can translate new sentences from English to French.

## Hyperparameters

* Number of Epochs: 4
* Batch Size: 64
* RNN Size: 256
* Number of layers: 2
* Encoding Embedding Dimension Size: 256
* Decoding Embedding Dimension Size: 256
* Learning Rate: 0.001
* Keep probability: 0.75

## One sample result

Input
  Word Ids:      [127, 209, 168, 225, 171, 124, 158]
  English Words: ['he', 'saw', 'a', 'old', 'yellow', 'truck', '.']

Prediction
  Word Ids:      [300, 333, 334, 210, 170, 290, 322, 243, 1]
  French Words: il a vu un vieux camion jaune . <EOS>

## Instructions

* clone the project
* execute **jupyter notebook dlnd_language_translation.ipynb**

