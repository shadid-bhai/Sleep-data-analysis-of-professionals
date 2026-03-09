# Sleep Health & Lifestyle Analysis

## 📌 Executive Summary

This project explores the relationship between professional lifestyles, physical activity, and sleep quality. By analyzing a dataset of 300+ individuals across various occupations, I identified key stressors and habits that impact sleep duration and the prevalence of sleep disorders.

**The Goal:** To provide data-driven insights into how workplace stress and daily routines correlate with long-term sleep health.

---

## 📊 Key Insights

* **Occupation vs. Stress:** Software Engineers and Accountants reported higher efficiency but also higher stress levels compared to other roles.
* **Activity Impact:** A direct positive correlation was found between daily steps and sleep quality, specifically for individuals in high-stress professions.
* **Health Correlations:** BMI and Blood Pressure emerged as the strongest predictors for Sleep Apnea and Insomnia within this cohort.

---

## 🛠️ Tech Stack & Tools

* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

---

## 📂 Project Structure

```text
├── data/                   # Raw and processed CSV files
├── notebooks/              # Analysis and EDA (Jupyter Notebooks)
├── visuals/                # Exported charts and plots
├── requirements.txt        # Reproducibility dependencies
└── README.md               # Project documentation

```

---

## 🚀 Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/shadid-bhai/Sleep-data-analysis-of-professionals.git

```


2. **Install dependencies:**
```bash
pip install -r requirements.txt

```


3. **Run the analysis:**
Open `notebooks/analysis.ipynb` in Jupyter or VS Code to view the full workflow.

---

## 🔍 Methodology

1. **Data Cleaning:** Handled missing values and standardized categorical columns (e.g., merging similar job titles).
2. **EDA:** Conducted univariate and bivariate analysis to find hidden patterns between stress and sleep.
3. **Feature Engineering:** Calculated "Sleep Efficiency" metrics to better categorize rest quality.
4. **Statistical Visualization:** Used heatmaps to identify correlations and boxplots to compare sleep across different professions.

---

## 💡 Conclusion & Recommendations

Based on the data, the analysis suggests that increasing daily physical activity by even **20%** can significantly mitigate the negative impact of workplace stress on sleep duration. Future work could involve building a predictive model to identify early signs of sleep disorders based on lifestyle inputs.
