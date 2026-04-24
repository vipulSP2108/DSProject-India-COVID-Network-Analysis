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

1. **Shooting Upwards (The Wave):** At the start of a wave, cases are low. When a bubble shoots mostly UP, an explosive outbreak is starting. The daily cases are multiplying logarithmically.
2. **Moving Right & Peaking (The Pivot):** As the wave hits its peak, the explosive vertical growth stops. The bubble pivots, moving horizontally to the right as the massive daily caseload adds swiftly to the total cumulative cases (X-axis).
3. **Falling Downwards (The Burnout):** As the wave subsides due to interventions, viral burnout, or immunity, the bubble plummets DOWN. The massive wave is over, but the state is now pushed far to the right, permanently scarred by its cumulative toll. Successive waves repeat this cycle, forming multiple loops.
4. **The Logarithmic Wall (The Visual Compression of 2021-2022):** You will notice the bubbles fly from left to right extremely fast in 2020, but then seem to hit a "wall" and stay huddled in a small horizontal space for 2021 and 2022. This is the effect of the logarithmic X-axis. Going from 1,000 to 100,000 early cases covers tremendous visual distance, but once a state has millions of cumulative cases, absorbing another massive wave of 2 million cases barely moves it to the right.

Notice how the Hub states (Maharashtra, Delhi) lead the charge upwards, while peripheral states follow with a delay—proof of the network synchronization hypothesis discussed in this analysis.

---

## Project Overview
This repository contains the full analysis, data pipelines, and rigorous statistical tests validating the "Testing Disparity" and "Centrality-Synchronization" hypotheses regarding the spread of COVID-19 in India.

### Contents:
* `COVID19_India_Network_Analysis.ipynb`: The primary interactive data story and pipeline (runnable on Google Colab).
* `final_report_india.tex`: The formal academic submission manuscript.
* `india_report_only_figures/`: The isolated figures and interactive map files.

*Note: The maps generated in this repository suffer from known software projection errors regarding the boundaries of India. These are cartographic artifacts of the Folium/GeoJSON tools and are explicitly disclaimed in the formal report.*
