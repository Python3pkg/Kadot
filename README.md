![Kadot](https://github.com/the-new-sky/Kadot/raw/master/logo.png)

## A clean natural language processing toolkit.

[![Build Status](https://travis-ci.org/the-new-sky/Kadot.svg?branch=master)](https://travis-ci.org/the-new-sky/Kadot) [![Coverage Status](https://coveralls.io/repos/github/the-new-sky/Kadot/badge.svg?branch=master)](https://coveralls.io/github/the-new-sky/Kadot?branch=master) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/513eab88b0af4c93b1524d91090397a0)](https://www.codacy.com/app/lorisazerty/Kadot?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=the-new-sky/Kadot&amp;utm_campaign=Badge_Grade) [![Code Health](https://landscape.io/github/the-new-sky/Kadot/master/landscape.svg?style=flat)](https://landscape.io/github/the-new-sky/Kadot/master) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/the-new-sky/Kadot/master/LICENSE.md) [![Latest Version](https://pypip.in/version/Kadot/badge.svg)](https://pypi.python.org/pypi/Kadot/)


Kadot just let you process a text easily.

```python
>>> hello_world = Text("Hello, I'm Kadot : the clean text analyser.")
>>> hello_world.tokens

['Hello', 'I', 'm', 'Kadot', 'the', 'clean', 'text', 'analyser']
```

## Include

- A Tokenizer
- A Word-Level (like word embedding) and a Text-Level vectorizer. 

That's all ! But **in a very near future :

- A powerful Text Classifier
- A Markov Text Generator 
- A modulable [Named Entity Recognizer](https://en.wikipedia.org/wiki/Named-entity_recognition)

The philosophy behind Kadot is clear, **never hardcode the language rules**: use unsupervised techniques for **support most languages**.
