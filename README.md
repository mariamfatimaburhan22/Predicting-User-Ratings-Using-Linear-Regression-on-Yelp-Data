# ⭐ Predicting User Ratings Using Linear Regression on Yelp Data

## 📊 Project Overview
This project uses a subset of the **Yelp Dataset** to build a **linear regression model** that predicts user ratings for businesses based on various features. By applying data cleaning, preprocessing, outlier removal, and feature selection techniques, we aim to improve model performance and provide useful insights for businesses.

---

## 🎯 Objective
- Clean and preprocess the Yelp dataset  
- Remove irrelevant data and outliers  
- Apply **linear regression** to model the relationship between features and user ratings  
- Investigate how **feature selection** and different **train/test splits** affect model performance  
- Provide insights into user behavior and business ratings to support data-driven decisions

---

## 🧾 Dataset Summary
- **Source:** Yelp Open Dataset (subset used)
- **Target Variable:** User rating (1–5 stars)
- **Feature Examples:**
  - Business type  
  - Number of reviews  
  - Average check-in frequency  
  - Location-based variables  
  - Categorical & numeric user/business metadata

---

## ⚙️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn (LinearRegression, train_test_split, metrics)  
- Seaborn & Matplotlib (data visualization)  
- Jupyter Notebook

---

## 🧠 Methodology
1. **Data Cleaning**
   - Removed nulls and inconsistent records  
   - Filtered out irrelevant features

2. **Outlier Detection**
   - Applied statistical methods to detect and remove outliers

3. **Feature Selection**
   - Tested performance with different subsets of features  
   - Analyzed feature importance based on correlation and model weights

4. **Model Training**
   - Built a Linear Regression model  
   - Evaluated using different train/test split ratios (e.g., 80/20, 70/30)

5. **Model Evaluation**
   - Evaluated using metrics such as:
     - Mean Squared Error (MSE)  
     - R² score  
     - Mean Absolute Error (MAE)

---

## 📈 Key Insights
- Business characteristics like category, review count, and location have noticeable impact on user ratings  
- Outlier removal significantly improved prediction accuracy  
- Training/testing data split ratios affected model generalization ability

---

