# 📦 **Canadian Freight Analysis**  

## 🚀 **Project Overview**  
This project leverages the **Canadian Freight Analysis Framework (CFAF)** dataset to uncover insights into freight transportation trends across Canada. By exploring shipment characteristics such as weight, distance, transportation mode, and revenue, the analysis aims to drive data-informed strategies for optimizing freight operations.  

📈 **Key Goals:**  
- Understand revenue-generating factors.  
- Identify trends by region, mode, and shipment attributes.  
- Build predictive models for revenue optimization.  

---

## 🎯 **Motivation**  
Freight transportation underpins Canada’s economy, connecting industries and regions. This project empowers stakeholders by:  
- Highlighting key drivers of freight revenue.  
- Improving operational efficiency and decision-making.  
- Supporting new freight businesses with actionable insights.  

---

## 📂 **Dataset Overview**  
**Source:** Statistics Canada surveys  
**Time Period:** 2011–2017  
**Rows:** ~58,721  
**Features:** Shipment value, weight, mode, distance, and more.  

### **Key Features:**  
| **Column Name**       | **Description**                       |  
|------------------------|---------------------------------------|  
| `transport_mode`       | Mode of transport (truck, rail, air) |  
| `shipment_weight`      | Total weight of the shipment         |  
| `revenue`              | Revenue generated                   |  
| `origin_region`        | Shipment starting region            |  
| `destination_region`   | Shipment destination region         |  

---

## 🛠️ **Methodology**  

### **Data Preprocessing:**  
- Cleaned missing and irrelevant data.  
- Grouped provinces into regions: **East**, **West**, and **Other Parts**.  
- Encoded categorical variables and created new features.  

### **Exploratory Data Analysis (EDA):**  
- Visualized trends in revenue by transport mode and region.  
- Investigated relationships between revenue, distance, and weight.  

### **Modeling & Prediction:**  
- **Additive Multiple Linear Regression (MLR):**  
  Modeled revenue with key features.  
- **Interaction Models:**  
  Explored variable interactions to enhance predictive accuracy.  

---

## 🔍 **Key Insights**  

📌 **Revenue Drivers:**  
- **Top Transport Mode:** Trucks lead in revenue generation, followed by rail and air.  
- **Regional Trends:** Western Canada contributes the highest revenue.  
- **Weight & Distance:** Heavier shipments and longer distances positively impact revenue.  

📌 **Model Highlights:**  
- **Additive Model:** Adjusted R-squared = **0.8017**  
- **Interaction Model:** Adjusted R-squared = **0.9188**  
  - Captures variable interactions, explaining ~91.88% of revenue variability.  

---

## 💻 **Tools & Technologies**  

| **Category**      | **Tools**                                 |  
|--------------------|-------------------------------------------|  
| Programming        | **R**                                    |  
| Data Manipulation  | `dplyr`, `car`                           |  
| Modeling           | `olsrr`, `leaps`                         |  
| Visualization      | `GGally`, `ggplot2`                      |  

---

## 📈 **Results Summary**  

### **Additive MLR Model**  
Revenue prediction based on transport mode, weight, distance, and commodity type.  

### **Interaction Model**  
Improved predictions by accounting for interactions between features, achieving **high accuracy**.  

---

## 🔮 **Future Scope**  
- Integrate additional datasets to refine models.  
- Apply machine learning techniques to explore non-linear trends.  
- Investigate environmental and sustainability metrics in freight transportation.  
