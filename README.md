# Text Summarization Project

This repository contains a project for text summarization using the Pegasus model from Hugging Face and the Samsum dataset. The project is implemented on Google Colab.

## Table of Contents

- [Text Summarization Project](#text-summarization-project)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Installation](#installation)

## Introduction

Text summarization is the process of shortening a text document to create a summary that retains the most important points of the original document. This project utilizes the Pegasus model, a state-of-the-art transformer model for abstractive text summarization, and the Samsum dataset, which contains dialogues for training and testing. The implementation is carried out using the Hugging Face Transformers library on Google Colab.

## Features

- Utilizes the Pegasus model for state-of-the-art abstractive summarization.
- Leverages the Samsum dataset for training and evaluation.
- Implemented using Hugging Face Transformers library for ease of use.
- Provided Google Colab notebook for interactive execution.

## Installation

To run this project on Google Colab, follow these steps:

1. Open the provided Google Colab notebook link.
2. Ensure you have a Google account to save a copy of the notebook.
3. Use a GPU instead of a CPU a heavy processing is needed to be performed.
4. Follow the instructions within the notebook to install the required libraries.

The necessary Python libraries include:
- `transformers`
  - `AutoTokenizer`
  - `AutoModelForSeq2SeqLM`
  - `pipeline`
- `datasets`
- `torch`
- `numpy`
- `pandas`

These can be installed within the Colab notebook using:

```python
!pip install transformers datasets torch numpy pandas
