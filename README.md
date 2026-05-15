# AI-Based Vertebra Metastasis Detection System

## Overview
This project presents a machine learning-based system for detecting metastasis in vertebra X-ray images. The system uses image processing and feature extraction techniques to assist in early diagnosis.

## Features
- Automated detection of vertebra abnormalities
- Feature extraction using GLCM and LBP
- Classification using Random Forest and Isolation Forest
- Heatmap-based lesion localization for better interpretability

## Technologies Used
- Python
- OpenCV
- Scikit-learn
- NumPy, Matplotlib
- GLCM (Gray-Level Co-occurrence Matrix)
- LBP (Local Binary Patterns)

## Working Pipeline
1. Input vertebra X-ray image
2. Preprocessing and normalization
3. Feature extraction (GLCM + LBP)
4. Classification using ML models
5. Output prediction with heatmap visualization

##  Results
- Achieved approximately **98% accuracy**
- Generated heatmaps highlighting affected regions

## Output Samples
(Add screenshots here)
- Original X-ray image  
- Processed image  
- Heatmap output  

##  How to Run
```bash
pip install -r requirements.txt
python main.py
