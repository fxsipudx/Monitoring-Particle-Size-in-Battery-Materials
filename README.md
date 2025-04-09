# Particle Morphology Analyzer for Battery Materials

A lightweight Python toolkit to analyze particle shapes in **Scanning Electron Microscope (SEM)** images of battery electrode materials. This tool helps assess **particle size uniformity**, **elongation (eccentricity)**, and **smoothness (convexity)** — all crucial for quality control in lithium-ion battery manufacturing.

---

## 🧠 What It Does

- 📷 Reads grayscale SEM images of battery materials
- 🔍 Applies Gaussian blur and Otsu's thresholding to segment particles
- 📐 Extracts shape features for each particle:
  - **Area**
  - **Perimeter**
  - **Eccentricity** (how stretched)
  - **Convexity** (how smooth or jagged)
- 📊 Plots distribution histograms and scatter plots
- 🧾 Outputs a labeled table and **CSV report**
- 🖍️ Overlays particles with **IDs and contour drawings**, highlighting oversized ones in red
