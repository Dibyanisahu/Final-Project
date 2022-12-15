# Final-Project

## Topic: Building a Business Contextual Chatbot from Scratch in Python (using NLTK)and seq to seq model.

**Objective:** The project is about creating an AI contextual chatbot using NLP and deep learning that understands customers queries related to the organisation.

**Motivation:** The idea of the project was not to create very high ended chatbot having excellent cognitive skills but using basic python and machine learning to help myself do my first deep learning, NLP project.

**Pre-requisites:** 
NLTK(Natural Language Toolkit): Natural Language Processing with Python provides a practical introduction to programming for language processing.

**Installation of NLTK:** 
pip install nltk

import nltk

nltk.download('punkt')

nltk.download('wordnet')

from nltk.stem import WordNetLemmatizer

lemmatizer = WordNetLemmatizer()

import pickle

import numpy as np

from keras.models import Sequential

from keras.layers import Dense, Activation, Dropout

from keras.optimizers import SGD

**How to run:** 
Using jupyter notebook.

**Reference:** https://towardsdatascience.com/how-to-create-a-chatbot-with-python-deep-learning-in-less-than-an-hour-56a063bdfc44


