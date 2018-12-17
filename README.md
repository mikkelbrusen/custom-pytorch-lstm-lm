# Language Model Using a Custom Build LSTM
This repository contains the code to implement a Language Model using a custom LSTM built within the PyTorch framework.

This custom LSTM was built as part of a project in the course 02456 Deep Learning @ DTU - Technical University of Denmark
+ This code was originally forked from the [PyTorch word level language modeling example](https://github.com/pytorch/examples/tree/master/word_language_model).

The model comes with instructions to train a word level language models over the Penn Treebank (PTB)

### Google Colab 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/weiji14/deepbedmap/)

This code is also available in a Jupyter Notebook on Google Colab, which allows the usage of a free GPU to speed up the training. 
More details can be found in the Notebook

## Software Requirements

Python 3 and PyTorch 0.4 are required for the current codebase.

## How To Run
+ Train the model using `main.py`, either with the hyperparameters as is, or by modifying to your needs.
+ When a model has been trained, run the `generator.py` script to generate text from the language model.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
