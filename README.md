#  Liquified CO2 Transport Techno-Economic Analysis 

##  Overview

**Current Status: Ongoing**

Constructing a **Techno-Economic Analysis ** framework for the maritime transport of Liquefied CO2 (LCO2). This project integrates **real-time AIS vessel telemetry** with **Copernicus weather data** to model voyage economics dynamically.
Targeting the development of a pipeline to predict cost of transport by utilizing **Gaussian Mixture Models (GMM)** coupled with **Monte Carlo simulations** to quantify the **Levelized Cost of Transport (LCOT)** .

The project would follow a 5-stage pipeline:

1.  **Data Acquisition:** Scrape AIS data for gas carriers and fetch corresponding historical weather data.
2.  **Feature Engineering:** Calculate theoretical fuel consumption and to create a "physics-grounded" target variable.
3.  **Simulation:**
    * Develop a **GMM** on historical data to generate realistic scenarios.
    * Run a **Monte Carlo simulation ** to stress-test LCOT against fuel price volatility and weather delays.
4.  **Economic Analysis:** Applying maritime CCS cost formulas to derive the final LCOT distribution.

