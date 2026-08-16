# Crop and Fertilizer Analysis

## About
This project has two parts:
- Predict which crop to grow
- Predict fertilizer usage needed

## Dataset
- 4513 records
- Features: Soil, NPK, pH,
  Rainfall, Temperature

## Part 1 - Fertilizer Usage Prediction
Regression problem to predict
how much fertilizer is needed

### Results
| Model             | R2 Score |
|-------------------|----------|
| Linear Regression | 0.89     |
| Random Forest     | 0.87     |

## Notebook 2 - Crop Recommendation

Classification problem to predict
which crop to grow

### Results
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 85.60%   |
| Random Forest       | 99.88%   |

## Libraries Used
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## How To Run
1. Open .ipynb in Google Colab
2. Upload dataset CSV file
3. Run all cells in order
