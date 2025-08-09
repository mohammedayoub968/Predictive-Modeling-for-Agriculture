# Crop Type Prediction using Logistic Regression

## 📌 Project Overview
This project uses **Logistic Regression** to identify the most predictive single soil feature (`N`, `P`, `K`, `ph`) for determining crop type.  
The dataset contains soil measurements and crop labels, and the model performance is evaluated using **F1-score (weighted)**.

---

## 📂 Dataset
The dataset `soil_measures.csv` contains:
- **N**: Nitrogen content in the soil  
- **P**: Phosphorus content in the soil  
- **K**: Potassium content in the soil  
- **ph**: Soil pH level  
- **crop**: Target variable (crop type)

---

## ⚙️ Requirements
Install the required Python packages:

```bash
pip install pandas numpy scikit-learn
