# 🧠 Optimization for Analytics


## 📌 Project Summary

This repository showcases a comprehensive optimization and analytics project conducted as part of the MS987 Optimization for Analytics coursework (2023–24). It tackles two real-world-inspired challenges using FICO Xpress Mosel and Python:

Predictive Modeling for air quality estimation based on sensor data.

Strategic Optimization for routing and resource planning in city home care services.

🔍 Project Structure

## 📦 Part 1: Air Quality Estimation via Optimization

🎯 Objective

Develop a predictive tool that estimates air quality attributes using a customized regression model with a tolerance-based error function, implemented via Linear Programming.

🛠️ Tasks

Clean and preprocess the UCI Air Quality dataset to extract 500 valid entries.

Implement a generic LP model to:

Minimize sum of errors.

Minimize maximum error.

Output regression coefficients (α, β) and error metrics.

Optional: Test model on additional 100 unseen data points.

🧰 Tools

FICO Xpress Mosel

Linear Programming

UCI Air Quality Dataset

📄 Files (in GROUP_3_PART_1.zip)

part1_model.mos – Mosel LP implementation

part1_output.txt – Results with coefficients and errors

part1_memo.pdf – Technical memo explaining model structure and insights


## 📦 Part 2: City Operations Optimization – Home Care Planning

🎯 Objective

Optimize home care operations for a city council, including assigning tasks to centers and planning staff routes using optimization and heuristics.

🛠️ Tasks

Part a: Formulate a minimum-cost network flow model with capacity constraints to assign clients to care centers.

Part b: Output client distribution and explain modeling decisions.

Part c: Implement a heuristic for multi-agent route planning (staff routes under 8-hour shifts).

Bonus (Part d): Apply an improvement heuristic to optimize existing routes by swapping arcs.

🧰 Tools

FICO Xpress Mosel (Part a, b)

Python (Part c, d)

Data: CareDistances.csv, CareDurations.txt, CareDistances-FULL.csv

📄 Files (in Group 3 Part 2.zip)

part2_model.mos – Network flow model

heuristic_routes.py – Route generation using greedy/random logic

improvement_heuristic.py – Post-optimization improvement algorithm

part2_output.csv – Assignment results

part2_memo.pdf – Explanation and results summary
