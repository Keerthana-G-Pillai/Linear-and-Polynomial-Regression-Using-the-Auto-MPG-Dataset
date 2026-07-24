# 📈 Experiment 02 — Linear & Polynomial Regression

> **Course:** Machine Learning Lab  
> **Dataset:** Auto MPG (Seaborn)

---

## 🎯 Objective

Study the relationship between **Engine Displacement** and **Miles Per Gallon (MPG)** by implementing:

- 📉 Linear Regression
- 📈 Polynomial Regression (Degree 2–5)

and compare their prediction performance.

---

## 🧪 Experiment Summary

| Item | Details |
|------|---------|
| Dataset | Auto MPG |
| Samples | ~392 |
| Feature | Engine Displacement |
| Target | Miles Per Gallon (MPG) |
| Models | Linear Regression, Polynomial Regression |
| Evaluation | MSE • RMSE • R² Score |

---

## 🔬 Experiment Pipeline

```text
Auto MPG Dataset
        │
        ▼
 Remove Missing Values
        │
        ▼
 Select Feature & Target
        │
        ▼
 Train/Test Split
        │
 ┌──────┴────────┐
 ▼               ▼
Linear      Polynomial
Regression   Regression
                 │
          Degree 2 → 5
                 │
                 ▼
      MSE • RMSE • R²
                 │
                 ▼
      Performance Comparison
```

---

## 📊 Results

| Model | Degree | MSE ↓ | R² ↑ |
|------|:------:|-------:|------:|
| Linear Regression | 1 | 18.10 | 0.663 |
| Polynomial Regression | 2 | 15.10 | 0.719 |
| 🏆 Polynomial Regression | 3 | **14.94** | **0.722** |
| Polynomial Regression | 4 | 14.96 | 0.722 |
| Polynomial Regression | 5 | 15.23 | 0.717 |

---

## 📌 Key Observations

✅ Polynomial Regression models the nonlinear relationship more effectively than Linear Regression.

✅ Increasing the polynomial degree initially improves prediction accuracy.

⚠️ Higher polynomial degrees may begin to overfit the training data.

🏆 Degree **3** achieved the best overall performance in this experiment.




---

> *Sometimes the best prediction isn't a straight line.*
