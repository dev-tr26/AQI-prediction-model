# AQI Prediction using Machine Learning Models

## 📚 Project Overview
This project aims to predict the Air Quality Index (AQI) using machine learning models. The dataset used contains AQI and weather data for Shanghai from 2014 to 2021. The models applied include:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

---

## 📂 Dataset
**Dataset Name:** `Shanghai AQI and Weather 2014-2021.csv`  
**Encoding:** `latin-1`

The dataset includes various features such as:
- Date and Time
- AQI values
- Meteorological data (temperature, humidity,windspeed,sunHour,	DewPointC, pressure etc.)

---

## 📊 Models Implemented
1. **Decision Tree**
   - Basic model with default parameters.
2. **Random Forest**
   - Hyperparameter tuning applied but no significant improvement.
3. **SVM (Support Vector Machine)**
   - Tried for classification/regression, but performance remained suboptimal.
4. **XGBoost**
   - Attempted with default and tuned parameters.

---

## 📏 Evaluation Metrics & Results
To assess model performance, the following metrics were used:

1. **R² Score (Coefficient of Determination):**  
   Measures how well the model predictions approximate the actual data. A score closer to 1 indicates a better fit.

2. **Mean Absolute Error (MAE):**  
   Measures the average magnitude of errors in predictions.

3. **Root Mean Squared Error (RMSE):**  
   Square root of MSE to provide error in the original unit.

### 📈 Model Performance Summary
| Model                  | RMSE   | MAE   | R2 Score |
|------------------------|--------|-------|----------|
| Decision Tree          | 65.46  | 54.22 | 0.2563   |
| Random Forest          | 61.68  | 50.43 | 0.34     |
| SVM                    | 64.11  | 51.27 | 0.28     |
| XGBoost                | 63.85  | 51.79 | 0.292    |
| Tuned Random Forest    |R2 score : 0.341 |
---

## 🔥 Hyperparameter Tuning
- Hyperparameters tuned for the **Random Forest model**.
- Despite efforts, the R² score did not show significant improvement.

---

## 🚀 Usage Instructions
1. Run the Jupyter Notebook:
```bash
jupyter notebook final_model.ipynb
```
## 🔎 Observations & Next Steps
- Consider data transformation and normalization to improve model performance.
- Feature selection and dimensionality reduction techniques can be explored.
- Test additional ensemble models or neural networks for better prediction.
