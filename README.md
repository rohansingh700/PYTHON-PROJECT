# 🍷 Wine Quality Analysis Project

## 📌 Project Overview

This project focuses on analyzing the quality of red wine using exploratory data analysis (EDA). The dataset contains physicochemical properties of wine such as acidity, alcohol, pH, and more, which are used to understand patterns affecting wine quality.

The goal is to:

* Explore the dataset
* Identify relationships between features
* Visualize patterns impacting wine quality

---

## 📂 Dataset

* Dataset used: **Wine Quality (Red Wine) Dataset**
* Format: CSV
* Features include:

  * Fixed acidity
  * Volatile acidity
  * Citric acid
  * Residual sugar
  * Chlorides
  * Free sulfur dioxide
  * Total sulfur dioxide
  * Density
  * pH
  * Sulphates
  * Alcohol
  * Quality (target variable)

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Steps Performed

### 1. Data Loading

* Imported dataset using Pandas
* Checked shape and structure of data

### 2. Data Exploration

* Used `.info()` and `.describe()` for understanding data
* Checked for missing values
* Analyzed unique values and distributions

### 3. Data Visualization

Various visualizations were created to understand relationships:

* 📊 Bar Plot → Distribution of wine quality
* 🐝 Swarm Plot → Quality vs Alcohol
* 🎻 Violin Plot → Alcohol distribution across quality
* 📦 Box Plot → Outlier detection
* 🔥 Heatmap → Feature correlations
* 📈 ECDF Plot → Alcohol distribution
* 📉 Joint Plot → Residual sugar relationship

---

## 📊 Key Insights

* Alcohol content has a strong relationship with wine quality
* Certain chemical properties like citric acid and chlorides influence quality
* Correlation heatmap helps identify important features
* Distribution of quality is imbalanced

---

## ▶️ How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/wine-quality-analysis.git
```

2. Navigate to the project folder:

```bash
cd wine-quality-analysis
```

3. Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn
```

4. Run the notebook:

```bash
jupyter notebook wine.ipynb
```

---

## 📁 Project Structure

```
wine-quality-analysis/
│
├── wine.ipynb
├── winequality-red.csv
└── README.md
```

---

## 🚀 Future Improvements

* Apply machine learning models for prediction
* Perform feature engineering
* Handle class imbalance
* Deploy as a web app

---

## 🤝 Contributing

Feel free to fork this repository and improve the project. Contributions are always welcome!

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgment

Dataset sourced from public wine quality datasets for educational purposes.

---
