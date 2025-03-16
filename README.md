# 📊 **Customer Churn Analysis**  

**A data-driven approach to predicting customer churn using a Telco dataset.**  
This project covers **data exploration, preprocessing, visualization, feature engineering, and machine learning (Random Forest) for churn prediction.**  

---

## 🔍 **Project Overview**  
Customer churn analysis helps businesses understand why customers leave and take proactive measures.  
This project:  
✔️ Loads and explores the dataset 📂  
✔️ Cleans and preprocesses data 🛠️  
✔️ Visualizes key insights 📊  
✔️ Implements a **Random Forest model** 🌲  
✔️ Evaluates performance using **classification metrics** 🎯  

---

## 🛠 **Tech Stack**  
- **Python** 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning:** Random Forest Classifier  
- **Data Visualization:** Seaborn, Matplotlib  

---

## 📂 **Project Structure**  
```
/Customer_Churn_Analysis
  ├── data/               # Dataset files
  ├── notebooks/          # Jupyter notebooks for EDA & modeling
  ├── models/             # Saved machine learning models
  ├── src/                # Scripts for data preprocessing & training
  ├── results/            # Model evaluation reports & plots
  ├── README.md           # Project documentation
  ├── requirements.txt    # Dependencies
```

---

## 🚀 **Installation & Setup**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/Customer_Churn_Analysis.git
cd Customer_Churn_Analysis
```

### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3️⃣ Run Jupyter Notebook**  
```bash
jupyter notebook
```
Open **`Customer_Churn_Analysis.ipynb`** to explore the project.  

---

## 📊 **Data Analysis & Preprocessing**  
1️⃣ **Load & Explore Data** 📂  
- Load the Telco dataset and check for missing values.  
- Understand churn distribution and customer demographics.  

2️⃣ **Data Cleaning & Preprocessing** 🛠️  
- Handle missing values.  
- Encode categorical variables (e.g., gender, contract type).  
- Scale numerical features (e.g., monthly charges, tenure).  

3️⃣ **Visualization** 📊  
- Churn vs. Monthly Charges  
- Churn vs. Contract Type  
- Correlation heatmap  

4️⃣ **Feature Engineering**  
- Select important features using feature importance scores.  
- Prepare training and testing datasets.  

---

## 🌲 **Machine Learning Model**  

### **Random Forest for Churn Prediction**  
✔ **Splits data into training & testing sets**  
✔ **Trains a Random Forest classifier**  
✔ **Predicts customer churn**  
✔ **Evaluates using accuracy, precision, recall, F1-score**  

### **Model Evaluation**  
- **Confusion Matrix**  
- **ROC-AUC Score**  
- **Precision-Recall Curve**  

---

## 📈 **Results & Insights**  
✅ **Feature Importance:**  
- **Contract type, tenure, and monthly charges** strongly influence churn.  
✅ **Model Accuracy:** ~85%  
✅ **Business Insight:**  
- Customers with **month-to-month contracts** are more likely to churn.  
- Higher **monthly charges** increase churn probability.  

---

## 👨‍💻 **Contributors**  
**Bishal Jaysawal** - [GitHub Profile](https://github.com/Bishaljay)  
