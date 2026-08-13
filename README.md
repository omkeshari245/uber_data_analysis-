# 🚕 Uber Data Analytics Dashboard
An end-to-end interactive dashboard analyzing **150,000+ Uber ride records** to evaluate business performance, ride completion dynamics, revenue streams, cancellation drivers, customer segmentation, and geospatial ride patterns.
---

## 📌 Executive Summary

This project transforms raw ride-hailing transactional data into actionable operational and financial insights. By structuring data across key operational pillars, the dashboard empowers decision-makers to minimize ride drop-offs, optimize driver allocation in high-density areas, and boost overall customer satisfaction.

---

## 📊 Dashboard Architecture & Page Overview

The dashboard is structured into **5 dedicated analytical views**:

### 1. 🏠 Overview Page
* **Key Performance Indicators (KPIs):**
* **Completed Bookings** vs. **Lost Bookings** (Cancelled / Incomplete / No Driver Found)
* **Total Revenue**, **Total Ride Distance**, and **Average Distance per Ride**
* **Time-Series Analysis:** Monthly & Quarterly trends for Completed Bookings and Total Revenue.
* **Vehicle & Location Breakdown:** Revenue distribution by Vehicle Type; Top Pickup & Drop-off locations by volume.
* **Rating Metrics:** Tracked **Average Rider Ratings** and **Average Driver Ratings**.

### 2. 🚗 Vehicle Performance Page
* **Granular Breakdown:** Deep dive into individual vehicle categories (Auto, Sedan, SUV, Bike, Prime, etc.).
* **Key Metrics:** Booking counts, generated revenue, and percentage contribution to overall company revenue.

### 3. 💰 Revenue Analysis Page
* **Multi-Dimensional Analysis:** Revenue sliced by **Customer Category**, **Vehicle Type**, and **Payment Method** (Cash, UPI, Credit/Debit Card, Wallet).
* **Temporal Patterns:** Revenue performance tracking across Monthly and Quarterly horizons.

### 4. 👤 Rider & Cancellation Analysis Page
* **Cancellation Breakdown:** Granular analysis of cancelled rides categorized by reason (Driver vs. Customer).
* **Rider Segmentation Table:** Classified profiles into **First-time Riders**, **Return Riders**, and **Regular Riders**.
* **Payment Preference:** Payment method adoption across different rider cohorts.

### 5. 📍 Location & Geospatial Analysis Page
* **Distance Analytics:** Monthly total ride distance and distance breakdown by vehicle type.
* **Demand Hotspots:** Identification of peak **Busy Time Slots** and high-volume **Busy Areas** to address supply-demand gaps.

---

## 🎛️ User Experience & UI Features

* **Hide & Show Filter Panel:** Built-in collapsible filter side-drawer using bookmarks and action toggles to ensure a clean visual canvas while maintaining deep dynamic slicing capabilities.
* **Global Slicers:** Universal filtering across Vehicle Types, Date Ranges (Month/Quarter), Payment Methods, and Booking Statuses.

---

## 📁 Dataset Summary

* **Total Records:** 150,000 rides
* **Key Fields Included:** `Booking ID`, `Date`, `Time`, `Customer ID`, `Booking Status`, `Vehicle Type`, `Pickup/Drop Location`, `Ride Distance`, `Booking Value`, `Payment Method`, `Driver/Customer Ratings`, and `Cancellation Reasons`.

---

## 🛠️ Tools & Technologies Used

* **Business Intelligence:** Power BI (DAX, Data Modeling, Power Query)
* **Data Processing:** Excel / SQL
* **UI/UX Design:** Custom visual containers, visual bookmarks, and toggle navigation controls.

---


## 🚀 How to Open & Explore

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/uber-dashboa
