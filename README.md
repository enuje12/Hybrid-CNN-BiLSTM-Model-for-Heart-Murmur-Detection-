# Hybrid CNN–BiLSTM Heart Murmur Detection

## Overview
This notebook demonstrates a research project aimed at detecting heart murmurs from audio recordings using a hybrid deep learning framework combining **CNN**, **BiLSTM**, and **attention mechanisms**.

## Main Contributions
- Developed a hybrid deep learning framework combining **CNN, BiLSTM, and attention mechanisms** for heart murmur detection.
- Achieved **91.2% accuracy**, **92.8% recall (sensitivity)**, and **0.94 ROC AUC** on the test set.
- Utilized **smartphone microphone recordings** as the data source for accessible and low-cost cardiac screening.
- Designed a preprocessing pipeline that converts raw audio into **Mel spectrogram representations**.
- Implemented **data augmentation** and **class imbalance handling** techniques (SMOTE, SpecAugment) for improved model generalization.
- Trained and evaluated the model on the **PhysioNet CirCor Phonocardiogram dataset**.
- Incorporated **attention map visualizations** to interpret which sound segments influence model predictions.
- Provided a **complete codebase** for training, evaluation, and inference to enable further research.

## NOTE
All visualizations, outputs, and results (e.g., Mel spectrograms, confusion matrix, ROC curves, and metrics report) are available in the Jupyter Notebook file (.ipynb). Please open the notebook to view them.
