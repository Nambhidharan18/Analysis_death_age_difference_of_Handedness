# Analysis Death Age Difference of Handedness

## 📌 Project Overview

This project analyzes the relationship between **handedness and age at death** using historical left-handedness and mortality datasets. The analysis uses probability and statistical methods to estimate whether left-handed and right-handed individuals have different average ages at death.

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** – Data loading, cleaning, and manipulation
* **NumPy** – Numerical and probability calculations
* **Matplotlib** – Data visualization
* **Conditional Probability & Bayes' Theorem** – Statistical analysis

## 📊 Analysis Performed

The project includes:

1. Analyzing left-handedness rates across different age groups and genders.
2. Calculating **birth years** and average left-handedness rates.
3. Estimating the probability of being left-handed given age.
4. Analyzing the distribution of deaths by age.
5. Calculating conditional probabilities of age at death given handedness.
6. Comparing the estimated average age at death for left-handed and right-handed individuals.
7. Repeating the analysis using **1990 and 2018** as study years.

## 📈 Key Results

| Study Year | Left-Handed Average Age | Right-Handed Average Age | Difference |
| ---------- | ----------------------- | ------------------------ | ---------- |
| 1990       | 71.37 years             | 73.59 years              | 2.22 years |
| 2018       | 72.96 years             | 73.46 years              | 0.50 years |

The analysis shows that the estimated difference in average age at death decreases substantially from **2.22 years in 1990 to 0.50 years in 2018**.

## 📉 Visualizations

The project generates visualizations for:

* Left-handedness by age and gender
* Mean left-handedness by birth year
* Death distribution by age
* Conditional age-at-death distributions for left- and right-handed individuals

## 📂 Dataset

The project uses two publicly available datasets:

* Left-handedness by age and gender
* U.S. mortality/death distribution by age

The datasets are loaded directly from their respective online CSV/TSV sources using Pandas.

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <project-folder>
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib
```

### 3. Run the Python script

```bash
python main.py
```

Make sure you have an active internet connection because the datasets are loaded directly from online sources.

## 💡 Conclusion

This project demonstrates how **data analysis, visualization, and probability theory** can be combined to investigate relationships within real-world datasets. The results suggest that the estimated lifespan difference associated with handedness becomes much smaller when modeled using the 2018 study year.

## 👨‍💻 Skills Demonstrated

**Python | Data Analysis | Data Cleaning | Data Visualization | Statistical Analysis | Probability | Conditional Probability | Bayes' Theorem | Pandas | NumPy | Matplotlib**
