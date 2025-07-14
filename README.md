# SCT_DS_4
# Task 04 – Traffic Accident Pattern Analysis and Report Generation

---

This project analyzes U.S. traffic accident data to uncover patterns related to **weather conditions**, **time of day**, and **accident severity**. The project utilizes visual analytics to explore the most influential factors and compiles a detailed PDF report of the findings.

---

## Objectives

- Load and preprocess the traffic accident dataset  
- Extract and analyze time-related features (hour, weekday, month)  
- Visualize accidents by weather condition and severity  
- Identify temporal and environmental accident patterns  
- Generate and download a PDF report containing all visualizations  

---

## Workflow Summary

1. Download the accident dataset from an online source (fallback to sample data if unavailable)  
2. Parse `date` and extract:
   - Hour of accident  
   - Day of the week  
   - Month  
3. Visualize:
   - Accidents by hour, weekday, and month  
   - Accidents by weather condition  
   - Accident severity distribution  
4. Save visualizations as `.png` files  
5. Use `fpdf2` to generate a professional PDF report  
6. Automatically download the report: `accident_report.pdf`  

---

## Technologies Used

- `Python 3.x`  
- `pandas`, `numpy` – data preprocessing  
- `matplotlib`, `seaborn` – data visualization  
- `fpdf2` – PDF report generation  
- Google Colab – runtime environment for execution and downloads  

---

## Evaluation

- ✅ Dataset successfully loaded and preprocessed  
- ✅ Time-based and environmental patterns visualized  
- ✅ Plots saved as high-quality `.png` images  
- ✅ PDF report (`accident_report.pdf`) compiled and downloaded  
- ✅ Charts include:
  - Hourly, daily, and monthly accident counts  
  - Weather condition distributions  
  - Severity level analysis  

---

## Notes

- Sample data is used if live data cannot be accessed  
- Visualizations offer a clear understanding of when and under what conditions accidents occur  
- The project provides a scalable structure for integrating further spatial analysis (e.g., accident hotspots on maps)  

---
