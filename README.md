# Surface Telemetry Analysis

This project demonstrates how device telemetry (CPU, memory, temperature, fan RPM, battery wear, and error logs) can be analyzed to detect anomalies and forecast device errors.

The analysis is based on **synthetic data** designed to mimic real-world Surface device behavior.

## Project Steps
1. Generate synthetic telemetry dataset  
2. Explore trends and visualize metrics  
3. Detect anomalies (thermal spikes, error bursts) using **Isolation Forest**  
4. Forecast next-hour error rates with **Gradient Boosting**  
5. Translate results into **product team recommendations**

## Why It Matters
For hardware and software teams, telemetry helps answer:  
- When are devices running outside safe bounds?  
- Can we predict failures before they impact users?  
- Which components (CPU, battery, fan) contribute most to errors?  

## Files
- `surface.ipynb` → Colab notebook with full code and plots  
- `surface.pdf` → Exported notebook for easy review  

## Sample Output
Example anomaly detection plot (red = anomaly):  
*(insert plot image here if you save one with `plt.savefig("anomaly_plot.png")`)*

---

**Note:** All data is synthetic and for demonstration purposes only.
