# 📘 Machine Learning Algorithms Explained

A comprehensive and hands-on guide to understanding core machine learning algorithms. This project includes:

- ✅ Exploratory Data Analysis (EDA)
- ✅ Machine Learning models implemented **from scratch** (using NumPy)
- ✅ Equivalent implementation using **Scikit-Learn**
- ✅ Evaluation metrics and visualizations
- ✅ Clean, modular code for learning and reuse


## 📂 Project Structure

ml-algorithms-explained/
│
├── datasets/             # Raw datasets used in EDA and ML
├── eda/                  # Jupyter notebooks for EDA
├── notebooks/            # ML algorithm notebooks (scratch + sklearn)
├── src/                  # Python scripts with algorithm implementations
├── utils/                # Reusable helper functions (metrics, plots, etc.)
├── environment.yml       # Conda environment file
└── README.md             # This file


## 📊 Exploratory Data Analysis (EDA)

Before applying ML, each dataset undergoes detailed EDA:

- ✅ Missing value treatment
- ✅ Univariate & bivariate analysis
- ✅ Correlation heatmaps
- ✅ Class balance and data distributions
- ✅ Key insights and observations

| Dataset       | Status  | Use Case             |
|---------------|---------|----------------------|
| Iris          | ✅ Done | Classification       |
| Titanic       | 🔄 WIP  | Binary Classification |
| Boston Housing| 🔲 Todo | Regression           |


## 🤖 Machine Learning Algorithms Covered

| Algorithm             
|-----------------------|
| Linear Regression      
| Logistic Regression    
| K-Nearest Neighbors    
| Decision Tree
| Random Forest          
| Naive Bayes            
| Support Vector Machine 
| K-Means Clustering     
| Principal Component Analysis (PCA) 
| Gradient Descent       

---

## 🛠️ Technologies Used

- Python 3.10+
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- Conda (for virtual environment)

---

## 📦 Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/Kumbhakarn/ml-algorithms-explained.git
cd ml-algorithms-explained
````

### 2. Create & Activate Environment

```
conda env create --file environment.yml
conda activate ml-core-venv

```

### 3. Start Jupyter

```bash
jupyter notebook
```

---

## 🚀 Upcoming Additions

* [ ] Add more datasets (e.g., Wine, Diabetes)
* [ ] Automate EDA reports (with Sweetviz / Pandas Profiling)

---
