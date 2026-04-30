# Energy Consumption Prediction using Polynomial Regression ⚡🌡️

## 📌 Overview
This project analyzes the non-linear relationship between daily maximum temperatures (**TMAX**) and electricity consumption. While traditional linear models often fail to capture the spikes in energy demand during both extreme heat and cold, this **Polynomial Regression** model successfully maps the "U-curve" of utility demand.

## 📊 Model Performance
- **Algorithm:** Polynomial Regression
- **Degree:** 2 (Quadratic)
- **R-Squared Score:** 0.3483
- **Mean Absolute Error (MAE):** 384.33

## 💡 Key Insights
- **Temperature Correlation:** The model confirms that temperature accounts for approximately **35%** of the variance in daily energy consumption.
- **Non-Linear Trends:** The polynomial fit demonstrates that as temperatures stray from the 18°C-22°C "comfort zone," energy demand increases exponentially due to cooling/heating requirements.
- **Real-World Complexity:** An R² of 0.35 is a realistic result for environmental data, suggesting that factors like humidity, day of the week, and holiday schedules also influence the remaining 65% of the variance.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook

## 📁 Repository Structure
- `power_model.pkl`: Saved model weights for future predictions.
- `energy_plot.png`: Visualization of the actual vs. predicted consumption curve.
- `notebook.ipynb`: Full source code with data preprocessing and evaluation.

## 🚀 Future Enhancements
To improve the model's predictive power (R^2), future iterations will explore:
1. Incorporating **Precipitation (PRCP)** data.
2. Adding **Temporal Features** (Day of the week, seasonality).
3. Experimenting with **Regularization** (Ridge/Lasso) to prevent potential overfitting at higher degrees.

---
Created by Shivi Srivastava as part of a Machine Learning portfolio project.
