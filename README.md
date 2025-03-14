# 📊 **UPI Transactions Data Analysis**  

## 📌 **Problem Statement**  
With the rapid rise of **digital payments**, businesses and financial institutions need insights into **user behavior** to:  
✅ **Optimize services** for different user demographics.  
✅ **Tailor marketing strategies** for merchants and payment methods.  
✅ **Enhance user experience** by identifying transaction trends.  

Analyzing **large-scale transaction data** can be complex, so this project leverages **Tableau** to:  
- **Visualize transaction trends** across **cities, age groups, and payment methods**.  
- Enable **interactive exploration** of dimensions like **bank, currency, and device type**.  
- Provide **actionable insights** on popular merchants and user behavior.  

---

## 🚀 **Solution Approach**  

### 🔹 **Step 1: Data Import & Preparation**  
📌 **Data Source**: UPI transaction dataset (`CSV/Excel`) with fields like:  
✔ `City`, `Age Group`, `Payment Method`, `Merchant Name`, `Bank Name`, `Currency`  
✔ `Device Type`, `Transaction Volume`, `Transaction Amount`, `Payment Mode`  

📌 **Tools Used**: **Tableau Desktop**  
✔ **Data Cleaning**: Removed **duplicates** & **null values**.  
✔ **Calculated Fields**: Created **age groups** (e.g., **18-24, 25-34, 35-44**).  

---

### 🔹 **Step 2: Transactions Distribution by City**  
📌 **Visualization**: **Bar chart** showing **transaction volume** across key cities like:  
🔹 **Mumbai, Bangalore, Hyderabad, Jaipur**  
📌 **Key Insight**: **Mumbai leads UPI adoption, accounting for 35% of total transactions**.  

![Transaction Volume by City](https://github.com/user-attachments/assets/aa129d1c-9404-4199-8e6c-a15ae08dcab0)  

---

### 🔹 **Step 3: Transactions by Age Group**  
📌 **Visualization**: **Histogram/Stacked Bar Chart** categorizing users into **age groups**:  
✔ **18-24**  
✔ **25-34**  
✔ **35-44**  
✔ **45+**  

📌 **Key Insight**: **Users aged 25-34 dominate transactions**, showing **higher digital literacy and adoption**.  

![Transactions by Age](https://github.com/user-attachments/assets/fa745e9a-0cb0-4244-bc93-eb4ccae2ff71)  

---

### 🔹 **Step 4: Payment Method & Merchant Analysis**  
📌 **Visualization**: **Pie Chart/Treemap** for **popular payment methods** & **merchant transactions**.  
✔ **Top Payment Methods**: **QR Code, UPI ID, Auto-Pay**.  
✔ **Top Merchants**: **Amazon, Flipkart, Swiggy, Zomato, IRCTC**.  

📌 **Key Insight**: **E-commerce & food delivery dominate UPI transactions**.  

![Payment Method & Merchants](https://github.com/user-attachments/assets/ee146dfe-af6f-4cb7-bcbc-084838abc5bd)  

---

### 🔹 **Step 5: Interactive Dashboard Development**  
📌 **Added Filters** for:  
✔ **Bank Name** (e.g., HDFC, SBI, ICICI).  
✔ **Currency** (INR, USD).  
✔ **Device Type** (Android, iOS).  
✔ **Payment Mode** (Immediate, Scheduled).  
✔ **Purpose** (Shopping, Bills, Travel, Food Delivery).  

📌 **Interactivity**: Users can **drill down** into **city-wise trends**, e.g.,  
🔹 View **IRCTC transactions by age group in Mumbai**.  

![Interactive Dashboard](https://github.com/user-attachments/assets/c1c7fd2a-bd96-485d-9cff-09cf5c07e3cd)  

---

## 🛠 **Technologies & Tools Used**  
✔ **Tableau Desktop** – For **data visualization & interactive dashboard creation**.  

---

## 🔑 **Key Insights**  
📌 **Top Cities**: **Mumbai, Bangalore, Hyderabad, Jaipur** lead in UPI transactions.  
📌 **Age Demographics**: **25-34 age group** contributes **48%** of all transactions.  
📌 **Popular Merchants**: **Amazon & Flipkart** account for **60%** of e-commerce transactions.  
📌 **Preferred Payment Method**: **QR Code (55%)** is the most used, followed by **UPI ID payments**.  

---

## 🔗 **How to Use the Dashboard**  
1️⃣ **Download the Tableau Workbook** 📥  
🔹 [UPI Transactions Tableau Dashboard](https://github.com/Medha-77/Financial-Trends-Analysis-Using-UPI-Transaction-Data/blob/main/Tableau%2BDashboard%2B2%20(1).twbx)  

2️⃣ **Download the Data Source** 📊  
🔹 [UPI Transactions Dataset](https://github.com/Medha-77/Financial-Trends-Analysis-Using-UPI-Transaction-Data/blob/main/UPI%2BTransactions%20(3).xlsx)  

3️⃣ **Open in Tableau Desktop** or **Publish to Tableau Server**.  
4️⃣ **Use Filters** to explore transactions by **bank, city, device type, or payment purpose**.  

🚀 **Explore insights into digital payment trends & optimize financial strategies!**
