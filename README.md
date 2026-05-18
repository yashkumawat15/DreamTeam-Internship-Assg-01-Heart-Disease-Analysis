# 🫀 Heart Disease Analysis-Assignment 1


## 📌 Overview


An exploratory data analysis (EDA) project on the **Cleveland Heart Disease dataset**, uncovering patterns and risk factors associated with heart disease through statistical summaries and visualizations.

---

## 📁 Project Structure

```
├── data.csv          # Cleveland Heart Disease dataset (294 records)
├── xyz.ipynb         # Main EDA notebook
└── README.md
```

---

## 📊 Dataset

The dataset contains **294 patient records** with the following features:

| Feature | Description |
|---|---|
| `age` | Age of the patient |
| `sex` | Sex (1 = male, 0 = female) |
| `cp` | Chest pain type (0–3) |
| `trestbps` | Resting blood pressure (mm Hg) |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| `restecg` | Resting ECG results (0–2) |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1 = yes, 0 = no) |
| `oldpeak` | ST depression induced by exercise |
| `slope` | Slope of the peak exercise ST segment |
| `ca` | Number of major vessels colored by fluoroscopy |
| `thal` | Thalassemia type |
| `num` | Target — diagnosis of heart disease (0 = no disease) |

> **Note:** Some features (`chol`, `slope`, `ca`, `thal`) contain missing values marked as `?`.

---

## 🔍 Analysis Overview

The notebook covers:

- **Data Inspection** — shape, info, descriptive statistics, null & duplicate checks
- **Univariate Analysis** — distribution of age, sex, chest pain type, and other categorical features
- **Bivariate Analysis** — count plots and box plots broken down by sex across multiple clinical features
- **Correlation Analysis** — heatmaps to identify relationships between numeric features
- **Feature Engineering** — age bucketed into groups: `Young` (18–40), `Middle` (41–52), `Senior` (53–64), `Super Senior` (65+)
- **Encoding** — one-hot encoding of `sex`, `cp`, and `age_period` for downstream modeling

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** — data manipulation
- **NumPy** — numerical operations
- **Matplotlib** — plotting
- **Seaborn** — statistical visualizations

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook xyz.ipynb
   ```

---

## 📌 Key Insights

- Age groups and sex show notable differences in chest pain type and maximum heart rate.
- Correlation heatmaps reveal meaningful relationships between `cp`, `thalach`, `exang`, and the target variable.
- Feature engineering on age improves interpretability for downstream classification tasks.

---

## 👤 Author

**Yash Kumawat**

- LinkedIn: [linkedin.com/in/your-profile](www.linkedin.com/in/yash-kumawat-02559629a)
- GitHub: [github.com/your-username](https://github.com/yashkumawat15)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
