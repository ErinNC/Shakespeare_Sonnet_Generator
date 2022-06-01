# Shakespeare Sonnet Generator

Our goal in this project is to build a Shakespeare Sonnet Generator using a recurrent LSTM neural network. More specifically, we will use deep learning libraries, TensorFlow and Keras, to build a Sequential model that will predict the next character from a sequence of characters.

A large portion of this project focuses on cleaning the text data and preparing it for our neural network. We then build and train our model.

There is much room for improvement in our model. Future goals include:
- Building a model in which the sequences are composed of words rather than characters
- Refine the training and text generation to be able to ask for different genres/styles of Shakespearean text
- Train a classification model that takes in text and returns which Shakespearean work it is most likely from


### Download Shakespeare's Sonnets from the [Project Gutenberg](https://www.gutenberg.org/cache/epub/1041/pg1041.txt) website.

### Necessary Libraries
- random
- sys
- os

- requests
- pandas 
- numpy 
- matplotlib.pyplot 
- %matplotlib inline

- tensorflow.keras.callbacks.LambdaCallback
- tensorflow.keras.preprocessing.sequence
- tensorflow.keras.models.Sequential
- tensorflow.keras.layers.Dense
- tensorflow.keras.layers.Embedding
- tensorflow.keras.layers.Bidirectional
- tensorflow.keras.layers.LSTM

- a custom text data preparation class:
  - !wget https://raw.githubusercontent.com/LambdaSchool/DS-Unit-4-Sprint-3-Deep-Learning/main/module1-rnn-and-lstm/data_cleaning_toolkit_class.py
- data_cleaning_toolkit_class.data_cleaning_toolkit


