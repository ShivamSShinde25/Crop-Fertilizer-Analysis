# Crop and Fertilizer Analysis

## About
This repository contains two notebooks
related to crop and fertilizer analysis
using Machine Learning.

---

## Notebook 1 - Fertilizer Usage Prediction

### Problem
Predict how much fertilizer is needed
based on soil and crop conditions.

### Type
Regression Problem

### Dataset
- 4513 records
- Features: District, Soil Color,
  Nitrogen, Phosphorus, Potassium,
  pH, Rainfall, Temperature

### Models Used
- Linear Regression
- Random Forest Regressor

### Results
| Model             | R2 Score |
|-------------------|----------|
| Linear Regression | 0.89     |
| Random Forest     | 0.87     |

---

## Notebook 2 - Crop Recommendation

### Problem
Predict which crop should be grown
based on soil and weather conditions.

### Type
Classification Problem

### Dataset
- Same dataset as Notebook 1
- Target: Crop column
- 16 different crop classes

### Models Used
- Logistic Regression
- Random Forest Classifier

### Results
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 85.60%   |
| Random Forest       | 99.88%   |

---

## Libraries Used
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How To Run
1. Open any notebook in Google Colab
2. Upload Crop_and_fertilizer_with_usage.csv
3. Run all cells in order
