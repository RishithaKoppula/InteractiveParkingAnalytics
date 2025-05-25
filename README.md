# 🚗 Interactive Parking Analytics Dashboard (Tableau)

This project explores hourly parking lot usage trends and future demand forecasting using Tableau.  
The interactive dashboard helps stakeholders analyze **peak usage times**, monitor **lot-level trends**, and **forecast usage** to assist with better access control decisions.

---

## 🎯 Objective

To build a visual analytics tool that:

- Identifies hourly peak usage across multiple parking lots
- Forecasts future lot usage for proactive capacity planning
- Provides filters and drilldowns for weekday/hour-based patterns
- Offers insights into lot-level trends over time

---

## 🧰 Tools Used

- Tableau Desktop (Visual Analytics & Forecasting)
- Basic Excel (preprocessing and adjustment of timestamps)
- GitHub (for version control and documentation)

---

## ⚙️ Key Steps Implemented

1. **Data Cleaning & Preprocessing**
   - Imputed missing `EntranceTime` / `ExitTime`
   - Calculated `Usage Duration` in hours
   - Derived `HourOfDay`, `Weekday`, and `Month` dimensions

2. **Visualization Design**
   - Built a **PeakUsage heatmap** (Hour vs Lot) using card counts
   - Forecasted lot-wise demand for 2025 using Tableau's built-in forecasting model
   - Designed a **dual-axis message system** to handle lots with insufficient forecast data

3. **Interactivity**
   - Added filters for `Lot Number`, `Weekday`, `Hour`
   - Used dynamic tooltips, conditional messages, and highlight actions
   - Created a unified dashboard combining 3 sheets:
     - PeakUsage
     - Forecast Usage
     - Trend Over Time

---

## 📈 Outputs

![image](https://github.com/user-attachments/assets/bd9f4e71-7e9a-4b91-87d2-255595e5bce2)
