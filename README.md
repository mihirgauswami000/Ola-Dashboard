

# 📊 Ola Ride Analytics Dashboard

### A Power BI Project for Visualizing Rides, Revenue & Ratings Across Bangalore

---

## 1. **Project Title / Headline**

🚕 **Ola Ride Analytics: Interactive Dashboard for Ride & Revenue Insights**
A dynamic Power BI dashboard designed to analyze Ola ride data across Bangalore—focusing on booking behavior, vehicle performance, cancellation trends, revenue flow, and customer-driver experience.

---

## 2. **Short Description / Purpose**

The **Ola Ride Analytics Dashboard** is an interactive Power BI report built to uncover insights from 100,000+ Ola ride records for June 2025. It visualizes trends in booking activity, cancellation reasons, revenue distribution, and service satisfaction to support data-driven decisions by transport analysts and mobility companies.

---

## 3. **Tech Stack**

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main data visualization platform used for report creation.
* 🧹 **Power Query** – Data transformation and cleaning layer for preparing usable tables.
* 🧠 **DAX (Data Analysis Expressions)** – Used for calculated KPIs, rating metrics, and conditional insights.
* 🔗 **Data Modeling** – Relationships built among bookings, customers, vehicles, and ratings for interactive filtering.
* 📁 **File Format** – `.pbix` used for development; `.png` used for showcasing dashboard screenshots.

---

## 4. **Data Source**

**Source:** Simulated Ola ride data based on actual operational structure.
**Structure:** The dataset includes approximately **100,000 ride records** for the month of **June 2025**, with the following key fields:

* `Date`, `Time`, `Booking ID`, `Customer ID`, `Booking Status`
* `Vehicle Type` – Auto, Bike, eBike, Mini, Prime Sedan, Prime SUV, Prime Plus
* `Pickup` and `Drop Locations` – 50 randomly generated Bangalore localities
* `Ride Distance`, `Booking Value`
* `Driver Rating`, `Customer Rating`
* `Avg VTAT` – Vehicle Time to Arrival
* `Avg CTAT` – Customer Time to Arrival
* `Cancellation Reason` – By both customer and driver
* `Incomplete Ride Reason` – Customer demand, vehicle breakdown, or other issues

---

## 5. **Features / Highlights**

### • **Business Problem**

Ola receives thousands of ride requests daily. Without analytics, it's difficult to understand:

* Why rides are being cancelled
* Which vehicle types perform better
* Who the most valuable customers are
* How drivers and customers rate each other

---

### • **Goal of the Dashboard**

To build a real-time analytics platform that:

* Tracks ride volume and success rates over time
* Reveals cancellation trends and underlying issues
* Highlights high-performing vehicles and customers
* Compares driver and customer satisfaction
* Analyzes revenue split by payment modes

---

### • **Walkthrough of Key Visuals**

#### ✅ **Overall Page**

* **Total Bookings:** 100,000
* **Total Booking Value:** ₹55 Million
* **Booking Status Breakdown:** Pie chart showing success vs. canceled/incomplete rides
* **Ride Volume Over Time:** Line chart analyzing ride demand patterns throughout the month

#### 🚗 **Vehicle Type Page**

* **Top 5 Vehicle Types by Ride Distance**
* **Average Customer Ratings by Vehicle Type**
  Insight: Larger vehicles (e.g., Prime SUV, Prime Plus) tend to get better ratings and longer ride distances.

#### ❌ **Cancellation Page**

* **Cancelled Rides by Customer and Driver**
* **Top Reasons**: Driver asked to cancel, AC not working (for 4-wheelers), customer changed plans
* **Incomplete Rides Reasons**: Vehicle breakdown, customer demand, others

#### 💳 **Revenue Page**

* **Revenue by Payment Method**: UPI, Wallet, Cash, Card
* **Top 5 Customers by Booking Value**: Loyalty targeting insight

#### ⭐ **Ratings Page**

* **Driver vs. Customer Ratings**: Dual line comparison
* **Driver Rating Distribution**: Histogram of performance across all drivers

---

### • **Business Impact & Insights**

* 📈 **Fleet Optimization** – Identify which vehicle types are more efficient and well-rated
* ❌ **Cancellation Reduction** – Pinpoint recurring cancellation causes and address through policy
* 💰 **Payment Preference Analysis** – Track digital vs. cash revenue flow
* ⏱ **Operational Timing Metrics** – Use VTAT and CTAT to minimize customer wait time
* 🧑‍✈️ **Performance Monitoring** – Use ratings to train or reward drivers

---

## 6. **Screenshots / Demo**



### 🔍 Overview Page

![Overall](screenshots/overall_dashboard.png)

### 🚙 Vehicle Type Analysis

![Vehicle Type](screenshots/vehicle_type_analysis.png)

### ❌ Cancellation Trends

![Cancellation](screenshots/cancellation_dashboard.png)

### 💳 Revenue Insights

![Revenue](screenshots/revenue_dashboard.png)

### ⭐ Ratings Analysis

![Ratings](screenshots/ratings_dashboard.png)

---

Let me know if you want this as a `.md` file or ready-to-paste GitHub repo `README.md` with your actual screenshots.
