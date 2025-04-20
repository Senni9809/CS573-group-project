CS573 Group Project: Traditional ML Model for Stress Detection
This repository contains the results and code for our group's CS573 project.
We focus on traditional machine learning models using multimodal wrist biosignals (ACC, EDA, TEMP, BVP) from the WESAD dataset to detect stress.

📂 Files
TranditionalML_model.pdf
→ Summary of preprocessing, EDA, model performance, and experiments.

tranditionalml_model.py
→ Code for training and evaluating Random Forest and XGBoost models.

tranditionalml_preprocessing.py
→ Code for preprocessing the WESAD dataset (signal normalization, segmentation, label mapping).

📝 Quick Summary
Achieved high performance:

Random Forest: 97.55% accuracy, 0.9971 ROC-AUC

XGBoost: 95.76% accuracy, 0.9905 ROC-AUC

Preprocessing included Z-score normalization and sliding window segmentation (160 samples).

Multimodal signals significantly improved performance compared to using EDA alone.

📌 Notes
Please refer to TranditionalML_model.pdf for detailed analysis and experimental results.

This repository serves as a basis for our group’s final project integration.

