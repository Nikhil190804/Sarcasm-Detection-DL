# Multimodal Sarcasm Detection: Machine Learning and Deep Learning Techniques

## Overview
This project explores sarcasm detection using both **Machine Learning (ML)** and **Deep Learning (DL)** techniques. The focus is on combining multiple modalities of input data, including **audio**, **text**, and **speaker information**, to detect sarcasm in conversations. The goal is to build an effective model that can detect sarcasm using various machine learning and deep learning algorithms.

## Key Features
- **Multimodal Approach**: Utilizes both audio and textual data for sarcasm detection.
- **Classical ML Models**: Logistic Regression, Random Forest, SVM, Decision Trees, MLP.
- **Deep Learning Models**: CNN, RNN, LSTM with varying architectures.
- **Speaker Information**: The dataset includes data on the speaker’s identity, providing additional context for detecting sarcasm.
- **Contextual Understanding**: The dataset splits data into 'context' and 'utterance' for better sarcasm analysis.

## Dataset
The project uses the **Mustard++** dataset, which includes video clips from TV shows like **Friends**, **The Big Bang Theory**, and **The Golden Girls**. The dataset includes the following:
- **Textual Modality**: Transcripts of dialogues.
- **Audio Modality**: Audio files from video clips converted to spectrograms.
- **Speaker Information**: Identifies the speaker of each line.
- **Context and Utterance**: Two segments for each sample, one for the context (previous lines) and one for the current utterance.

The dataset is balanced with 601 samples per class (sarcasm present and sarcasm absent).

