# Dual-Phase-Solar-Grid-Optimization-Generation-Forecasting-and-Automated-Defect-Detection




## Business Problem:
Current solar energy grids suffer from two critical inefficiencies: environmental unpredictability and undetected hardware degradation.

First, because solar generation relies entirely on weather constraints, grid operators face critical **Supply/Demand Dislocations**. Midday generation surpluses are frequently wasted, while evening demand spikes cause severe power shortages. Operations lack the ability to accurately forecast short-term energy output based on localized meteorological conditions, making automated battery storage management impossible.

Second, when a grid *does* underperform, operators struggle to identify the root cause. **Hardware Eclipsing** (such as micro-cracks or dead zones within individual solar cells) drastically reduces system efficiency, but manually inspecting massive arrays for microscopic damage is costly and time-consuming.

**Our Solution:**
This project deploys a dual-phase Machine Learning architecture to create a self-optimizing, self-diagnosing solar grid:

1. **Predictive Generation Forecasting:** Utilizing historical meteorological data (Radiation, Sunshine, Air Temperature), we deploy a time-series forecasting model to predict grid `SystemProduction` 24 to 72 hours in advance, allowing automated systems to optimally route excess midday power into battery storage.
2. **Automated Cell Malfunction Detection:** Utilizing the ELPV dataset, we deploy a Convolutional Neural Network (CNN) to perform automated image processing on electroluminescence scans of the array. This isolates and flags malfunctioning cells, allowing maintenance teams to instantly pinpoint degraded hardware without manual inspection.

---

