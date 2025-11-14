
## **Data Visualization & Storytelling using Coffee Shop Sales Dataset**

This repository contains my solution for **Task 2** of the **OIT / Uptricks Pvt Ltd Data Analyst Internship**.  
The objective of this task is to create meaningful data visualizations and present a simple data story using sales data.

---

# 🚀 **Task Objective**
- Create data visualizations that communicate insights clearly  
- Use any sales dataset (I used **Coffee Shop Sales.xlsx**)  
- Generate a minimum of **4 visuals** with proper storytelling  
- Submit code + visuals + README on GitHub  

---

# 🛠 **Tools & Technologies Used**
- **Google Colab** for executing Python code  
- **Python** for data processing  
- **Pandas** for data cleaning  
- **Plotly Express** for creating interactive charts  
- **Excel Dataset**: *Coffee Shop Sales.xlsx*

---

# 📂 **Dataset Overview**
The dataset contains transaction–level coffee shop sales data with information like:
- Transaction Date  
- Product Category  
- Product Name  
- Store Location  
- Sales Amount  

Some columns differ between versions, so I used **automatic column detection** to prevent errors.

---

# 📈 **Generated Visualizations**
I created the following **4 visualizations**, as required by the task:

### **1️⃣ Monthly Sales Trend**
A line chart showing how revenue changes month by month.  
Helps to identify high-performing months and seasonal demand.

### **2️⃣ Sales by Category**
A bar chart showing revenue distribution across product categories  
(e.g., Coffee, Tea, Bakery, Pastries, Drinks).

### **3️⃣ Top 15 Best-Selling Products**
A ranking chart of the highest revenue–generating products.  
Useful for inventory decisions and promotions.

### **4️⃣ Sales by Store Location**
Shows how different store locations perform in terms of revenue.  
Useful for identifying profitable branches.



# 📜 **Code Explanation**
The Python notebook includes:
- Automatic detection of **date**, **sales**, **category**, **product**, and **store** columns  
- Date conversion and monthly grouping  
- Clean and easy-to-understand visualizations  
- Output saved inside a `reports/` folder as `.html` files

This ensures the code works even if the dataset column names are different

# 📁 **Repository Structure**

