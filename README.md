# 🌊 Flood Susceptibility Mapping — Assam, India

A GIS + Machine Learning project aimed at identifying flood-prone zones in the state of Assam using geospatial features and predictive modeling.

---

## 📌 Problem Statement

Assam is highly vulnerable to seasonal flooding due to the Brahmaputra River and heavy monsoon rainfall. Accurate identification of flood-prone zones is essential for proactive disaster management and mitigation.

---

## 🎯 Objective

To develop a machine learning model that accurately predicts flood susceptibility using geospatial features, thereby assisting planners in risk assessment and emergency preparedness.

---

## 🧩 Features Used

Derived from DEMs and remote sensing data:

- **Slope**
- **Topographic Roughness Index (TRI)**
- **Topographic Position Index (TPI)**
- **Distance from River**
- **Rainfall**
- **NDVI (Vegetation Index)**
- **Land Use / Land Cover (LULC)**

---

## 🗺️ Data Sources

- [Bhuvan (NRSC)](https://bhuvan.nrsc.gov.in)
- [Bhoonidhi (NRSC)](https://bhoonidhi.nrsc.gov.in)
- [CHRS Rainfall](https://chrsdata.eng.uci.edu)
- [Open Government Data Portal](https://data.gov.in)

---

## 🧠 Models Implemented

| Model                        | Accuracy (%) | Notes                     |
|-----------------------------|--------------|---------------------------|
| 🟢 Random Forest             | 97.50        | Best performance overall  |
| 🔵 Support Vector Machine    | 88.09        | Strong generalization     |
| 🟡 Multi-Layer Perceptron    | 85.53        | Neural model baseline     |

---

## 📌 Methodology

1. Extracted geospatial features using **QGIS**.
2. Created a flood inventory dataset with 200 points (100 flooded, 100 unflooded).
3. Trained ML models using 159 points and tested on 41.
4. Evaluated results using accuracy, confusion matrix, Producer's and User's Accuracy (PA/UA).

---

## ✅ Key Highlights

- Leveraged both spatial and statistical techniques for flood risk prediction.
- Random Forest achieved the highest test accuracy of **97.5%**.
- Validated performance using real-world data and visual inspection.
- Built upon methodologies referenced from research in India and Nigeria.

---

## 📂 Dataset & Resources

📁 [Access dataset, maps, and visualizations (OneDrive)](https://iiitbac-my.sharepoint.com/:f:/g/personal/siddharth_maramreddy_iiitb_ac_in/EknJ2fb4i3FPnTzT_l-Cc_MBtPqr3xqY1pNMBrNdeNpT2Q?e=hj20o6)

---

## 👥 Team

- **Sai Venkata Sohith Gutta**  
- **Maramreddy Siddharth Reddy**  
- **Shreyas S**
