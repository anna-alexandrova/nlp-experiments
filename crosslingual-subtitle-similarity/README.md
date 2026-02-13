# Siamese LSTM for Cross-Lingual Subtitle Similarity

This project implements a Siamese LSTM network to model cross-linguistic semantic similarity between subtitle segments using the ParTy (Parallel Typology Corpus).

## Data Source

The project is based on the ParTy corpus developed by [Natalia Levshina](https://github.com/levshina) (@levshina).

Levshina, Natalia. 2016. *Verbs of letting in Germanic and Romance languages: A quantitative investigation based on a parallel corpus of film subtitles*. Languages in Contrast 16(1): 84–117.

## Goal

To predict whether two subtitle segments in different languages express equivalent semantic content.

## Disclaimer

This is a prototype for cross-linguistic semantic similarity based on a Siamese LSTM architecture, designed for experimentation and methodological exploration. In particular:

- The model has not been benchmarked against state-of-the-art multilingual transformer models.
- Hyperparameter tuning is limited with no optimization for maximal performance.
- Scalability, memory efficiency, and deployment aspects have not been engineered for large-scale or real-time applications.
- No formal error analysis across all 42 target languages is provided.
- The dataset would need to be significantly larger to support real-world applications.

This code should therefore be considered a simple proof of concept rather than a production-ready system.

## Environment

This notebook is designed to be run on Google Colab.
