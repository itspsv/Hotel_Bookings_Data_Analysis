# Hotel Bookings Data Analysis

This project analyzes hotel booking data to uncover trends related to customer behavior, cancellations, and revenue patterns.  
Using Python, I performed **data cleaning, exploratory data analysis (EDA), and visualization** to derive actionable business insights.

---

## Project Overview
The dataset contains hotel booking records from **City Hotels** and **Resort Hotels** with features such as booking dates, stay duration, number of guests, and cancellation status.  
The goal is to identify **key factors influencing cancellations** and understand **booking trends over time**.

---

## Tools & Libraries Used
- **Python**  
- **Pandas** – Data manipulation and analysis  
- **NumPy** – Numerical operations  
- **Matplotlib** & **Seaborn** – Data visualization  
- **Jupyter Notebook**

---

## Data Preprocessing
- Loaded dataset using `pandas.read_csv()`  
- Converted `reservation_status_date` to datetime format  
- Checked for missing values and dropped null records  
- Removed extreme outliers (`adr < 5000`)  
- Verified column data types and basic statistics  

---

## Exploratory Data Analysis (EDA)
Performed descriptive analysis and visualizations to understand:
- Reservation status (canceled vs. not canceled)  
- Hotel type performance (City vs. Resort)  
- Average Daily Rate (ADR) trends  
- Monthly booking and cancellation patterns  
- Top 10 countries with the highest cancellations  
- Market segment distribution and its influence on cancellation  

---

## Key Visualizations
1. **Reservation Status Count**  
   Bar chart showing the ratio of canceled vs. non-canceled bookings.  
2. **Hotel Type vs. Cancellations**  
   Comparison between City and Resort hotels.  
3. **ADR Trend Over Time**  
   Line plots for average daily rate per hotel type.  
4. **Monthly Cancellation Trends**  
   Count plots showing cancellation frequency per month.  
5. **Top 10 Countries with Most Cancellations**  
   Pie chart highlighting cancellation distribution by country.  

---

## Insights & Findings
- **City Hotels** had a higher cancellation rate than Resort Hotels.  
- **Peak cancellations** occurred between **July and August**, possibly due to seasonal demand fluctuations.  
- **ADR (Average Daily Rate)** was generally higher for Resort Hotels.  
- **Online TA (Travel Agencies)** accounted for most of the cancellations.  
- Bookings from **certain countries** showed higher cancellation ratios.  

---

## Dataset
- File: `hotel_bookings.csv`  
- Source: [Kaggle - Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/mojtaba142/hotel-booking)

---

## Conclusion
This analysis provides valuable insights into booking patterns, helping hotel managers optimize pricing strategies, reduce cancellations, and improve customer retention.
