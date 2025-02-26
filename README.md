# **Battery Capacity Prediction - ThinkClock Internship Assignment** 🚀

## **📌 Project Overview**  
This repository contains the solution for the **ThinkClock Python Developer Internship Assignment**, focusing on **battery health analytics** using **Electrochemical Impedance Spectroscopy (EIS) data**. The tasks completed in this project include:

- **Task A: 3D Visualization of Impedance Evolution**  
  - Generated a **3D plot** to show how battery impedance (R(Z), Im(Z)) evolves with cycle aging.
- **Task B: Incremental Capacity Analysis (ICA)**  
  - Computed **dQ/dV vs. Voltage** and plotted **incremental capacity shifts** over battery cycles.
- **Task C: Machine Learning Model for Battery Capacity Prediction**  
  - Trained a **Gradient Boosting Regressor (GBR)** to predict battery capacity from EIS features.

## **🔧 Tech Stack**  
- **Python (NumPy, Pandas, SciPy)**  
- **Machine Learning (Scikit-learn, XGBoost)**  
- **Data Visualization (Matplotlib, Seaborn, Plotly)**  

## **📂 File Structure**  
```
📁 Battery-Capacity-Prediction/
│── 📄 Python_Developer_Assignment.ipynb  # Jupyter Notebook implementation
│── 📄 Battery_Capacity_Prediction_Report.docx  # Detailed report
│── 📄 Assignment_PythonDeveloper.pdf  # Original assignment document
│── 📁 Data/  # Dataset files (.mat)
│── 📁 Plots/  # 3D EIS, ICA, and prediction results
│── 📁 Models/  # Trained ML model (if saved)
```

## **🚀 How to Run**  
1. **Clone this repo:**  
   ```bash
   git clone https://github.com/your-username/Battery-Capacity-Prediction.git  
   cd Battery-Capacity-Prediction  
   ```  
2. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt  
   ```  
3. **Run Jupyter Notebook:**  
   ```bash
   jupyter notebook  
   ```  

## Key Findings  
- **Battery aging leads to increased impedance** (visualized in Task A).  
- **Incremental capacity analysis confirms degradation over time** (Task B).  
- **Machine learning model achieves R² = 0.9767, accurately predicting battery capacity** (Task C).  


