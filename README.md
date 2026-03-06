<h1 align='center'> 🛒 WALMART - Business Case Study 🛒 </h1>
<h2 align='center'> Confidence Interval & Central Limit Theorem </h2>
<h3 align='right'>Analysed by : <b>Ritesh Charan Raj</b></h3>

---

## 📝 Case Report

- You can access the complete Python notebook here  
➡️ **Ritesh_Walmart___Confidence_Interval_and_CLT.ipynb**

- You can access the complete case study report here  
➡️ **Ritesh_Walmart__ _Confidence_Interval_and_CLT_Colab.pdf**

---

# 📌 Business Problem

Walmart is one of the largest retail companies in the world.  
The company wants to understand **customer purchasing behaviour** across different demographics.

The key focus of this case study is to analyze **whether male and female customers spend differently** and estimate the **true population mean purchase using statistical techniques**.

---

# 🎯 Objective

The objective of this analysis is to:

- Understand customer purchase behaviour
- Perform exploratory data analysis (EDA)
- Detect and handle outliers
- Apply **Central Limit Theorem (CLT)**
- Construct **Confidence Intervals**
- Compare **purchase behaviour between male and female customers**
- Provide data-driven insights for business decisions

---

# 📊 Dataset Description

The dataset contains **550,068 transactions and 10 features** related to customer purchases. :contentReference[oaicite:1]{index=1}

| Feature | Description |
|-------|-------------|
| User_ID | Unique customer identifier |
| Product_ID | Unique product identifier |
| Gender | Gender of the customer |
| Age | Age group of customer |
| Occupation | Occupation category |
| City_Category | City type (A, B, C) |
| Stay_In_Current_City_Years | Years spent in the current city |
| Marital_Status | Marital status of the customer |
| Product_Category | Product category |
| Purchase | Purchase amount |

---

# 🔎 Analysis Performed

### 1️⃣ Data Cleaning
- Checked missing values
- Checked duplicate records
- Converted categorical variables
- Verified dataset structure

### 2️⃣ Outlier Detection
- Used **IQR method**
- Visualized using **boxplots**
- Identified extreme purchase values

### 3️⃣ Univariate Analysis
- Age distribution
- Occupation distribution
- City category distribution
- Marital status comparison

### 4️⃣ Bivariate Analysis
- Gender vs Age
- Gender vs Occupation
- Gender vs City Category
- Gender vs Product Category

### 5️⃣ Statistical Analysis
- Applied **Central Limit Theorem**
- Built **sampling distributions**
- Calculated **confidence intervals**
- Compared male vs female average purchases

---

# 📈 Key Insights

- **Age group 26–35** has the highest number of purchases.
- **City Category B** customers contribute the most purchases.
- **Single customers** tend to make more purchases than married customers.
- **Product Category 1 and 5** contribute significantly to overall sales.
- **Male customers show higher purchase counts compared to females** across most demographic groups. :contentReference[oaicite:2]{index=2}

---

# 🛠 Tools & Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
SciPy  

---

# 📂 Repository Structure
