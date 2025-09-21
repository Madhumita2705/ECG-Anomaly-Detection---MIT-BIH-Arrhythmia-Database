ECG Arrhythmia Classification – MIT-BIH Dataset
**Overview**

This repository contains a stack of projects on ECG arrhythmia detection using the MIT-BIH Arrhythmia Database. The work progresses through multiple phases, starting with beat-level classification and extending into feature engineering, sequence modeling, and explainable AI.


**📂 Dataset**

We use the MIT-BIH Arrhythmia Database available on PhysioNet:
🔗 MIT-BIH Arrhythmia Database – PhysioNet


**Phase 1: Beat-Level Classification**

Challenge: Dataset was highly imbalanced (Normal beats dominated rare arrhythmia beats).

Solution: Used SMOTE oversampling to balance classes.

Model: Implemented a 1D CNN + LSTM hybrid model for beat-level classification.

Code Structure:

classification_1D CNN.ipynb - simple model with 1D CNN

classification_SMOTE_1D CNN.ipynb - model after using SMOTE on dataset

classification_SMOTE_1D CNN+LSTM.ipynb - model using SMOTE along with hybrid 1D CNN and LSTM model


**Phase 2: Feature Extraction (Classical ML)**


**Phase 3: Sequence Modeling (Rhythm Prediction)**


**Phase 4: Explainable AI**

