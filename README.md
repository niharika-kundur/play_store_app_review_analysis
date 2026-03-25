# 📊 Google Play Store Data Analysis (EDA)

## 📌 Overview

Performed Exploratory Data Analysis (EDA) on Google Play Store apps and user reviews to identify key factors influencing **app engagement, ratings, and installs**.

---

## 🎯 Objective

* Analyze app performance across categories
* Identify factors affecting installs and ratings
* Understand user sentiment from reviews

---

## 📂 Datasets

* **Play Store Apps Data** (~10K apps)
* **User Reviews Data** (~64K reviews)

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy)
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 🧹 Data Cleaning

* Removed **1181 duplicate apps**
* Handled missing values (median for Rating, mode for categorical columns)
* Converted data types (Reviews, Installs, Price)
* Cleaned inconsistent formats (“10,000+”, “$”, “Varies with device”)

---

## 📊 Key Analysis

* Ratings distribution
* Category-wise app trends
* Reviews vs Installs relationship
* Free vs Paid app comparison
* User sentiment analysis

---

## 📈 Key Insights

* Most apps have ratings between **4.0 – 4.5**
* **Free apps dominate** the Play Store
* Strong correlation between **reviews and installs**
* Categories like **Game, Tools, Family** lead in installs
* Paid apps are fewer but maintain **stable ratings**
* User sentiment is largely **positive**

---

## 🚀 How to Run

```bash
git clone https://github.com/niharika-kundur/playstore-eda.git
cd playstore-eda
pip install pandas numpy matplotlib seaborn
jupyter notebook
```


## 📌 Conclusion

The analysis highlights how **data-driven insights** can help improve app performance, user engagement, and market success.

---
