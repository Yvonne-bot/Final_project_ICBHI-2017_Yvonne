
This repository contains the implementation of my MSc Data Science final project:
“Attention-Based CNN-LSTM for Respiratory Sound Classification: Enhancing Robustness with Data Augmentation and Model Explainability.”

The project explores deep learning architectures for classifying respiratory cycles (normal, crackle, wheeze, both) using the ICBHI 2017 Respiratory Sound Database. 

It integrates data augmentation, class imbalance handling, and explainability techniques to improve robustness and transparency.

Models Implemented:

1. Baseline MLP (with MFCC features)

2. CNN (with log-mel spectrograms)

3. CNN-LSTM Hybrid

4. CNN-LSTM-Attention Hybrid

      -Weighted

       -Tuned

       -Augmented + Tuned + Weighted (final model)

Evaluation Metrics

1. Accuracy

2. Precision, Recall, F1-score (per-class and macro)

3. ROC and AUC

4. Confusion Matrices

The final model integrates Local Interpretable Model-agnostic Explanations (LIME) to provide transparent, localised insights into which time-frequency regions 
influenced predictions.

