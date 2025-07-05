# 🚗 Dynamic Pricing for Urban Parking Lots

A real-time intelligent pricing engine built as a part of **Summer Analytics 2025** hosted by the **Consulting & Analytics Club × Pathway**.

---

## 📌 Overview

Urban parking spaces are limited. Static pricing leads to underutilization or overcrowding. Our system uses real-time data to dynamically update parking prices based on demand, traffic, queue, vehicle type, and special day effects.

---

## 💻 Tech Stack

- Python 🐍  
- Pandas & NumPy  
- Bokeh (for real-time plotting)  
- FPDF (for report generation)  
- Google Colab (execution)  
- GitHub (submission & collaboration)  

---

## 🏗️ Architecture Diagram

```mermaid
flowchart TD
    A[Parking Lot Input Data] --> B[Feature Extraction]
    B --> C[Demand Estimation Model]
    C --> D1[Price Calculation Model 1]
    C --> D2[Price Calculation Model 2]
    D1 --> E[Bokeh Visualization]
    D2 --> F[PDF Report]
