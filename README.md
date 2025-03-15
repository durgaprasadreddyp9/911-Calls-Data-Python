# 🚨 911 Calls Data Analysis

## 📌 Overview
This project analyzes **911 emergency call data** to uncover insights into **call trends, response patterns, and public safety needs**. Using **data visualization and feature engineering**, we explore key **emergency trends** across different **locations, times, and call reasons**.

### 🔹 **Key Insights & Contributions**
✅ **Top Zip Codes & Townships** for 911 calls.  
✅ **Most Common Emergency Reasons** – Fire, Traffic, EMS.  
✅ **Peak Hours & Days for Emergency Calls**.  
✅ **911 Call Trends Over Time** – Monthly, Daily, Hourly Analysis.  
✅ **Heatmaps & Clustermaps** for response pattern visualization.  

---

## 🏗 **Analysis Workflow**

### **1️⃣ Data Preparation**
- 📥 **Load Data**: Import **CSV file** into a **Pandas DataFrame**.
- 🏗 **Data Overview**: Check dataset structure, missing values, and data types.

### **2️⃣ Feature Engineering**
- Extract **Reason for Call** from the `title` column.
- Convert **timeStamp** to **DateTime format**.
- Extract **Hour, Month, and Day of Week** for trend analysis.

### **3️⃣ Exploratory Data Analysis (EDA)**
- 📌 **Top 5 Zip Codes & Townships** for 911 calls.
- 📌 **Count of Unique Title Codes**.
- 📌 **Call Frequency by Reason (Fire, EMS, Traffic).**

### **4️⃣ Data Visualization**
- 📊 **911 Calls by Reason** – `Seaborn Countplots`.
- 🗓 **Day of Week vs. Call Reason** – `Countplot`.
- 📆 **Month vs. Call Reason** – `Countplot & Linear Fit`.
- 🔥 **Heatmaps & Clustermaps** for **Call Volume vs. Time**.

---

## 📊 **Key Findings & Visualizations**

### **1️⃣ Most Common Reasons for 911 Calls**
```python
sns.countplot(x="Reason", data=df, palette="coolwarm")
