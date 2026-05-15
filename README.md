# 🧠 AI-Based Vertebra Metastasis Detection System

## 📌 Overview
This project presents a machine learning-based system for detecting metastasis in vertebra X-ray images. The system uses image processing and feature extraction techniques to assist in early diagnosis.

## 🚀 Features
- Automated detection of vertebra abnormalities
- Feature extraction using GLCM and LBP
- Classification using Random Forest and Isolation Forest
- Heatmap-based lesion localization for better interpretability

## 🧠 Technologies Used
- Python
- OpenCV
- Scikit-learn
- NumPy, Matplotlib
- GLCM (Gray-Level Co-occurrence Matrix)
- LBP (Local Binary Patterns)

## ⚙️ Working Pipeline
1. Input vertebra X-ray image
2. Preprocessing and normalization
3. Feature extraction (GLCM + LBP)
4. Classification using ML models
5. Output prediction with heatmap visualization

## 📊 Results
- Achieved approximately **98% accuracy**
- Generated heatmaps highlighting affected regions

## 📷 Output Samples
<img width="964" height="739" alt="2" src="https://github.com/user-attachments/assets/b50c6bde-34e9-48ad-bdfd-6bcab5647634" />

<img width="1111" height="788" alt="14" src="https://github.com/user-attachments/assets/7a4f31d3-01f4-4eb5-b32b-3bbf5f7f6805" />

<img width="519" height="435" alt="6" src="https://github.com/user-attachments/assets/1464b868-9beb-47e9-837d-f2489f54978a" />


## ▶️ How to Run
```bash
pip install -r requirements.txt
python main.py
