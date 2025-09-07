# Budyko Curves and State-Level Water Balance Data

## Introduction
The **Budyko curve** is a classic concept in hydrology that describes how climate controls the long-term balance between water and energy. It relates **precipitation** (water supply), **potential evapotranspiration** (climate water demand), and **actual evapotranspiration**.

The central idea is:
- In **humid regions** (where precipitation is high compared to demand), evaporation is limited by **energy** such as solar radiation and temperature.
- In **arid regions** (where demand exceeds supply), evaporation is limited by **water availability**.

## Purpose of This Project
This project uses the Model Parameter Estimation Experiment (MOPEX) database for 12 states:
1. **Calculate key ratios**:
   - The evaporation ratio (*E/P*)  
   - The aridity index (*Ep/P*)
2. **Plot the state data** as a scatter diagram.
3. **Overlay Budyko-style curves** (theoretical models of water–energy balance).
4. **Compare data to theory** to see how well Budyko’s framework explains real-world climates.

## Why Compare Data to Budyko Curves?
- **Climate regime insight**:  
  - States near the *water-limited* line are typically dry or arid.  
  - States near the *energy-limited* line are typically humid.  
- **Educational value**: This comparison shows how a simple conceptual model can capture complex climate–hydrology interactions.  

## Visualization
The plot produced in this project shows:
- Scatter points for each state (labeled with abbreviations).  
- Two physical boundaries: energy-limited and water-limited.  
- Budyko curve for comparison.  
This allows a **visual understanding** of how states differ in their climatic water balance and how closely they follow Budyko’s theory.

## Requirements
- Python 3  
- Libraries:  
  - `numpy`  
  - `matplotlib`  

## Acknowledgment
This project was inspired by **Module 1 of CEE 450 (2024)** taught by **Professor Murugesu Sivapalan**, which introduced the Budyko framework as a foundation for understanding hydrologic balance across climates.

