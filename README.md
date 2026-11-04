# 🏨 Hotel Booking Cancellation Analysis

## 📌 Project Overview
This project analyzes hotel booking data to identify cancellation patterns, understand customer behavior, and discover factors that contribute to hotel booking cancellations.

The analysis focuses on City Hotels and Resort Hotels using Python and data visualization libraries.

## 📊 Dataset
- Total bookings: 119,390
- Bookings after cleaning: 118,897
- Hotels: City Hotel and Resort Hotel
- Location: Portugal
- Period: July 2015 – August 2017

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 🧹 Data Cleaning
- Checked missing values and data types.
- Converted reservation status dates into datetime format.
- Removed unnecessary columns (`agent` and `company`).
- Removed rows containing missing values.
- Removed extreme ADR outliers.
- Extracted months for monthly analysis.

## 📈 Exploratory Data Analysis
The project includes the following visualizations:

1. Reservation Status Count
2. Reservation Status by Hotel Type
3. Average Daily Rate in City and Resort Hotels
4. Monthly Reservation Status
5. Monthly ADR of Canceled Bookings
6. Top 10 Countries with Most Cancellations
7. ADR Comparison: Canceled vs. Non-Canceled Bookings
8. ADR Comparison for January 2016 – September 2017

## 🔍 Key Findings
- Approximately 37% of bookings were canceled.
- City Hotels had a higher cancellation rate (42%) than Resort Hotels (28%).
- January recorded the highest cancellation share (57%).
- August had the lowest cancellation share (24%).
- Portugal accounted for approximately 62% of all cancellations.
- Online Travel Agents contributed 47% of canceled bookings.
- Canceled bookings had a higher average daily rate (ADR 122) compared to non-canceled bookings (ADR 101).

## 💡 Business Recommendations
- Review pricing strategies to reduce cancellations.
- Offer discounts during weekends and holidays.
- Introduce targeted marketing campaigns during January.
- Improve room quality and customer service, particularly in Portugal.

## 🎯 Project Objective
The main objective is to use data analysis and visualization to understand hotel booking cancellations and provide actionable insights that can help hotels improve revenue and reduce booking cancellations.

## 👨‍💻 Author
**Hotel Booking Cancellation Analysis – Data Analytics Project**
