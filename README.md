# 🚖 NCR Ride Booking Analysis (Python + Power BI)

## 📌 Project Overview
This project focuses on analyzing **Uber ride booking data for the NCR region** to uncover key trends such as **booking status, peak hours, payment behavior, cancellations, customer ratings, and driver performance**.  
The analysis was performed using **Python for data cleaning & EDA** and **Power BI for interactive dashboards**.

---

## 🎯 Objectives
- Understand overall **ride booking trends** and monthly performance  
- Analyze **booking status** (Completed, Cancelled, Incomplete)  
- Identify **popular payment methods** (UPI, Cash, Card, Wallet)  
- Explore **customer behavior** (ratings, cancellations, booking patterns)  
- Evaluate **driver performance** (ratings, cancellation rate, shift analysis)  
- Build a professional **Power BI dashboard** for decision-making  

---

## 🛠 Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Power BI** (Power Query, DAX, Interactive Visuals)
- **Jupyter Notebook**
- **CSV Dataset**
- **Git & GitHub (Git LFS for large files)**

---

## 📂 Dataset Information
The dataset includes ride booking details such as:
- Booking Status (Completed / Cancelled / Incomplete)
- Payment Method (UPI / Cash / Credit Card / Debit Card / Wallet)
- Booking Time (Hour / Month)
- Ride Distance
- Revenue / Booking Value
- Customer Ratings
- Driver Ratings
- Cancellation Reasons (Customer + Driver)
- Shift Analysis (Morning / Afternoon / Evening / Night)

---

## 📊 Dashboard Pages (Power BI)

### 1️⃣ Overview Dashboard
**Key insights covered:**
- Total Bookings
- Total Revenue
- Total Ride Distance
- Booking Trend by Month
- Booking Status Distribution
- Payment Method Usage
- Incomplete Rides Count

📌 **KPIs Shown:**
- Average Booking Value  
- Total Bookings  
- Total Revenue  
- Total Ride Distance  
- Incomplete Rides  

---

### 2️⃣ Customer Dashboard
**Key insights covered:**
- Total Customers
- Customer Cancellation Rate %
- Average Customer Rating
- Booking Value
- Payment Type Distribution (Digital vs Cash)
- Customer Ride Cancellations by Reason
- Booking Distribution by Customer Rating

---

### 3️⃣ Driver Dashboard
**Key insights covered:**
- Average VTAT (Driver Waiting Time)
- Driver Cancellation Rate %
- Average Driver Rating
- Average Ride Distance
- Bookings by Driver Rating
- Reasons for Driver Ride Cancellations
- Driver Waiting Time (VTAT) by Shift
- Customer Pickup Time (CTAT) by Shift

---

## 📌 Key Insights (Highlights)
- **UPI** is the most used payment method compared to cash/cards.
- Majority of bookings are **Completed**, followed by **Cancelled** and **Incomplete**.
- Customer rating distribution shows most users rate between **4 and 5**.
- Driver performance varies significantly by **shift timings**.
- Cancellation reasons indicate operational issues like **wrong address, change of plans, driver-related issues**, etc.

---

## 📁 Project Files
- `booking_data_analysis.ipynb` → Python EDA + data cleaning notebook  
- `ncr_ride_bookings.csv` → Raw dataset  
- `uber_cleaned_eda.csv` → Cleaned dataset for analysis  
- `Uber.pbix` → Power BI Dashboard file  
- `Uber-Ride-Booking-Dashboard-NCR-Region.pdf` → Dashboard Export  

---

## 🚀 How to Run (Python Part)
1. Clone the repository:
   ```bash
   git clone https://github.com/Antima5555/uber-ride-booking-analysis.git
