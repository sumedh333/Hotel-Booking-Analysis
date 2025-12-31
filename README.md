# Hotel Booking Analysis – Guest Behavior & Booking Trends

## Overview
Analysis of hotel booking data to understand **seasonal demand patterns, customer behavior, cancellations, and revenue KPIs**, with the objective of supporting **pricing strategy, capacity planning, and operational decision-making** in the hospitality domain.

---

## Dataset
- **Source**: Hotel Booking Demand dataset  
- **Records**: ~63,000 bookings  
- **Hotel Types**: City Hotel, Resort Hotel  

---

## Analysis Focus
The analysis examines **monthly demand trends**, **differences between hotel types**, **cancellation behavior across customer segments**, and **key hospitality KPIs** such as ADR and RevPAR.

---

## Exploratory Data Analysis (Key Findings)

### 1. Monthly Booking Trend by Hotel Type
![Monthly Booking Trend](visuals/monthly_booking_trend.png)

**Insight:**  
City hotels consistently receive higher booking volumes, while both City and Resort hotels exhibit strong seasonal peaks during summer months.

---

### 2. Reservation Status by Customer Type
![Reservation Status by Customer Type](visuals/reservation_by_customer_type.png)

**Insight:**  
Transient customers contribute the majority of cancellations, whereas contract and group customers demonstrate higher booking reliability.

---

## Tableau Dashboard
An interactive Tableau dashboard was built to track **core hospitality KPIs and operational metrics**.

![Tableau Dashboard](visuals/tableau_dashboard.png)

**Dashboard Highlights**
- Total Bookings: 63,353  
- Average Daily Rate (ADR): 106.3  
- Revenue Per Available Room (RevPAR): 394.4  
- Seasonal demand and parking trends  
- Customer and geographic segmentation with interactive filters  

🔗 **Tableau Public Dashboard**:  
https://public.tableau.com/views/HotelBookingAnalysis_17215875929250/HotelBookingAnalysis

---

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib)
- **Jupyter Notebook** for exploratory analysis
- **Tableau** for interactive dashboards

---

## Business Impact
- Identified seasonal demand patterns to support **capacity and pricing decisions**
- Highlighted high-cancellation customer segments for **policy optimization**
- Enabled **dashboard-driven monitoring** of revenue and occupancy KPIs
