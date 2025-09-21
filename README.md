# ECG Arrhythmia Classification – MIT-BIH Dataset

## Overview
This repository contains a stack of projects on ECG arrhythmia detection using the MIT-BIH Arrhythmia Database. The work progresses through multiple phases, starting with beat-level classification and extending into feature engineering, sequence modeling, and explainable AI.

## 📂 Dataset
We use the MIT-BIH Arrhythmia Database available on PhysioNet:  
🔗 [MIT-BIH Arrhythmia Database – PhysioNet](https://physionet.org/content/mitdb/1.0.0/)

## Phase 1: Beat-Level Classification
**Challenge:** Dataset was highly imbalanced (Normal beats dominated rare arrhythmia beats).

**Solution:**
- Applied SMOTE oversampling to balance the dataset.  
- Built and compared 1D CNN baseline (with & without SMOTE) and 1D CNN + LSTM hybrid model.

**Code Structure:**
- `ecg-anomaly-detection-result-analysis.ipynb` → Comparison of all 3 approaches.  
- `classification_1D CNN.ipynb` → Simple 1D CNN model.  
- `classification_SMOTE_1D CNN.ipynb` → CNN model trained after SMOTE balancing.  
- `classification_SMOTE_1D CNN+LSTM.ipynb` → Hybrid CNN + LSTM with SMOTE.

## Phase 2: Feature Extraction (Classical ML)

## Phase 3: Sequence Modeling (Rhythm Prediction)

## Phase 4: Image-Based Representations

## Phase 5: Explainable AI
