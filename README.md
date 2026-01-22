# Semi-Supervised Learning on Handwritten Digits

This project compares semi-supervised learning methods with a supervised baseline on the UCI Optical Recognition of Handwritten Digits dataset, focusing on performance when only a small fraction of labels is available.

## Repository contents

- semi_supervised_learning_analysi.ipynb 
  Jupyter notebook with the full implementation: data loading, PCA visualization, supervised SVM baseline, and semi-supervised methods (Self-Training and Label Propagation).

- requirements.txt
  Python dependencies needed to run the notebook:
  - scikit-learn>=1.0.0  
  - numpy>=1.20.0  
  - pandas>=1.3.0  
  - matplotlib>=3.4.0  
  - seaborn>=0.11.0  
  - ucimlrepo>=0.0.2  
  - jupyter>=1.0.0  

- Project.pdf
  Project report summarizing the experimental setup, results, and key observations.

## Project overview

The goal of this project is to study how semi-supervised learning behaves under label scarcity for a 10-class digit recognition task. The notebook:

- Loads the UCI handwritten digits dataset (8×8 images, 64 features, digits 0–9).
- Builds a supervised SVM baseline.
- Trains Self-Training and Label Propagation models on partially labeled data.
- Evaluates accuracy and macro-F1 over different label proportions.

## How to run

### Option 1 – Run in Google Colab

1. Open https://colab.research.google.com.
2. Go to the **GitHub** tab.
3. Search for Mohumeddahir/semi-supervised-digits.
4. Open semi_supervised_learning_analysi.ipynb .
5. Run all cells via **Runtime → Run all**.
