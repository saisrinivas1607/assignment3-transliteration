# assignment3-transliteration
Seq2Seq Transliteration using RNN LSTM GRU

Sequence-to-Sequence Learning for Transliteration

## Overview

This project implements character-level transliteration using Sequence-to-Sequence (Seq2Seq) models on the Dakshina dataset.

The assignment covers:

* Vanilla Seq2Seq Model
* Hyperparameter Tuning using WandB Sweeps
* Attention-Based Seq2Seq Model
* Connectivity Visualization using Attention
* Evaluation on Test Data

## Dataset

* Dataset: Dakshina Dataset
* Language: Telugu

## Models Implemented

### Vanilla Seq2Seq

* Encoder: GRU
* Decoder: GRU
* Embedding Size: 64
* Hidden Size: 128

### Attention Seq2Seq

* Encoder: GRU
* Decoder: GRU with Attention
* Embedding Size: 64
* Hidden Size: 128

## Hyperparameter Sweep

Hyperparameters explored:

* Cell Type: RNN, GRU, LSTM
* Embedding Size: 32, 64
* Hidden Size: 64, 128

Best Configuration:

* Cell Type: GRU
* Embedding Size: 32
* Hidden Size: 128

## WandB

Weights & Biases was used for:

* Experiment Tracking
* Hyperparameter Sweeps
* Parameter Importance Analysis
* Parallel Coordinates Visualization

## Repository Contents

* assignment3.ipynb
* README.md

## Team Members

* Sai Srinivas N
* Likhita U

