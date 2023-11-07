# ENGLISH---HINGLISH-TRANSFORMATION-

# English to Hinglish Translation with Noun Preservation

This Python script uses the Hugging Face Transformers library to perform English to Hinglish translation while preserving nouns in the input text. It identifies nouns in the input sentences and ensures that their translations are retained in the final output. This can be useful for maintaining context and clarity in translations.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Sample Input](#sample-input)
- [Output](#output)
- [License](#license)

## Introduction

Hinglish is a blend of Hindi and English, commonly spoken in various parts of India. This script allows you to translate English sentences to Hinglish while preserving nouns, making the translation more contextually accurate and meaningful.

## Prerequisites

Before using the code, make sure you have the following prerequisites:

- Python 3.x
- Hugging Face Transformers library
- NLTK library for part-of-speech tagging

You can install the required libraries by running:

```bash
pip install transformers nltk
```

Additionally, you will need to download the NLTK part-of-speech tagger data. You can do this by running the following Python code within your Python environment:

```python
import nltk
nltk.download('averaged_perceptron_tagger')
```

## Installation

1. Clone or download the code from this repository.
2. Install the required libraries as mentioned in the prerequisites section.

## Usage

You can use this code to translate English sentences to Hinglish while preserving nouns. Follow these steps to use the code:

1. Modify the `input_text` list with your own English sentences that you want to translate while preserving nouns.

2. Run the Python script:

```bash
python translate_and_preserve_nouns.py
```

3. The translated sentences will be printed to the console.

## Sample Input

Here is an example of the input sentences that you can use:

```python
input_text = [
    "Definitely share your feedback in the comment section.",
    "So even if it's a big video, I will clearly mention all the products.",
    "I was waiting for my bag."
]
```

## Output

![image](https://github.com/Chethan-Aditya/ENGLISH---HINGLISH-TRANSFORMATION-/assets/98507432/841b6c58-d235-4902-93c5-bfc89929991b)



```

You can create a new README.md file in your GitHub repository and paste this content into it. Customize it as needed to fit the specifics of your project and repository.
