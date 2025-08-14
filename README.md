

# 📊 Virtual Dashboard for Stock Prediction and Visualization

## 📌 Project Overview
This project involves the development of a **predictive model for stock prices** based on historical data, combined with an **interactive visualization dashboard**.  
The aim is to provide **accurate analysis** and actionable insights to help **stock traders, investors, and analysts** make informed decisions.

### 🔍 Detailed Process
1. **Data Acquisition**
   - Extracted a **valid list of companies** from NSE (National Stock Exchange).
   - Downloaded historical datasets for over **2,000 companies** using the `yfinance` library.

2. **Data Merging & ETL Process**
   - Merged all company datasets into a **single master dataset**.
   - Performed **ETL (Extract, Transform, Load)**:
     - Removed duplicates and unwanted data.
     - Cleaned missing values.
     - Standardized and formatted data for consistent analysis.

3. **Model Training & Prediction**
   - Trained multiple **machine learning regression models** on cleaned data.
   - Calculated **accuracy scores** to select the best-performing model.

4. **User Interaction & Investment Simulation**
   - Developed a system where users can:
     - Enter **investment amount**.
     - Select **company** from NSE list.
     - Choose an **investment period** (e.g., 1 year, 2 years).
   - The system predicts **future stock prices** and estimates **returns**.

5. **Outcome**
   - Provides **data-driven investment insights**.
   - Helps in **risk management** and **profit optimization** for traders, analysts, and investors.

---

## 🎯 Aim
To deliver **clear analysis** and **accurate predictions** that support stock traders in their decision-making.

---

## 🏷️ Category
**Machine Learning** – Prediction Model & Visualization

---

## 🛠️ Tools and Technology

### **Development Environment**
- **Hardware**: 8 GB RAM, 1 TB HDD, 256 GB SSD, Ryzen 5 (3rd Gen)
- **Operating System**: Windows 10
- **Frontend**: Tableau
- **Middleware**: Jupyter Notebook
- **Backend**: Excel, CSV

### **Technologies & Libraries**
- **Python** – Core programming language
- **Pandas** – Data manipulation & analysis
- **NumPy** – Numerical computing
- **Scikit-learn** – Machine learning algorithms
- **Tableau** – Interactive dashboard visualization
- **Jupyter Notebook** – Development & analysis environment
- **yfinance** – Stock data retrieval

---

## 📂 Modules of the System

### **1. Data Collection**
- Gather relevant data from multiple sources (datasets, CSV, Excel).
- Acquire raw data for analysis and model building.

### **2. Data Preprocessing**
- Handle missing values.
- Remove duplicates.
- Encode categorical data.
- Standardize data for better model performance.

### **3. Model Training**
Trained multiple machine learning regression models:
- **Linear Regression**
- **Decision Tree Regression**
- **Random Forest**
- **K-Nearest Neighbours (KNN)**
- **Support Vector Regressor (SVR)**
- **Adaboost Algorithm**

### **4. Prediction**
- Use trained models to predict future stock prices.
- Evaluate performance using accuracy metrics.

### **5. Visualization**
- Create interactive dashboards and graphs in Tableau.
- Visualize stock trends, patterns, and insights.

---

## 🚀 Features
- 📥 **Import Historical Stock Data** – Fetch stock market data from datasets.
- 🧹 **Data Cleaning & Preprocessing** – Ensure data quality.
- 🧠 **Train Multiple Regression Models** – Build prediction models.
- 📈 **Generate Predictions** – Forecast future prices.
- 📊 **Interactive Charts & Graphs** – Visualize insights using Tableau.
- 💰 **Investment Return Estimation** – Predict future stock prices and potential profit for given investment period & amount.

---

## 👥 Users of the System
- **Stock Traders** – Identify trends, set strategies, and improve profitability.
- **Data Analysts** – Analyze trends and improve model performance.
- **Financial Analysts** – Risk management & investment strategy building.
- **Investors** – Make data-driven buy/sell/hold decisions.

---

## 🏫 Developed At
**GLS University (FCAIT), Ahmedabad**

---

## 🎓 Guided By
**Dr. Jatin Modh** – FCAIT, Assistant Professor

---

## 📊 Example Visualizations
*(Screenshots or Tableau dashboard preview can be added here)*

---

## 📥 Installation & Usage

1. **Clone the Repository**

git clone https://github.com/raoshreepal/Stock-Price-Pridction-Project-Datascience-and-Machinelearning-.git

2. **Navigate to the Project Folder**


cd your-repo-name


3. **Install Required Python Libraries**

pip install -r requirements.txt

4. **Run the Jupyter Notebook**


jupyter notebook


5. **Open Tableau Dashboard**
   Import processed CSV files into Tableau to explore visualizations.

---

## 📄 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute with proper attribution.

---

## 📌 Note

The dataset used in this project is large and **not included in the repository** due to GitHub's 100MB file size limit.
Please download the dataset from the provided external source https://www.kaggle.com/datasets/raoshreepalkaggle/stock-privce-proidiction-with-maching-learning/.



---

