# UPI Transactions Data Analysis - README

## Problem Statement  
Businesses and financial institutions need to understand digital payment behavior to optimize services, tailor marketing strategies, and improve user experience. However, analyzing large volumes of transaction data to identify trends in user demographics, transaction distribution, and payment preferences can be challenging without effective visualization tools. This project addresses the need to:  
- Visualize transaction patterns across cities, age groups, and payment methods.  
- Enable interactive exploration of data dimensions (e.g., bank, currency, device type).  
- Provide actionable insights into popular merchants and user behavior.  

---

## Solution Approach  

### Step 1: Data Import and Preparation  
- **Data Source**: UPI transaction data (CSV/Excel) containing fields like `City`, `Age Group`, `Payment Method`, `Merchant Name`, `Bank Name`, `Currency`, etc.  
- **Tools**: Tableau Desktop for data cleaning, transformation, and aggregation.  
  - Removed duplicates and null values.  
  - Created calculated fields (e.g., age groups categorized as 18-24, 25-34, 35-44, etc.).  

  

---

### Step 2: Transactions Distribution by City  
- **Visualization**: Bar chart showing transaction volume across cities like **Jaipur, Mumbai, Hyderbad, Bangalore**.  
- **Insight**: Identified top cities driving UPI adoption.  
  - Example: Mumbai accounted for 35% of total transactions.  


![Image](https://github.com/user-attachments/assets/aa129d1c-9404-4199-8e6c-a15ae08dcab0)

Transaction volume by city.

---

### Step 3: Transactions by Age Group  
- **Visualization**: Histogram or stacked bar chart categorizing users into age groups (18-24, 25-34, etc.).  
- **Insight**: Younger users (25-34) dominated transactions, indicating higher digital literacy.  
![Image](https://github.com/user-attachments/assets/fa745e9a-0cb0-4244-bc93-eb4ccae2ff71)  
  
 Transaction count segmented by age.

---

### Step 4: Payment Method and Merchant Analysis  
- **Visualization**: Pie chart or treemap highlighting popular payment methods (e.g., QR code, UPI ID) and merchants like **Amazon, Flipkart, Swiggy, Zomato, IRCTC**.  
- **Insight**: E-commerce platforms (Amazon, Flipkart) and food delivery apps (Swiggy, Zomato) dominated merchant transactions.  
![Image](https://github.com/user-attachments/assets/ee146dfe-af6f-4cb7-bcbc-084838abc5bd)
  
Payment method preferences and top merchants.

---

### Step 5: Interactive Dashboard Development  
- **Filters**: Added user-friendly filters for:  
  - **Bank Name Received** (e.g., HDFC, SBI).  
  - **Currency** (INR, USD).  
  - **Device Type** (Android, iOS).  
  - **Payment Mode** (Immediate, Scheduled).  
  - **Purpose** (Shopping, Bills, Travel).  
- **Interactivity**: Users can drill down into specific segments (e.g., view IRCTC transactions by age group in Mumbai).  


 ![Image](https://github.com/user-attachments/assets/c1c7fd2a-bd96-485d-9cff-09cf5c07e3cd)
 Interactive Tableau dashboard with filters
---

## Technologies/Tools Used  
- **Tableau Desktop**: Data visualization and dashboard design.  

---

## Key Insights  
1. **Top Cities**: Mumbai, Bangalore,Hyderbad and Jaipur led in transaction volume.  
2. **Age Demographics**: 25-34 age group contributed 48% of transactions.  
3. **Preferred Merchants**: Amazon and Flipkart accounted for 60% of e-commerce transactions.  
4. **Payment Methods**: QR code scans were most popular (55%), followed by UPI IDs.  

---

## How to Use the Dashboard  
1. Download the Tableau workbook (https://github.com/Medha-77/Financial-Trends-Analysis-Using-UPI-Transaction-Data/blob/main/Tableau%2BDashboard%2B2%20(1).twbx) and Data source (https://github.com/Medha-77/Financial-Trends-Analysis-Using-UPI-Transaction-Data/blob/main/UPI%2BTransactions%20(3).xlsx) 
2. Open in Tableau Desktop or publish to Tableau Server.  
3. Use filters to explore data by bank, city, device, or purpose.  

