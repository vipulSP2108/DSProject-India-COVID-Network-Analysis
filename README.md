# COVID-19 India Network & Spatial Analysis

![COVID-19 Motion Chart](india_report_only_figures/motion_chart.gif)

## How to Read the Motion Chart
This Rosling-style motion chart visualizes the trajectory of the COVID-19 pandemic across Indian states. 

**The Axes:**
* **X-Axis:** Total Confirmed Cases (Cumulative). This represents how far along in the pandemic a state is. (Logarithmic Scale)
* **Y-Axis:** New Daily Cases (7-day Average). This represents the current speed or "explosiveness" of the outbreak. (Logarithmic Scale)

**The Bubbles:**
* **Size:** Represents the constant population of the state. Huge bubbles are populous states like Maharashtra or Uttar Pradesh.
* **Color:** Represents geographic regions (North, South, East, West, Central, Northeast).

### The Narrative of the Movement
When you watch the animation, you are seeing the fundamental laws of network-driven transmission:

1. **Shooting Upwards (The Outbreak):** At the bottom-left, cases are low. When a bubble shoots straight UP, an explosive outbreak is starting. The daily cases are multiplying logarithmically.
2. **Moving Mostly Right & Hovering (The Core Pandemic):** Once the daily cases reach a peak capacity, the bubble stops going up and starts moving steadily to the right for 1-1.2 years. This is the tragic core of the pandemic—daily cases are consistently high, so the total cumulative cases (X-axis) just keeps grinding higher and higher over time. 
3. **Falling Downwards (The Burnout):** Finally, as herd immunity, interventions, or viral burnout take effect, the bubble plummets straight DOWN. The wave is over, but the state remains far to the right, permanently scarred by its cumulative toll.

Notice how the Hub states (Maharashtra, Delhi) lead the charge upwards, while peripheral states follow with a delay—proof of the network synchronization hypothesis discussed in this analysis.

---

## Project Overview
This repository contains the full analysis, data pipelines, and rigorous statistical tests validating the "Testing Disparity" and "Centrality-Synchronization" hypotheses regarding the spread of COVID-19 in India.

### Contents:
* `COVID19_India_Network_Analysis.ipynb`: The primary interactive data story and pipeline (runnable on Google Colab).
* `final_report_india.tex`: The formal academic submission manuscript.
* `india_report_only_figures/`: The isolated figures and interactive map files.

*Note: The maps generated in this repository suffer from known software projection errors regarding the boundaries of India. These are cartographic artifacts of the Folium/GeoJSON tools and are explicitly disclaimed in the formal report.*
