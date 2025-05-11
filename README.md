# Diabetes EDA on Pima Indians Dataset 🧪📊

This repository contains an exploratory data analysis (EDA) of the Pima Indians Diabetes dataset. The objective of this project is to uncover insights and patterns related to diabetes based on various medical and personal attributes of female patients.

---

## 📁 Project Structure
- EDA.ipynb # Jupyter notebook for EDA.
- pima-indians-diabetes.csv # Dataset used for analysis.
- README.md # Project documentation.


---

## 📚 Dataset Description

The dataset used is the **Pima Indians Diabetes Dataset**, which contains several medical predictor variables and one target variable (`Outcome`). This dataset is often used in classification tasks to predict whether a patient has diabetes based on diagnostic measurements.

**Features:**

- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skinfold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function
- `Age`: Age (years)
- `Outcome`: Class variable (0: Non-diabetic, 1: Diabetic)

---

## 🚀 Getting Started

To run the notebook locally:

### 🔧 Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`

### Key Features
The notebook explores:

- Data cleaning and missing value handling

- Univariate and multivariate analysis

- Correlation matrix and heatmaps

- Class balance of diabetic vs non-diabetic outcomes

- Distribution of key predictors like glucose and BMI

### 📥 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/diabetes-eda-pima-indians.git
cd diabetes-eda-pima-indians

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

# Install required libraries
pip install -r requirements.txt


