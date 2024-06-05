# NormaLex

## Text Normalization Project

## Description

NormaLex project contains several text normalization and cleaning functions and classes written in Python. 
The goal of this project is to provide a set of tools for cleaning and normalizing text data, which is a crucial step in many Natural Language Processing tasks.

## Features

- Text cleaning: Remove unnecessary characters, symbols, numbers, etc.
- Text normalization: Convert html text or xml text into a standard format.
- Customizable: Easily extend the existing classes and functions to suit your needs.

## Installation

To install the necessary dependencies for this project, run the following command:

```bash
pip install -r requirements.txt
```
## Usage

Import the necessary functions or classes from the project and use them to clean and normalize your text data. 
For example:

```
from text_normalization import TextNormalizer

tn = TextNormalizer()
clean_text = tn.clean("///1234é"à'ç'some random text(....")
normalized_text = tn.normalize(clean_text)

```

## Contributing

Contributions are welcome! 
