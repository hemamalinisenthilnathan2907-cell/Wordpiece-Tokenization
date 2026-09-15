# WordPiece Tokenization From Scratch

## Project Overview

This project demonstrates the working of the WordPiece Tokenization algorithm from scratch using Python.

WordPiece is a subword tokenization algorithm used by BERT-family models. It uses token frequencies, pair frequencies, and WordPiece scores to select the best pair for merging.

In this project, the sample corpus contains the words:

- cat
- cats
- cat
- cap

## Objectives

- Understand the basic idea of WordPiece Tokenization
- Create initial word splits
- Calculate token frequencies
- Calculate pair frequencies
- Calculate WordPiece scores
- Find the best pair
- Merge the selected pair
- Tokenize a new word
- Convert tokens into Token IDs

## Project Structure

```text
Wordpiece-Tokenization/
│
├── Corpus.txt
├── README.md
└── WordPiece_Tokenization.ipynb
