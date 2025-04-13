# Fetal Health Classification

A machine learning project that classifies fetal health as **Normal**, **Suspect**, or **Pathological** using supervised learning algorithms applied to Cardiotocography (CTG) data.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset & Citation](#dataset--citation)  
3. [Repository Structure](#repository-structure)  
4. [Setup & Usage](#setup--usage)  
5. [Modeling Approach](#modeling-approach)  
6. [Results & Insights](#results--insights)  
7. [Technologies Used](#technologies-used)  
8. [Credits](#credits)

---

## Project Overview

The goal of this project is to use machine learning models to assist in early detection of fetal risks by analyzing CTG readings.  
By predicting fetal health status from a set of features measured during pregnancy, this model can help clinicians intervene earlier and improve prenatal outcomes.

---

## Dataset & Citation

- **Source**: [Kaggle - Fetal Health Classification Dataset](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data)  
- **License**: Not explicitly stated. Authors request proper citation.

> Ayres de Campos et al. (2000). SisPorto 2.0: A Program for Automated Analysis of Cardiotocograms.  
> *J Matern Fetal Med*, 5:311–318.

⚠️ **Note**: The dataset is not included in this repository. To run the project:
- Download the CSV from Kaggle
- Place it in the `data/` folder as `fetal_health.csv`

---

## Repository Structure

Fetal-Health-Classification/
├── data/
│   └── fetal_health.csv              # (Manually downloaded from Kaggle)
├── notebooks/
│   └── Fetal_Health_Classification.ipynb  # Main analysis notebook
└── README.md


---

## Setup & Usage

1. **Clone the Repository**
```bash
git clone https://github.com/YOUR-USERNAME/Fetal-Health-Classification.git
cd Fetal-Health-Classification
```

2. **Install Required Libraries**  
You can install packages using pip or conda. Example:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. **Download the Dataset**
Download from Kaggle and save it as:
```bash
data/fetal_health.csv
```
4. **Run the Notebook** 
Open the Jupyter Notebook inside the notebooks/ folder and run all cells to view preprocessing, modeling, and evaluation.

## Modeling Approach

The following supervised classifiers were implemented and compared:

- **K-Nearest Neighbors (KNN)**
- **Logistic Regression (Multinomial)**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**

The notebook includes steps for:

- Feature standardization  
- Train-test splitting  
- Cross-validation  
- Accuracy and classification report analysis  
- Confusion matrix visualization

---

## Results & Insights

| Model                     | Accuracy |
|--------------------------|----------|
| Random Forest            | ~95%     |
| Support Vector Machine   | ~92%     |
| Logistic Regression      | ~88%     |
| K-Nearest Neighbors      | ~85%     |

- **Random Forest** achieved the highest accuracy and performed well across all classes.
- **SVM** provided competitive results, particularly on borderline cases.
- **KNN** and **Logistic Regression** were slightly less effective but useful as benchmarks.

---

## Technologies Used

- **Python 3.x**
- **pandas**, **numpy**
- **scikit-learn**
- **matplotlib**, **seaborn**
- **Jupyter Notebook**

---

## Credits

- **Team**: Dhwani Muni, Linda Tom, Manasvi Surasani, Nayanika Bobbili, Prakruthi Shivakumar, Ashwin Balaji
- **Data**: Ayres de Campos et al. (2000) – CTG dataset from Kaggle
- **Purpose**: Demonstrate practical application of ML classification for healthcare risk prediction

---

**Thank you for exploring this project!**
