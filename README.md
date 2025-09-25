# 🏡 Housing Price Prediction – Linear Regression  

## 📌 Overview  
This project demonstrates the implementation of **Simple & Multiple Linear Regression** using the **Housing Dataset**.  
It is part of my **AI & ML Internship – Task 3** and focuses on:  
- Understanding regression concepts  
- Building predictive models  
- Evaluating performance with standard metrics  
- Visualizing results and interpreting coefficients  

---

## 📂 Dataset  
- **File:** `Housing.csv`  
- **Description:** Contains housing features like area, number of bedrooms, bathrooms, stories, and furnishing status.  
- **Target Variable:** `price` (House Price)  

---

## ⚙️ Steps Implemented  
1. **Data Import & Preprocessing**  
   - Handling missing values  
   - Converting categorical variables  
2. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Correlation heatmap  
3. **Train-Test Split**  
4. **Model Training**  
   - Linear Regression using `scikit-learn`  
5. **Model Evaluation**  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  
6. **Visualization**  
   - Regression line plot  
   - Coefficient analysis  

---

## 📊 Sample Results  

After training the Linear Regression model:  

- **Mean Absolute Error (MAE):** `127,530.42`  
- **Mean Squared Error (MSE):** `3.54e+10`  
- **R² Score:** `0.82`  

🔎 **Interpretation:**  
- The model explains **~82% of the variance** in housing prices.  
- `area` had the strongest positive influence on price.  
- `bedrooms` and `bathrooms` also contributed positively.  
- Furnishing status had a moderate impact.  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone <your-repo-link>
   cd <repo-name>
