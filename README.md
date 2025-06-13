# Power BI: Design Scalable Semantic Models Lab

## Overview

This lab focuses on building highly flexible, scalable semantic models in Power BI using advanced DAX techniques. It demonstrates how to simplify reporting by dynamically switching measures and calculations without creating multiple visuals or redundant measures.

---

## Key Objectives

- Modify relationship behavior using DAX (e.g., USERELATIONSHIP).
- Create calculation groups for dynamic time intelligence (YTD, PY, YoY Growth).
- Build field parameters to allow users to switch between different measures in visuals.
- Simplify complex reporting scenarios and reduce redundant visuals.

---

## Tasks Summary

### 1️⃣ Work with Relationships
- Use inactive relationships for role-playing dimensions.
- Apply `USERELATIONSHIP()` within measures to control which relationship is active at query time.

### 2️⃣ Create Calculation Groups
- Build a `Time Calculations` group with:
  - Year-to-Date (YTD)
  - Previous Year (PY)
  - Year-over-Year (YoY) Growth (with dynamic formatting).

### 3️⃣ Apply Calculation Groups in Reports
- Add the calculation group to matrix visuals for flexible time-based analysis.

### 4️⃣ Create Field Parameters
- Build a `Sales Figures` field parameter to dynamically switch between:
  - Total Sales
  - Profit
  - Profit Margin
  - Orders
  - Target

### 5️⃣ Simplify Report Design
- Replace bookmark buttons with field parameters for easier navigation.
- Build interactive visuals where users can control which measure they want to analyze.

---

## Duration

⏱ ~30 minutes

## Lab Files

- Download starter files:  
  https://github.com/MicrosoftLearning/mslearn-fabric/raw/main/Allfiles/Labs/15/15-scalable-semantic-models.zip

---

## Key Concepts

✅ Role-playing dimensions  
✅ USERELATIONSHIP()  
✅ Calculation Groups  
✅ Field Parameters  
✅ Dynamic report interactivity  

---

## Outcome

By the end of this lab, you will have built a flexible and scalable semantic model, capable of supporting interactive reporting without unnecessary visual clutter or redundant measures.

