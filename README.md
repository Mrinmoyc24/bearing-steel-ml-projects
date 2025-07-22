# bearing-steel-ml-projects
**Predicting Carbide Banding & Interface Stability from SEM‑Derived Features**

This repository provides a complete end‑to‑end machine‑learning workflow for two key quality metrics in GCr15 bearing steel:
1. **Carbide Banding**: Low / Moderate / High  
2. **Interface Stability**: Stable / Unstable  

**Notebook outline:**
  1. **Data loading and exploration**
  2. **Pre-processing and feature engineering**
  3. **Model training pipeline:**
      A. K-nearest Neighbors
      B. Random Forest
      C. XGBoost
  4. **Evaluation and Metrics**
      A. Accuracy, Precision/Recall, ROC‑AUC
      B. Confusion Matrices
  5. **Visualization**
      A. Elbow & Silhouette Plots
      B. ROC Curves
      C. Feature‑Importance Charts


**Best accuracy:**
  1. Carbide Banding: 87.3% (Random Forest)
  2. Interface Stability ROC‑AUC: 0.92 (XGBoost)


**Top Feature:**
  1. Cooling rate
  2. Chromium content
  3. Austenization temperature


**Contact:**
Mrinmoy Chanda
M.Tech, Materials Science, IIT Kanpur
email: mrinmoyc24@iitk.ac.in
