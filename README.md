# 🚢 Titanic Survival Prediction  
### CodSoft Data Science Internship – Task 1

---

## 📌 Project Description
This project focuses on predicting whether a passenger survived the Titanic disaster using machine learning techniques. It is a classic beginner-friendly data science project that demonstrates the complete workflow of data preprocessing, exploratory data analysis, model building, and evaluation.

---

## 👤 Author Information
- **Name:** Kathir S N  
- **Internship:** CodSoft  
- **Domain:** Data Science  
- **Task:** Task 1 – Titanic Survival Prediction  
- **Batch:** December B70

---

## 🎯 Objective
To build a machine learning model that predicts passenger survival based on features such as age, gender, passenger class, fare, family size, and port of embarkation.

---

## 📂 Dataset Details
- **Dataset Name:** Titanic Dataset  
- **File:** `Titanic-Dataset.csv`  
- **Format:** CSV  

### Dataset Features:
| Feature | Description |
|------|------------|
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class (1st, 2nd, 3rd) |
| Sex | Gender of passenger |
| Age | Age of passenger |
| SibSp | Siblings/Spouses aboard |
| Parch | Parents/Children aboard |
| Fare | Ticket fare |
| Embarked | Port of embarkation |

---

## 🛠️ Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn  
- **Platform:** Google Colab  

---

## 🔄 Project Workflow
1. Import required libraries  
2. Load the dataset  
3. Perform data cleaning and preprocessing  
4. Handle missing values  
5. Encode categorical variables  
6. Exploratory Data Analysis (EDA)  
7. Split data into training and testing sets  
8. Train Logistic Regression model  
9. Evaluate model performance  
10. Predict survival outcomes  

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed survival distribution  
- Compared survival rates based on:
  - Gender
  - Passenger class  
- Visualized insights using bar plots and count plots  

---

## 🤖 Machine Learning Model
- **Algorithm Used:** Logistic Regression  
- **Reason for Selection:**
  - Suitable for binary classification
  - Easy to interpret
  - Efficient for beginner-level projects  

---

## 📈 Model Evaluation
- **Evaluation Metrics:**
  - Accuracy Score
  - Classification Report
  - Confusion Matrix  

- **Model Accuracy:** ~80%

---

## ✅ Results & Conclusion
- Female passengers had a higher survival rate  
- Passengers in higher classes had better survival chances  
- Logistic Regression performed well after preprocessing  
- The model successfully predicts passenger survival  
