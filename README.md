# Netflix Data Analysis 📺

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Netflix Movies and TV Shows to uncover trends, patterns, and insights related to content type, genres, countries, release years, and ratings.

---

## 📂 Dataset

* **Source:** Kaggle
* **File:** [Dataset download](https://raw.githubusercontent.com/NAT12SHOZ/NETFLIX_PYTHON/main/Netflix_dataset.csv
)
  

Place the dataset inside the `data/` folder:

```
Netflix-Data-Analysis/
│
├── data/
│   └── netflix_titles.csv
├── netflix_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## 🛠 Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔍 Key Questions Answered

* Comparison between Movies vs TV Shows on Netflix?
* Which countries produce the most content?
* What are the most common genres?
* How has Netflix content grown over the years?
* Which ratings are most frequent?

---

## 📊 Sample Analysis Code

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load dataset
df = pd.read_csv('data/Netflix_dataset.csv')

# Basic info
print(df.shape)
print(df.columns)

# Movies vs TV Shows
df['type'].value_counts().plot(kind='bar', title='Movies vs TV Shows')
plt.show()
```

---

## 📈 Insights

* Netflix has **more movies than TV shows**.
* Content production increased rapidly after **2015**.
* The **USA and India** are top content-producing countries.
* Drama and International content dominate the platform.

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook netflix_analysis.ipynb
```

---

## 📌 Author

**Natisha Sameer**


