# 🚢 Prodigy Data Science Internship - Task 02

## 📌 Task
Perform **data cleaning** and **exploratory data analysis (EDA)** on a dataset of choice.  
For this task, the **Titanic dataset** from Kaggle/Prodigy datasets was used.

---

## 🛠️ Steps Performed
### 1. Data Cleaning
- Filled missing values in **Age** with the median.  
- Filled missing values in **Embarked** with the mode.  
- Dropped **Cabin** column due to excessive missing values.  
- Removed duplicate rows.  

### 2. Exploratory Data Analysis
Created visualizations to understand survival patterns:
- **Survival by Gender**  
- **Survival by Passenger Class (Pclass)**  
- **Age Distribution of Passengers**  
- **Fare Distribution by Class and Survival**  
- **Correlation Heatmap of Numerical Features**  
- **Survival by Embarkation Port (C, Q, S)**  

---

## 📊 Visualizations

### 🔹 Correlation Heatmap
![Heatmap](screenshots/Numeric%20Features.png)

### 🔹 Survival by Gender
![Gender vs Survival](screenshots/Survival%20Count%20by%20Gender.png)

### 🔹 Survival by Passenger Class
![Class vs Survival](screenshots/Survival%20Count%20by%20Passenger%20Class.png)

### 🔹 Age Distribution
![Age Distribution](screenshots/Age%20Distribution%20of%20Passengers.png)

---

## 📝 Insights
- **Women and children** had higher survival rates.  
- **First-class** passengers had better survival chances than second and third class.  
- **Younger passengers** had slightly better chances of survival.  
- **Fare** was positively correlated with survival → wealthier passengers survived more.  
- Passengers from **Embarked = C** port had higher survival rates compared to others.  

---

## ✅ Conclusion
Survival on the Titanic was **not random**.  
It was strongly influenced by **gender, passenger class, age, and fare**.  

This supports the historical account of **“women and children first”**, and also highlights the role of **social and economic status** in survival chances.  

---

## 📂 Dataset
Dataset used: [Titanic Dataset](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202)

---

## 👨‍💻 Author
**Tamilarasan K**  
Prodigy InfoTech – Data Science Internship (Task-02)
