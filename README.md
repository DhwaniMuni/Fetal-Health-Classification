# Fetal Health Classification

This project classifies fetal health into **Normal**, **Suspect**, or **Pathological** using multiple machine learning algorithms: **KNN**, **Logistic Regression**, **SVM**, and **Random Forest**.

## Overview

- **Goal**: Predict fetal health status based on Cardiotocography (CTG) data.
- **Algorithms**: 
  - K-Nearest Neighbors (KNN)
  - Logistic Regression (multinomial)
  - Support Vector Machine (SVM)
  - Random Forest (ensemble approach)

## Dataset

- **Source**: [Kaggle - Fetal Health Classification Dataset](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data)
- **License**: Unspecified. The authors request that you cite:

  > Ayres de Campos et al. (2000). SisPorto 2.0: A Program for Automated Analysis of Cardiotocograms.  
  > *J Matern Fetal Med,* 5:311–318.

### Important

Because the license is not explicitly stated, I am **not including the CSV** file in this repository.  
- If you'd like to reproduce this project, **please download** the CSV from Kaggle and place it in a `data/` folder with the name `fetal_health.csv`.

## How to Use

1. **Clone or Download** this repository (green “Code” button → “Download ZIP”).
2. **Download the dataset** from Kaggle ([link](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data)) and place the file in: data/fetal_health.csv

3. **Open the Jupyter Notebook** in `notebooks/` to see the code and run the analysis.
4. Make sure you have the necessary Python libraries installed (e.g. `pandas`, `numpy`, `scikit-learn`, `matplotlib`, etc.).

## Results (Short Summary)

- **Random Forest** generally had the best accuracy (roughly 94–95%).
- **SVM** also performed strongly.
- **Logistic Regression** and **KNN** had good but slightly lower performance.

## Citation and Credits

- **Dataset**: Please cite the original dataset authors:
> Ayres de Campos et al. (2000). SisPorto 2.0: A Program for Automated Analysis of Cardiotocograms.  
> *J Matern Fetal Med,* 5:311–318.

---

**Thank you for checking out this project!** 
