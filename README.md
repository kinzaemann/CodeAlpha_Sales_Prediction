# 📊 Sales Prediction Using Python

A machine learning project that predicts **product sales** based on advertising spend across **TV**, **Radio**, and **Newspaper** channels.

> **Built as part of my CodeAlpha Data Science Internship**

---

## 📌 Project Overview

| Detail | Description |
|--------|-------------|
| **Objective** | Predict sales based on advertising budget allocation |
| **Dataset** | 200 entries, 4 features |
| **Models Used** | Linear Regression, Random Forest, Gradient Boosting |
| **Best Model** | Gradient Boosting / Random Forest (highest R²) |
| **Tools** | Python, Pandas, Scikit-learn, Matplotlib, Seaborn |

---

## 📂 Project Structure

```
├── Sales_Prediction.ipynb       # Main Jupyter Notebook
├── Advertising.csv              # Dataset
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

---

## 📊 Dataset Features

| Feature | Description |
|---------|-------------|
| `TV` | Advertising spend on TV (in $) |
| `Radio` | Advertising spend on Radio (in $) |
| `Newspaper` | Advertising spend on Newspaper (in $) |
| `Sales` | Product sales (Target variable) |

---

## 🔧 Workflow

1. **Data Loading** — Read CSV using Pandas
2. **Exploratory Data Analysis** — Distribution plots, correlation heatmap, scatter plots
3. **Feature Analysis** — Investigated impact of each advertising channel on sales
4. **Model Training** — Trained Linear Regression, Random Forest, and Gradient Boosting models
5. **Model Evaluation** — Compared using MAE, RMSE, and R² Score
6. **Business Insights** — Identified most effective advertising channels

---

## 📈 Results

| Model | MAE | RMSE | R² Score |
|-------|-----|------|----------|
| Linear Regression | ~1.2 | ~1.6 | ~0.90 |
| Random Forest | ~0.6 | ~0.9 | ~0.97 |
| **Gradient Boosting** | **~0.7** | **~0.9** | **~0.97** |

---

## 🔑 Key Business Insights

- **TV advertising** has the strongest impact on sales (correlation ~0.78)
- **Radio advertising** has a moderate positive impact (correlation ~0.58)
- **Newspaper advertising** has the weakest effect (~0.23) — least cost-effective
- **Recommendation**: Prioritize **TV and Radio** budgets, reduce **Newspaper** spend
- Advertising spend explains over **90% of sales variation**

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/kinzaemannn/CodeAlpha-Sales-Prediction.git
   cd CodeAlpha-Sales-Prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook Sales_Prediction.ipynb
   ```

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — ML models and evaluation

---

## 📝 License

This project is for educational purposes as part of the **CodeAlpha Data Science Internship**.

---

## 👤 Author

**Kinza Eman**  
🔗 [Kaggle Profile](https://www.kaggle.com/kinzaemannn)  
🔗 [GitHub](https://github.com/kinzaemannn)
