
# 📊 AtliQ Hotels Data Analysis (EDA Project)

## 🚀 Project Overview
This project analyzes booking-level data from AtliQ Hotels to uncover key revenue drivers, customer behavior patterns, and hidden business inefficiencies impacting profitability.

---

## 📂 Dataset Description

The dataset contains **booking-level transactions** across multiple hotel properties and cities.

### 🔑 Key Features:
- **Booking Details:** booking_id, booking_date, check_in_date, checkout_date  
- **Customer Info:** no_guests, ratings_given  
- **Business Metrics:** revenue_generated, revenue_realized  
- **Segmentation:** city, room_category, booking_platform  

---
## ⚠️ Dataset Note

The dataset is not included in this repository due to its large size.

To run this project locally:
- Place the dataset inside the `data/` folder
- Ensure the file name is: `final_dataset.csv`

(Optional: You can use your own dataset with a similar structure.)

## 📥 Dataset Access

Due to GitHub file size limitations, the dataset is not included in this repository.

Download the dataset here:
👉 [ https://drive.google.com/drive/folders/1nUcQ16lKCbDj6nwnsMcUyD0ITqsw9XBo?usp=sharing ]

## Steps to run the project

1. Download and extract the dataset  
2. Place all CSV files inside the `data/` folder  
3. Run the notebooks  

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

## 📊 Key Analysis Performed

### 1️⃣ Occupancy Analysis
- Compared weekday vs weekend bookings  
- Found significantly higher demand on weekends  

### 2️⃣ City-wise Performance
- Evaluated revenue across cities  
- Identified top-performing cities (Mumbai, Delhi)  

### 3️⃣ Revenue Trends
- Analyzed booking trends over time  
- Identified seasonality and peak demand periods  

### 4️⃣ Booking Platform Analysis
- Majority revenue comes from third-party platforms  
- Direct bookings contribute less  

### 5️⃣ Customer Ratings Analysis
- Ratings mostly range between **3.5 – 3.8**  
- Indicates moderate customer satisfaction  

### 6️⃣ Revenue Leakage Analysis
- Significant revenue loss due to **cancellations & no-shows**  

---

## 💡 Business Insights

- 📈 Weekend bookings are significantly higher than weekdays  
- 🏙️ Mumbai and Delhi generate the highest revenue  
- 🌐 Heavy dependency on third-party booking platforms  
- ⭐ Customer ratings influence revenue realization  
- ⚠️ Revenue leakage is a critical profitability issue  

---

## 🧠 Business Recommendations

- 💰 Increase pricing strategically during weekends  
- 📢 Improve weekday occupancy through targeted campaigns  
- 🎯 Focus marketing on high-performing cities  
- 🔗 Promote direct bookings to reduce platform dependency  
- 🌟 Enhance customer experience to improve ratings  
- 🛑 Implement stricter cancellation policies  

---

## 📌 Key Highlights

- ✔️ Revenue leakage directly impacts profitability  
- ✔️ Strong weekend demand pattern  
- ✔️ Customer experience drives revenue  
- ✔️ High dependency on third-party platforms  
- ✔️ Clear booking seasonality trends  

---

## 🏁 Final Thoughts

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
