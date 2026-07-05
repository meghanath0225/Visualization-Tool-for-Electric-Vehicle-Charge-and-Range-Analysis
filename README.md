# 🚗 Visualization Tool for Electric Vehicle Charge and Range Analysis

An end-to-end data analytics and visualization project that analyzes electric vehicles, charging infrastructure, performance, efficiency, and pricing trends using Tableau, SQL, Python Flask, and Bootstrap.

---

## 📌 Project Overview

The **Visualization Tool for Electric Vehicle Charge and Range Analysis** is an interactive analytics platform designed to provide comprehensive insights into the electric vehicle ecosystem.

The project integrates multiple datasets to visualize charging infrastructure, vehicle specifications, energy efficiency, pricing, and market trends through interactive Tableau dashboards and storytelling techniques.

The visualizations are embedded into a Flask-based web application to deliver an engaging and user-friendly experience.

---

## 🎯 Project Objectives

The primary objectives of this project are:

- Analyze electric vehicle performance and charging infrastructure.
- Visualize charging station distribution across different regions.
- Compare EV brands based on range, efficiency, and pricing.
- Identify high-performing and energy-efficient electric vehicles.
- Study body styles and powertrain technologies in the EV market.
- Build interactive dashboards and stories for data-driven insights.
- Integrate Tableau analytics into a responsive web application.

---

## 📍 Data Sources

The project utilizes the following datasets:

| Dataset | Description |
|----------|-------------|
| CheapestElectricCars-EVDatabase.csv | Global EV specifications including range, efficiency, speed, and pricing |
| electric_vehicle_charging_station_list.csv | Charging station locations and charging types across India |
| ElectricCarData_Clean.csv | Cleaned EV dataset for analytical processing |
| EVIndia.csv | Electric vehicle information specific to the Indian market |

These datasets were cleaned, transformed, and analyzed to generate meaningful insights into electric mobility trends.

---

## 🗄️ SQL Analysis

SQL was used to perform exploratory and analytical operations on the EV datasets.

### Key Queries Implemented

- Top electric vehicles by driving range
- Average driving range by manufacturer
- Premium EV price analysis
- Body style distribution analysis
- Fast-charging capability comparison
- Brand-wise performance evaluation

### Sample Query

```sql
SELECT Brand,
       ROUND(AVG(Range_Km),2) AS Average_Range
FROM electriccardata_clean
GROUP BY Brand
ORDER BY Average_Range DESC;
```

---

## 📊 Key Metrics

| Metric | Value |
|----------|---------|
| Total Global EV Brands | 103 |
| Total Indian EV Brands | 9 |
| Dashboard Visualizations | 8 |
| Tableau Story Points | 5 |
| Datasets Used | 4 |
| SQL Queries Implemented | 8 |

These KPIs provide an overview of the analytical scope and project coverage.

---

## 📈 Dashboard Features

The interactive Tableau dashboard includes:

### 🔎 Interactive Analysis

Users can explore data dynamically through:

- Brand-based comparisons
- Body Style filtering
- PowerTrain analysis
- Regional charging infrastructure analysis
- Vehicle performance evaluation

### 📊 Visualization Modules

- Charging Stations by Region and Type
- EV Charging Station Map of India
- Different Electric Cars in India
- Top Speed Analysis by Brand
- Price Analysis of Electric Vehicles
- Top 10 Most Efficient EV Brands
- Brands According to Body Style
- PowerTrain Analysis
- Global EV Brand Statistics
- Indian EV Brand Statistics

---

## 📖 Tableau Story Insights

The Tableau Story presents a complete narrative of the EV ecosystem through the following analytical stages:

### 1️⃣ Charging Stations in India
This visualization presents the geographical distribution of electric vehicle charging stations across India. It highlights the availability of charging infrastructure in different regions and helps identify areas with higher EV adoption. The analysis supports understanding of accessibility, infrastructure readiness, and future expansion opportunities for sustainable transportation.

### 2️⃣ Charging Stations in Different Regions & Type
This analysis compares the number of charging stations across various regions and charging types. It reveals regional disparities in charging infrastructure and identifies the prevalence of fast and standard charging technologies. The insights can assist policymakers and investors in planning efficient EV ecosystem development.

### 3️⃣ Price Range of Different Electric Cars in India
This visualization explores the price distribution of electric vehicles available in the Indian market. It provides a comparative analysis of affordable, mid-range, and premium EV models, enabling consumers and stakeholders to understand market segmentation and purchasing trends.

### 4️⃣ Different Brands & Number of Models
This chart analyzes the diversity of EV manufacturers and the number of models offered by each brand. It highlights market competition, product availability, and the dominance of specific manufacturers within the Indian electric vehicle sector.

### 5️⃣ Top 10 Most Efficient EV Brands
Energy efficiency is a critical factor in electric mobility. This visualization ranks the top ten EV brands based on their energy consumption (Wh/km), showcasing vehicles that deliver superior performance while minimizing power usage. These insights support informed decision-making for environmentally conscious consumers. 

---

## 💡 Key Business Insights

- Metropolitan regions possess the highest concentration of charging stations.
- SUVs and Hatchbacks dominate the Indian EV market.
- Premium EV models deliver greater range but involve higher acquisition costs.
- Fast-charging technology adoption is increasing across manufacturers.
- Significant efficiency differences exist among EV brands, impacting operational costs.
- Global EV markets exhibit greater brand diversity than the Indian market.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Tableau Public | Interactive Data Visualization |
| MySQL | Data Analysis & Query Processing |
| Python | Backend Development |
| Flask | Web Application Framework |
| HTML5 | Frontend Structure |
| CSS3 | User Interface Styling |
| Bootstrap | Responsive Design |
| Git & GitHub | Version Control |

---

## 💼 Business Value

This project enables stakeholders to:

- Understand EV market dynamics and adoption patterns.
- Identify regions requiring charging infrastructure expansion.
- Compare vehicles based on efficiency, speed, range, and pricing.
- Support strategic decisions for sustainable transportation initiatives.
- Promote awareness of electric mobility technologies.

---

## 🌐 Live Dashboard & Story

### 📊 Tableau Dashboard

🔗 **Dashboard Link**

https://public.tableau.com/views/ElectricCarsAnalyticsDashboard_17831451243460/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

### 📖 Tableau Story

🔗 **Story Link**

https://public.tableau.com/views/StoryofElectricCarsinIndia_17832669081640/StoryofElectricCarsinIndia?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 📁 Project Structure

```text
EV VEHICLES VISUALIZATION
│
├── app.py
├── requirements.txt
├── README.md
|
│
├── datasets/
├── documentation/
│   └── Project_Report.pdf
│
├── screenshots/
│
├── sql/
│   ├── create_database.sql
│   └── sql_queries.sql
│
|
│
└── templates/
    └── index.html
```

---


## 📄 Documentation

Detailed project documentation is available at:

```text
documentation/Project_Report.pdf
```

---

## 🚀 Future Scope

- Real-time EV data integration
- Machine learning-based demand prediction
- Live charging station monitoring
- Mobile application development
- Government policy analytics
- Smart recommendation systems for EV buyers

---

## 📊 Project Outcome

This project successfully demonstrates the integration of:

- Data Cleaning & Transformation
- SQL-Based Analytical Processing
- Interactive Tableau Dashboards
- Tableau Storytelling Techniques
- Flask Web Application Development
- GitHub-Based Project Management

The platform provides comprehensive insights into electric vehicle adoption, charging infrastructure, efficiency, and market behavior, supporting informed decision-making in the evolving EV ecosystem.

---
