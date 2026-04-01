# Wine Quality Predictor

Neural network with linear regression output to predict the quality score of red wines.  
Built as an academic project using a real-world dataset from Kaggle.

---

## Model

- **Type:** Neural network with linear regression output
- **Task:** Predict wine quality score (continuous value)
- **Dataset:** [Red Wine Quality — UCI / Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

---

## Results

| Set        | Score  |
|------------|--------|
| Training   | 0.6979 |
| Test       | 0.5891 |

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

---

## Run locally

```bash
git clone https://github.com/SRodriguezSpina/RedNeuronal-wine-quality
cd RedNeuronal-wine-quality
pip install -r requirements.txt
```

---

## Dataset

The dataset contains physicochemical properties of red wines (acidity, sugar, pH, alcohol, etc.)  
and a quality score between 0 and 10 assigned by human tasters.

Source: [Cortez et al., 2009 — UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
