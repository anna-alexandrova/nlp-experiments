# Siamese LSTM for Cross-Lingual Subtitle Similarity

This project implements a Siamese LSTM network to model cross-linguistic semantic similarity between subtitle segments using the ParTy (Parallel Typology Corpus).

## Data Source

The experiments are based on the ParTy corpus developed by [Natalia Levshina](https://github.com/levshina) (@levshina).

Levshina, Natalia. 2016. *Verbs of letting in Germanic and Romance languages: A quantitative investigation based on a parallel corpus of film subtitles*. Languages in Contrast 16(1): 84–117.

## Goal

To predict whether two subtitle segments in different languages express equivalent semantic content.

## Disclaimer

This repository contains a research-oriented prototype for cross-linguistic semantic similarity based on a Siamese LSTM architecture.

The implementation is designed for experimentation and methodological exploration. In particular:

- The model has not been systematically benchmarked against state-of-the-art multilingual transformer models.
- Hyperparameter tuning is limited and not optimized for maximal performance.
- Training and evaluation are conducted on a subset of available language pairs.
- Scalability, memory efficiency, and deployment aspects have not been engineered for large-scale or real-time applications.
- No formal error analysis across all 42 target languages is provided.

This code should therefore be considered a proof-of-concept rather than a production-ready system.

## Environment

This notebook is designed to be run on Google Colab.
