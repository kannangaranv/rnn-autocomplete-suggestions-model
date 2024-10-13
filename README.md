# RNN-Based Autocomplete Suggestions

This project implements a Recurrent Neural Network (RNN) model to provide autocompletion suggestions for partially typed words. By inputting the initial 3-4 letters of a word (e.g., "univ"), the model predicts possible completions such as "university" or "universal."

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Autocomplete functionality enhances user experience in applications requiring text input. This project focuses on building an RNN model that suggests possible word completions based on a given prefix.

## Features

- **RNN Implementation:** Custom implementation of an RNN model using PyTorch.
- **Dynamic Suggestions:** Provides word completions based on 3-4 initial letters.
- **Training on Vocabulary:** The model is trained on a set of 10,000 common English words.

## Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib

## Dataset

The model is trained using a dataset of 10,000 common English words located in the file `wordlist.txt`. This file serves as the vocabulary for autocompletion.

## Installation

To set up the project, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/rnn-autocomplete-suggestions.git
cd rnn-autocomplete-suggestions
pip install torch numpy matplotlib
