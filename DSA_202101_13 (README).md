# Project Overview 

In this project we will go together into Gutenberg Books data to produce classification predictions and compare them; analyze the pros and cons of algorithms and generate and communicate the insights using natural language processing NLP techniques

# Installation


Use the package manager [pip](https://pip.pypa.io/en/stable/) to install these packages.

The Interpret Community SDK builds on Interpret, an open source python package from Microsoft Research for training interpretable models

```bash
pip install interpret-community
```

nlpaug is an library helps you with augmenting nlp for your machine learning projects
```
pip install nlpaug==1.1.0 
```
Transformers provides APIs to easily download and train state-of-the-art pretrained models. Using pretrained models can reduce your compute costs, carbon footprint, and save you time from training a model from scratch. The models can be used across different modalities such as:

📝 Text: text classification, information extraction, question answering, summarization, translation, and text generation in over 100 languages.
🖼️ Images: image classification, object detection, and segmentation.
🗣️ Audio: speech recognition and audio classification.
🐙 Multimodal: table question answering, optical character recognition, information extraction from scanned documents, video classification, and visual question answering.
```
pip install transformers==3.0.2 
```
Snorkel is a Python library that is used for data labelling. It programmatically manages and builds training datasets without manual labelling. In machine learning, labels are the target or the output variable in a dataset.Nov 11, 2021
```
!pip install snorkel==0.9.8 
```
MLxtend is an Library with Interesting Tools for Data Science Tasks
Create counterfactual records, draw PCA correlation graphs and decision boundaries, perform bias-variance decomposition, bootstrapping, and much more
```bash
pip install mlxtend==1.1.0
```
PyCaret is an open-source, low-code machine learning library in Python that automates machine learning workflows. Fast + Explainable + Scalable
```
pip install pycaret[full]
```



# Usage

```python
import nltk
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
nltk.download('gutenberg')
from sklearn import *
```

## How To Run this Notebook 
when you open the notebook run all cells 
There is a cell to install all the necessary libraries 
There will be an error when the LDA part is reached because there are packages dependency error
The kernel should be restarted and start running from LDA section first cell 