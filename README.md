# LIFELINE: Artemis II Astronaut Health Telemetry Monitoring System
## Overview
This project simulates a NASA-style mission control health monitoring system for astronauts using Splunk.
It demonstrates how biometric and performance data could be ingested, analyzed, and visualized to support crew health and safety during space missions.

All data used in this project is **simulated** and does not represent real astronaut medical data.

---

## Project Objectives
- Simulate astronaut health telemetry ingestion
- Visualize key health indicators (heart rate, oxygen, stress)
- Detect high-risk conditions during mission phases
- Present data in a mission control-style dashboard

---

## Data Description
The dataset includes:
- Heart rate
- Oxygen saturation levels
- Stress scores
- Sleep duration
- Exercise duration
- Mission phase (sleep, wake, exercise)
- Alert flags (NORMAL, WATCH, HIGH)

File: `data/astronaut_health.csv`

---

## Tools Used
- Splunk Enterprise (Search & Reporting)
- CSV-based simulated telemetry data
- SPL (Search Processing Language)

---

## Dashboard Panels
1. Average Heart Rate per Astronaut
2. High-Risk Alerts by Mission Phase
3. Stress Levels Over Time
4. Safe Oxygen Percentage Indicator

---

## How It Works 
Think of each astronaut like a player in a game.
Their heart rate, oxygen, and stress are their health bars.
Splunk watches those numbers and shows when someone may need attention.

This dashboard helps mission control quickly answer:
- Who is under stress?
- When do risks happen most?
- Are astronauts staying in safe health ranges?

---

## Screenshots

### Data Ingestion
<img width="1365" height="634" alt="image" src="https://github.com/user-attachments/assets/beceb6a3-03cb-48f7-ad06-1167e48b153a" />


### Dashboard Overview
<img width="1037" height="501" alt="{9B7C3649-95DA-45D8-A9BF-CF7E8C1E3038}" src="https://github.com/user-attachments/assets/c4d6150c-915b-4257-be2d-9b78861a7e9a" />
<img width="1309" height="288" alt="image" src="https://github.com/user-attachments/assets/8842ea3a-3fb6-4487-8a1e-f4e2330b916b" />
<img width="1307" height="289" alt="image" src="https://github.com/user-attachments/assets/c293c37f-1166-43db-a7de-37897aa43a18" />
<img width="1308" height="143" alt="image" src="https://github.com/user-attachments/assets/2716fe38-f57b-4bbb-befb-60af149e435a" />





(Additional screenshots available in the `screenshots/` folder.)

---

## Why This Matters for Space Missions
Monitoring astronaut health in real time is critical in microgravity environments where small issues can escalate quickly.

This project demonstrates:
- Systems thinking
- Human-centered monitoring
- Data visualization for decision support
- Foundations of operational health analytics

---

## What I Learned
This project taught me how Splunk handles indexes, data infestion, and field extraction, as well as how to confirm that telemetry data is actually being indexed and searchable. I learned how to create calculated fields from raw astronaut health data and use SPL to transform metrics like oxygen levels and heart rate into meaningful safety indicators. Working on this project also helped me understand how continuous health monitoring supports astronaut safety by identifying trends, thresholds, and potential risk conditions. In addition, I gained hands-on experience troubleshooting common Splunk errors and preparing data for clear, dashboard-ready visualizations. 
