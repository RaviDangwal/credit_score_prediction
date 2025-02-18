# 🚀 Credit Score Prediction  
*A Machine Learning Project for Predicting Credit Scores*  

## 📌 Table of Contents  
- [Introduction](#introduction)  
- [Dataset](#dataset)  
- [Project Workflow](#project-workflow)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results and Insights](#results-and-insights)  
- [Dashboard](#dashboard)   
- [Contributors](#contributors)    

---

## 🔍 Introduction  
The **Credit Score Prediction** project aims to classify individuals' creditworthiness based on various financial and personal attributes. This model can be used by banks and financial institutions to assess risks before issuing loans.  

## 📊 Dataset  
#### The dataset used contains details about borrowers, including income, debt, past loan history, and other financial metrics.  
#### Data preprocessing steps: Handling missing values, encoding categorical features, feature scaling, etc.  
#### Dataset source: Kaggle
#### The dataset contains the following attributes:

- Age: The age of the customer
- Occupation: The customer’s occupation
- Annual_Income: The customer’s annual income
- Monthly_Inhand_Salary: The customer’s base monthly salary
- Num_Bank_Accounts: The number of bank accounts held by the customer
- Num_Credit_Card: The number of credit cards held by the customer
- Interest_Rate: The interest rate applied to the customer’s credit cards
- Num_of_Loan: The total number of loans taken by the customer
- Type_of_Loan: The types of loans taken by the customer
- Delay_from_due_date: The average number of days by which payments are delayed
- Num_of_Delayed_Payment: The number of times payments have been delayed
- Changed_Credit_Limit: The percentage change in the credit card limit
- Credit_Mix: Classification of the customer’s credit mix (e.g., credit cards, loans, mortgages)
- Outstanding_Debt: The remaining debt to be paid by the customer
- Credit_Utilization_Ratio: The utilization ratio of the customer’s credit card
- Credit_History_Age: The duration of the customer’s credit history
- Payment_of_Min_Amount: Indicates if the customer has only paid the minimum amount
- Total_EMI_per_month: The customer’s total monthly EMI payments
- Amount_invested_monthly: The customer’s monthly investments
- Payment_Behaviour: The customer's payment behavior
- Monthly_Balance: The customer's monthly balance amount
- Credit_Score: The customer’s credit score category (target variable: Poor, Standard, Good)

## ⚙️ Project Workflow  
1. **Data Collection & Preprocessing**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering & Selection**  
4. **Model Training & Evaluation**  
5. **Hyperparameter Tuning**  
6. **Deployment & Visualization**  

## 🛠️ Technologies Used  
- **Programming Language:** Python  
- **Libraries & Frameworks:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost  
- **Visualization:** Tableau Dashboard  
- **Model Deployment (if applicable):** Flask  

## 💻 Installation  
Clone this repository:  
```bash
git clone https://github.com/yourusername/credit-score-prediction.git
cd credit-score-prediction
```
Install dependencies:  
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost catboost imbalanced-learn

```
Run the project (if applicable):  
```bash
cd frontend
python main.py
```

## 🚀 Usage  
- Load the dataset  
- Train the model  
- Evaluate predictions  
- Generate insights through visualization  

## 📈 Results and Insights  
- **Accuracy achieved:** *81%*  
- **Best performing model:** *XGBoost*  

## 📊 Dashboard  
![Dashboard Preview](https://public.tableau.com/app/profile/ravi.dangwal/viz/CreditScorePrediction/Dashboard1)  
[Link to Tableau Dashboard](https://public.tableau.com/app/profile/ravi.dangwal/viz/CreditScorePrediction/Dashboard1) *(Add the link if hosted online)*  

## 🔮 Future Improvements  
- Enhancing feature selection for better accuracy  
- Deploying the model as an API  
- Integrating with a web dashboard  

## 🤝 Contributors  
👤 **Ravi Dangwal**  
📧 [ravidangwal8@gmail.com]  
🔗 [[LinkedIn Profile](https://www.linkedin.com/in/ravidangwal/)]  

---

## 🌐 Deployment on AWS  

The **Credit Score Prediction Model** is successfully **deployed on an AWS EC2 instance**, allowing users to interact with it via a web interface or API.  

### 🔗 **Live Demo** (if applicable)  
👉 **[Visit the Application](http://52.66.248.93:8000/)**  

### ⚙️ **Deployment Details**  
- **Cloud Provider:** AWS (EC2 Instance)  
- **Server Framework:** Flask  
- **Model Hosted:** Trained ML Model (Pickle)  
- **Frontend (if applicable):** HTML, CSS  
- **Backend:** Python (Flask)   

### 🚀 **How to Use the Deployed Model**  
1. Open the **[Live Link](http://your-aws-public-ip-or-domain)**.  
2. Enter the required input values (financial attributes).  
3. Click **Predict**, and the model will return a credit score classification.  
---

### 🔥 **Why AWS Deployment?**  
✅ **Scalability** – Can handle multiple user requests.  
✅ **Accessibility** – Accessible from anywhere via the internet.  
✅ **Cost-Effective** – Pay-as-you-go cloud model.  

---

### ⭐ If you found this project helpful, give it a star! ⭐  
🔗 [GitHub Repository Link](#) *(Replace with actual link)*  

---

This structure makes your README detailed, professional, and easy to navigate. Let me know if you need modifications! 🚀
