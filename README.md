# 🚗 Car Price Prediction Model
[![Live Project](https://img.shields.io/badge/Live_Project-Click_Here-blue)](https://car-price-prediction-uwy6.onrender.com)

![dataset-cover](https://github.com/user-attachments/assets/8f8f4b1a-6eee-4dc5-9229-49366edb2fa9)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📄 Introduction

Accurately predicting the resale value of used cars is a real-world challenge due to varying factors such as brand, fuel type, age, mileage, etc. This project uses machine learning to estimate used car prices based on a dataset scraped from **Quikr.com**, with features like car name, company, year, kilometers driven, fuel type, and price. The final model is deployed via Flask on [Render](https://render.com).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🚙 Dataset

The dataset was originally scraped from **Quikr**, and underwent extensive cleaning and preprocessing.

**Key Features Used:**
- `name` — Car name (top 3 words of original string)
- `company` — Manufacturer (e.g. Hyundai, Maruti)
- `year` — Manufacturing year
- `Price` — Selling price (target variable)
- `kms_driven` — Kilometers driven
- `fuel_type` — Petrol, Diesel, CNG, etc.

**Steps Taken:**
- Removed rows with missing or malformed entries
- Removed "Ask for Price" entries
- Converted numerical fields to integers
- Handled outliers (e.g. cars with price > 60 lakh)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📑 Steps Involved

* Dataset Loading & Inspection
* Data Cleaning & Feature Engineering
* Outlier Removal & Normalization
* Exploratory Data Analysis using Seaborn & Matplotlib
* Model Training:
  - **Linear Regression**
  - **Lasso Regression**
  - **Random Forest Regressor**
* Model Evaluation using R² Score
* Saving Best Model with `pickle`
* Flask App Development for Model Serving
* Deployment on Render

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 💻 Approaches Used

### 📊 Data Cleaning & Analysis:
- Used pandas, numpy, seaborn, matplotlib for data wrangling and visualization
- Outlier detection using boxplots

### 🤖 Machine Learning Models:
- **Linear Regression** — Baseline model
- **Lasso Regression** — Regularized linear model
- **Random Forest Regressor** — Provided best accuracy and used for deployment

### 🌐 Web App:
- Built using **Flask**
- Users input car details to receive predicted price
- Integrated with trained model through pickle

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🔗 Deployment

This model is live and accessible at the following link:  
👉 **[Live](https://car-price-prediction-uwy6.onrender.com)**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## ✅ Conclusion

* Successfully built and deployed a machine learning model for predicting used car prices.
* The system is capable of handling user inputs from real-world car listings.
* Offers a practical and easy-to-use web interface.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📚 References

* [Quikr.com](https://www.quikr.com)
* [Scikit-learn Documentation](https://scikit-learn.org/)
* [Render Deployment](https://render.com/)

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nizaaf-dabir-524596203/)  
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NizaafDabir)
