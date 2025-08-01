# 🧠 Predicting Life Satisfaction with Machine Learning

This project applies machine learning techniques to predict a country’s **Life Ladder** score (a measure of life satisfaction) using features from the **World Happiness Report (WHR)** dataset. The goal is to understand which factors most influence subjective well-being and build a model that can generalize well to new data.

---

## 📊 Dataset

The dataset is derived from the [World Happiness Report](https://worldhappiness.report/) and includes country-level data on:

- Social support  
- Healthy life expectancy  
- Freedom to make life choices  
- Generosity  
- Perceptions of corruption  
- Confidence in national government  
- Democratic and delivery quality  
- GINI index and income inequality measures  
- Positive/Negative emotions and more  

**Target Variable**:  
`Life Ladder` – a self-reported measure of life satisfaction on a scale from 0 to 10.

---

## 🛠️ Features Used

Key features selected for modeling include:

- Social support  
- Healthy life expectancy at birth  
- Freedom to make life choices  
- Perceptions of corruption  
- Confidence in national government  
- Positive/Negative affect  
- Several inequality indicators like GINI index, etc.

---

## 🧪 ML Pipeline

### ✅ 1. Data Preparation

- Handled missing values  
- Encoded categorical variables (e.g., country)  
- Split data into training and testing sets  

### 🌲 2. Model Training

- Used Random Forest Regressor  
- Tuned hyperparameters with `GridSearchCV`  
- Visualized feature importances to understand key predictors  

### 📈 3. Evaluation

- Metrics used: `R² score`, `MAE`, `RMSE`  
- Plotted predictions vs. actual values  
- Performed feature selection to improve generalization  

---

## 🔍 Results

The optimized Random Forest model achieved:

- ✅ High R² score on the test set  
- ✅ Low RMSE, indicating accurate life satisfaction predictions  

---

## 🚀 How to Run

1. Clone this repo:

```bash
git clone https://github.com/yourusername/life-satisfaction-predictor.git
```

2. Open the notebook:

```bash
jupyter notebook notebook.ipynb
```

3. Run all cells to see results and visualizations.

---

Feel free to ⭐ the repo or open an issue if you have questions!
