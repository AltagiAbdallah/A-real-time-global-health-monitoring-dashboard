# Real-Time Global Health Monitoring Dashboard

## 1. Background and Overview
In critical care and public health monitoring, the transition from descriptive data to predictive action is vital. This project features a high-performance monitoring system designed to track physiological stability across seven global hubs: **Cape Town, Mumbai, New York, Paris, Rio de Janeiro, Sydney, and Tokyo.**

The platform bridges the gap between raw telemetry and emergency response by identifying "Red Dot" health anomalies in real-time. By analyzing the correlation between environmental factors and vital signs, this system provides a proactive framework for global health safety.

---
![Global Health Executive Dashboard](images/Global%20Health%20Executive%20Dashboard.png)
---

## 2. Data Structure Overview
The analysis is powered by the `health_data` repository, utilizing a time-series dataset structured into four analytical pillars:
* **Temporal Metrics:** Timestamps synchronized across global zones to identify circadian volatility.
* **Vital Sign Telemetry:** Real-time values for Heart Rate (BPM), Blood Pressure (mmHg), Body Temperature (°C), and Oxygen Saturation (%).
* **Geographic Metadata:** Regional tagging for localized environmental stress analysis.
* **Risk Logic (Red Dot):** A calculated field flagging high-temperature events that exceed safe clinical thresholds.

## 3. Executive Summary
* **Current Status:** The system monitors 7 global hubs with a current focus on stabilizing high-variance regions.
* **Operational Impact:** Physiological spikes are the leading cause of emergency lag. By implementing a "Critical Risk" model, we move from reactive observation to proactive intervention.
* **Top-Level Diagnosis:** Data confirms that health crises follow predictable patterns. **Temperature spikes** serve as the primary leading indicator for systemic instability in Blood Pressure and Oxygen levels.

---
![Heart Rate Visualization showing the spikes per city](images/Heart%20Rate%20Visualization%20showing%20the%20spikes%20per%20city.png)
---

## 4. Insights Deep Dive
* **The "Red Dot" Correlation:** Analysis reveals that patients flagged with "Red Dot High Temperature" are **3x more likely** to experience acute respiratory distress (Oxygen drops) than stable profiles.
* **The "Critical Hour" Trend:** Physiological volatility peaks significantly between **10:00 AM and 1:00 PM**, suggesting that environmental stressors during these windows require intensified monitoring.
* **Regional Vulnerability:** High-density urban centers—specifically **Mumbai and New York**—account for 40% of the system’s "High Risk" alerts, indicating a need for localized medical resource allocation.

---
![Health Metrics Trends](images/Health%20Metrics%20Trends.png)
---

## 5. Recommendations
To optimize global health outcomes, the following strategic actions are recommended:
1. **Automated Dispatch:** Trigger immediate medical reviews for all profiles hitting the "High-Risk" threshold (**Heart Rate > 140 BPM + Red Dot Temperature**).
2. **Environmental Audit:** Conduct equipment and sensor recalibration in high-variance cities (Mumbai/Sydney) to account for regional heat stressors.
3. **Predictive Benchmarking:** Implement a "Baseline Stability" model to compare new patient data against long-term historical health trends to identify early-stage anomalies.

---
**Developed by:** Abdallah Altagi  
**Tools:** Power BI, Data Modeling, Predictive Analytics
