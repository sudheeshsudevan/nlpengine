# NLP Engine

**nlpengine** is a collection of Natural Language Processing functions. Its designed to make a NLP engineer's life easier by bundling some of the everyday tasks like data cleaning, feature extraction, text classification, etc. This module is built on top of other popular open source python libraries.

# Installation

```python
pip install nlpengine
```

# Features

 The key featues in the initial release of **nlpengine** includes:
 

 - [ ] Easy to use text classifiers
 - [ ] NER
 - [ ] Several NLP functions 

### Text Classifier

 1. A wrapper on top of Facebook's **[FastText](https://github.com/facebookresearch/fastText)** text classifier to build a text classifier with jus two lines of codes.
	 
   ```python
    from nlpengine.classifiers.fasttext_classifier import FastTextClassifier
    clf = FastTextClassifier()
    model = clf.fit(text, labels)
