# Power_BI_Cpk_analyasis_with_DAX_and_Python_Data_Distribution_Analysis
This dashboard integrates Power BI DAX with Python for advanced data distribution and Process Capability (Cpk) analysis. By automating statistical metrics and custom matplotlib visuals like boxplots and histograms, it empowers Advanced Manufacturing Engineers to rapidly assess process stability and optimize performance to meet strict tolerances.
# Power BI & Python: Automated Process Capability ($C_{pk}$) Dashboard

## 🎯 Overview
This project demonstrates the powerful integration of Power BI's dynamic DAX engine with Python's statistical visualization capabilities. Designed for Advanced Manufacturing Engineering, this dashboard moves beyond basic reporting to provide a fully automated, interactive environment for evaluating process health, stability, and adherence to specification limits.

## 🚀 Why This is Highly Useful
Traditional manufacturing analysis often requires exporting data into secondary statistical software (like Minitab or Excel) to generate capability reports. This dashboard eliminates that bottleneck by combining live data tracking with advanced statistical charting in one unified view.

* **Instant Process Evaluation:** Custom DAX measures automatically calculate Process Capability ($C_{pk}$) and standard deviation on the fly. As data is filtered by different timeframes, batches, or categories, the statistical metrics update instantly.
* **Overcoming Native Limitations:** Power BI's native visuals are limited for strict statistical analysis. By embedding Python (`matplotlib`), this tool unlocks high-fidelity engineering charts—like custom-scaled boxplots and histograms with fixed specification limits—directly within the report.
* **Proactive Problem Solving:** Engineers can visually and mathematically compare established processes (POR) against new experimental parameters (Evaluation) side-by-side. This makes it incredibly easy to identify variance, mean shifts, and out-of-spec trends before they cause production defects.
* **Scalable Framework:** While this specific view analyzes distributions, the underlying architecture (DAX statistical modeling + Python visualization) can be scaled to monitor any quantifiable parameter, making it a highly adaptable template for continuous improvement projects.

## 🛠️ Technical Stack
* **Power BI (DAX):** Handles data modeling and dynamic mathematical formulas (Mean, Standard Deviation, $C_{pk}$).
* **Python (`matplotlib` & `pandas`):** Processes the dynamically filtered datasets from Power BI to render customized, specification-bound visual distributions.

## 💡 Engineering Impact
This hybrid approach empowers teams to make rapid, data-driven decisions. Instead of spending hours wrangling data to create static capability reports, engineers can use this interactive tool to monitor process stability, justify process changes, and validate manufacturing optimizations with total confidence.
