# 📈 Linear Regression Lab

A hands-on laboratory for exploring and implementing **logistic regression** techniques using real-world datasets. This project covers the full ML workflow — from data loading and EDA to model training, evaluation, and visualization — all inside Jupyter Notebooks.

---

## 📁 Project Structure

```
linear-regression-lab/
├── notebooks/          # Jupyter notebooks with experiments
├── pyproject.toml      # Project dependencies and metadata
├── .python-version     # Python version pinning
├── .gitignore
└── README.md
```

---

## 📊 Datasets

The datasets used in this project are sourced from Kaggle. You can download them via the Kaggle API or directly from the links below.

| Dataset | Source |
|---------|--------|
| *competitions/titanic* | [Kaggle](https://www.kaggle.com/datasets) |
|---------|--------|
| *uciml/adult-census-income* | [Kaggle](https://www.kaggle.com/datasets) |

> To download datasets programmatically, make sure you have your `kaggle.json` API credentials configured:
> ```bash
> kaggle datasets download -d <dataset-owner>/<dataset-name> -p <path where data is saved> --unzip
> ```

---

## 🧰 Tech Stack

- **Python** 3.14
- **Jupyter** — interactive notebook environment
- **pandas** — data manipulation and analysis
- **NumPy** — numerical computing
- **scikit-learn** — linear regression modeling and evaluation
- **Matplotlib** & **Seaborn** — data visualization
- **Missingno** — missing data visualization
- **uv** — fast Python package manager
- **imblearn** — handling imbalanced datasets

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/aithusiast/logistic-regression-lab.git
cd logistic-regression-lab
```

### 2. Install dependencies

This project uses [`uv`](https://github.com/astral-sh/uv) for dependency management:

```bash
uv sync
```

Or with pip:

```bash
pip install -e .
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

Then open any notebook from the `notebooks/` directory.

---

## 📌 Topics Covered

- Exploratory Data Analysis (EDA)
- Handling missing values
- Feature selection and preprocessing
- Handling imbalanced datasets
- Model evaluation metrics (f1-score, accuracy, recall, precision, etc)