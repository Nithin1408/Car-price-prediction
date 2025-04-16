# Car-price-prediction

# 🚗 Car Price Prediction using Machine Learning

This project aims to predict the selling price of used cars using various features such as age, fuel type, transmission, and ownership details. It's a supervised machine learning project using regression algorithms to provide accurate price estimates.

---

## 📌 Project Objectives

- Predict the price of a used car based on key features.
- Build and evaluate multiple machine learning regression models.
- Understand which factors most influence car prices.
- Create a reproducible pipeline for data preprocessing and model training.

---

## 📊 Dataset

The dataset contains information about used cars, including:
- Car Name
- Year of Manufacture
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner
- Selling Price (target)

---

## 🔧 Technologies Used

- Python
- Pandas & NumPy (data processing)
- Matplotlib & Seaborn (data visualization)
- Scikit-learn (model building & evaluation)
- Jupyter Notebook

---

## 🧪 Steps Performed

1. **Data Loading & Cleaning**  
   - Removed irrelevant columns  
   - Checked for null and duplicate values  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and correlations  
   - Analyzed the relationship between features and price  

3. **Feature Engineering**  
   - Converted categorical data using Label Encoding / One-Hot Encoding  
   - Created a new feature: car age  

4. **Model Building**  
   - Trained models like Linear Regression, Decision Tree, Random Forest  
   - Used R² Score and MAE to evaluate performance  

5. **Prediction & Conclusion**  
   - Identified the best-performing model  
   - Interpreted feature importance  

---

## 📈 Results

- The **Random Forest Regressor** gave the most accurate predictions.
- Important features included: **Car Age**, **Fuel Type**, and **Transmission Type**.

---

## ✅ Conclusion

This project demonstrated how machine learning can be effectively used to estimate the selling price of a used car. It involved data preprocessing, visualization, regression modeling, and evaluation. The model can be further optimized or deployed as a web app in the future.

---

## 📁 Project Structure

