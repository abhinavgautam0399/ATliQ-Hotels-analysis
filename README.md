
# 📊 AtliQ Hotels Data Analysis (EDA Project)

_End-to-end Exploratory Data Analysis project focused on uncovering revenue drivers, identifying leakage, and delivering actionable business insights to improve hotel profitability._

## 🚀 Project Overview

This project analyzes booking-level data from AtliQ Hotels to uncover:

- Revenue leakage due to cancellations and no-shows  
- Customer behavior patterns and booking trends  
- Platform dependency and performance  
- City-wise revenue distribution  
- Pricing and demand insights  

The goal is to translate raw data into meaningful insights and business recommendations.

---

## 🎯 Business Objective

Analyze hotel booking data to identify inefficiencies, optimize pricing strategies, improve occupancy, and enhance overall revenue performance.

---

## 📁 Dataset Description

The dataset contains booking-level transaction data across multiple hotel properties and cities.

### 🔑 Key Features:
- **Booking Details:** booking_id, booking_date, check_in_date, checkout_date  
- **Customer Info:** no_guests, ratings_given  
- **Revenue Metrics:** revenue_generated, revenue_realized  
- **Segmentation:** city, room_category, booking_platform  

---

## ⚠️ Dataset Note

Due to GitHub file size limitations, the dataset is not included in this repository.

### 📥 Dataset Access:
Download from here:  
👉[https://drive.google.com/drive/folders/1nUcQ16lKCbDj6nwnsMcUyD0ITqsw9XBo?usp=sharing]

## Steps to run the project

1. Download and extract the dataset  
2. Place all CSV files inside the `data/` folder  
3. 3. Run `AtliqHotelsEDA.ipynb` or `AtliQHotelsAnalysis.ipynb`  

---

## 📝 Note
Notebooks are placed in the root directory for ease of use. Simply download the dataset, place it in the `data/` folder, and run the notebooks without modifying any file paths.


```
data/
├── dim_date.csv
├── dim_hotels.csv
├── dim_rooms.csv
├── fact_aggregated_bookings.csv
└── final_dataset.csv
```
## 🔍 Dataset Understanding

Each row represents a **single booking transaction**, enabling:

- Revenue leakage analysis (cancellations & no-shows)  
- Platform performance evaluation  
- City-level performance tracking  
- Customer behavior insights  

---

## 🧠 Key KPIs Analyzed

- Revenue Generated vs Revenue Realized  
- Cancellation & No-show Impact (Revenue Leakage)  
- Occupancy Trends (Weekday vs Weekend)  
- Platform Contribution to Revenue  
- City-wise Revenue Performance  

---

## 🔍 Data Cleaning & Preprocessing

- Converted date columns into proper datetime format  
- Handled inconsistent date formats using `errors='coerce'`  
- Removed duplicate records to maintain data integrity  
- Identified missing values across key columns for analysis  

---

## ⚙️ Feature Engineering

New features were created to enhance analysis:

- **month:** Extracted from booking_date to analyze seasonality  
- **day_type:** Classified bookings into Weekday / Weekend  

---

## 🔎 Business Use Cases

Each booking record enables:

- Revenue leakage analysis (cancellations & no-shows)  
- Platform performance evaluation  
- City-level performance tracking  
- Customer behavior insights  

---

## 📊 Key Analysis Performed

### 📈 Occupancy Analysis
- Compared weekday vs weekend bookings  
- Observed significantly higher demand on weekends  

### 🌆 City-wise Performance
- Evaluated revenue across cities  
- Identified top-performing cities (Mumbai, Delhi)  

### 📅 Revenue Trends
- Analyzed booking trends over time  
- Identified seasonality and peak demand periods  

### 💻 Booking Platform Analysis
- Majority revenue comes from third-party platforms  
- Direct bookings contribute significantly less  

### ⭐ Customer Ratings Analysis
- Ratings mostly range between 3.5 – 4.0  
- Indicates moderate customer satisfaction  

### 💸 Revenue Leakage Analysis
- Significant revenue loss due to cancellations and no-shows  

---

## 💡 Business Insights

- Weekend bookings are significantly higher than weekdays  
- Mumbai and Delhi generate the highest revenue  
- Heavy dependency on third-party booking platforms  
- Customer ratings influence revenue realization  
- Revenue leakage is a critical profitability issue  

---

## 📌 Business Recommendations

- 🔥 Increase pricing strategically during weekends  
- 📉 Improve weekday occupancy through targeted campaigns  
- 🎯 Focus marketing efforts on high-performing cities  
- 🔗 Promote direct bookings to reduce platform dependency  
- ⭐ Enhance customer experience to improve ratings  
- 🚫 Implement stricter cancellation policies  

---

## 🚀 Key Highlights

- ✔ Revenue leakage directly impacts profitability  
- ✔ Strong weekend demand pattern  
- ✔ Customer experience drives revenue  
- ✔ High dependency on third-party platforms  
- ✔ Clear booking seasonality trends  

---

## 🧾 Final Thoughts

By improving cancellation control, enhancing customer experience, and optimizing booking strategies, AtliQ Hotels can significantly boost both revenue and operational efficiency.

---
## 📁 Project Structure

```
ATliQHotelsEDA/
│
├── data/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_aggregated_bookings.csv
│   └── final_dataset.csv
│
├── outputs/
│   └── charts/
│
├── AtliqHotelsEDA.ipynb
├── AtliQHotelsAnalysis.ipynb
├── README.md
└── requirements.txt
```

## 🎯 Outcome

This project demonstrates the ability to:

- Clean and preprocess raw datasets  
- Perform Exploratory Data Analysis (EDA)  
- Extract business insights from data  
- Build meaningful visualizations  
- Translate insights into actionable recommendations  

---

## 🛠️ Tools & Technologies

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔗 Connect With Me

- 💼 **LinkedIn:** https://www.linkedin.com/in/abhinav-gautam-6a922b22a?utm_source=share_via&utm_content=profile&utm_medium=member_android  
- 📧 **Email:** gautamabhinav456@gmail.com  

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
