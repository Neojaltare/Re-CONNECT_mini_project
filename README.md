# RE_CONNECT_PROJECT

This repository contains a series of notebooks focused on **emotion classification using RoBERTa** and **unsupervised topic modeling** with the MELD dataset.

## Structure

- `fine-tuning-roberta-for-emotion-classification.ipynb`: Main notebook where RoBERTa is fine-tuned on the MELD dataset.
- `topic-modelling-meld.ipynb`: Topic modeling experiments on MELD utterances using token embeddings, BERTopic and LDA.
- `Trained_Models/`: Checkpoints saved during training (not included in GitHub for size).
- `Training_Metrics/`: Training/validation metrics collected during fine-tuning.
- `Misc_Explorations/`: Additional notebooks where I explored more options for both model finetuning and topic modelling

## Dataset

The [MELD dataset](https://affective-meld.github.io/) (Multimodal EmotionLines Dataset) is used, containing emotionally labeled dialogue utterances from Friends episodes.

## Requirements

- Python 3.8+
- PyTorch
- `transformers`
- `sklearn`
- `bertopic`
- `sentence-transformers`
