# OLA Ride Booking Analysis Dashboard

## Project Overview

The OLA Ride Booking Analysis Dashboard is an interactive Power BI project designed to analyze ride booking data and provide valuable business insights. The dashboard helps understand booking trends, revenue performance, vehicle-wise analysis, cancellation patterns, and customer/driver ratings.

Using Power BI visualizations, stakeholders can monitor key performance indicators (KPIs) and make data-driven decisions to improve operational efficiency and customer satisfaction.

## Dashboard Preview

### Overall Analysis
![Overall Analysis](https://raw.githubusercontent.com/kumar-praveen/Ola-Data-Analysis-Project/main/Overall.png)

### Vehicle Type Analysis
![Vehicle Type Analysis](https://raw.githubusercontent.com/kumar-praveen/Ola-Data-Analysis-Project/main/Vehicle%20Type.png)

### Revenue Analysis
![Revenue Analysis](https://raw.githubusercontent.com/kumar-praveen/Ola-Data-Analysis-Project/main/Revenue.png)

### Cancellation Analysis
![Cancellation Analysis](https://raw.githubusercontent.com/kumar-praveen/Ola-Data-Analysis-Project/main/Cancellations.png)

### Ratings Analysis
![Ratings Analysis](https://raw.githubusercontent.com/kumar-praveen/Ola-Data-Analysis-Project/main/Ratings.png)

---

## Objectives

- Analyze overall ride booking performance.
- Track booking success and cancellation rates.
- Monitor revenue generated from different payment methods.
- Compare performance across vehicle categories.
- Evaluate customer and driver ratings.
- Identify booking trends over time.

---

## Tools & Technologies

- Power BI Desktop
- Microsoft Excel / CSV Dataset
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling

---

## Dashboard Pages

### 1. Overall Analysis

Provides a high-level overview of ride booking performance.

#### Key Metrics:
- Total Bookings
- Total Booking Value
- Booking Status Breakdown
- Ride Volume Trend

#### Insights:
- Booking success rate
- Driver cancellations
- Customer cancellations
- Driver not found cases
- Daily ride demand trends

---

### 2. Vehicle Type Analysis

Analyzes the performance of different vehicle categories.

#### Vehicle Categories:
- Prime Sedan
- Prime SUV
- Prime Plus
- Mini
- Auto
- Bike
- E-Bike

#### Metrics:
- Total Booking Value
- Successful Booking Value
- Average Distance Travelled
- Total Distance Travelled

#### Insights:
- Best performing vehicle type
- Distance utilization by category
- Revenue contribution by vehicle type

---

### 3. Revenue Analysis

Provides insights into revenue generation and payment preferences.

#### Metrics:
- Booking Value by Payment Method
- Ride Distance Over Time
- Top Customers by Booking Value

#### Payment Methods:
- Cash
- UPI
- Credit Card
- Debit Card

#### Insights:
- Most preferred payment method
- Revenue contribution by payment type
- High-value customers identification

---

### 4. Cancellation Analysis

Examines booking cancellations from both customer and driver perspectives.

#### KPIs:
- Total Bookings
- Successful Bookings
- Cancelled Bookings
- Cancellation Percentage

#### Customer Cancellation Reasons:
- Driver not moving towards pickup
- Driver asked to cancel
- Change of plans
- AC not working
- Wrong address

#### Driver Cancellation Reasons:
- Personal or car-related issues
- Customer-related issues
- Customer was unavailable
- Capacity-related issues

#### Insights:
- Major causes of cancellations
- Areas for operational improvement
- Service reliability assessment

---

### 5. Ratings Analysis

Compares customer and driver satisfaction across vehicle categories.

#### Metrics:
- Driver Ratings
- Customer Ratings

#### Insights:
- Highest rated vehicle categories
- Driver performance evaluation
- Customer satisfaction comparison

---

## Key Business Insights

- Majority of bookings were successfully completed.
- Cash and UPI contribute the highest booking value.
- Certain vehicle categories generate higher revenue than others.
- Cancellation analysis helps identify operational bottlenecks.
- Ratings remain consistent across most vehicle categories, indicating stable service quality.
- Daily ride volume trends reveal customer demand patterns.

---

## Project Structure

```text
OLA-Ride-Booking-Analysis/
│
├── Dataset/
│   └── OLA_Booking_Data.xlsx
│
├── Dashboard Screenshots/
│   ├── Overall Analysis.png
│   ├── Vehicle Type Analysis.png
│   ├── Revenue Analysis.png
│   ├── Cancellation Analysis.png
│   └── Ratings Analysis.png
│
├── OLA Dashboard.pbix
│
└── README.md
