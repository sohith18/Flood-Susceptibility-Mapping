# Flood Susceptibility Mapping of Assam, India

This project focuses on developing a flood susceptibility mapping model for the state of Assam using a combination of GIS-based spatial analysis and machine learning techniques. The objective is to support disaster preparedness by identifying regions vulnerable to flooding based on historical and environmental data.

---

## Objective

To create a reliable and accurate predictive model for identifying flood-prone zones in Assam by integrating geospatial features with machine learning algorithms.

---

## Data Sources

The following publicly available datasets were used:

- [Bhuvan (NRSC)](https://bhuvan.nrsc.gov.in)
- [Bhoonidhi (NRSC)](https://bhoonidhi.nrsc.gov.in)
- [CHRS Rainfall Data](https://chrsdata.eng.uci.edu)
- [Open Government Data Portal (India)](https://data.gov.in)

---

## Features Extracted

The model was trained on the following geospatial and environmental features derived using QGIS and remote sensing tools:

- Slope
- Topographic Roughness Index (TRI)
- Topographic Position Index (TPI)
- Distance from River
- Rainfall
- NDVI (Normalized Difference Vegetation Index)
- Land Use / Land Cover (LULC)

---

## Methodology

1. Historical flood inventory was created using known flood-prone and flood-free locations (100 each).
2. Feature extraction was performed using QGIS tools and raster processing.
3. Machine learning models were trained and validated using a stratified split (159 training points, 41 testing points).
4. Performance was assessed using accuracy metrics, confusion matrices, and PA/UA scores.

---

## Models and Performance

| Model                        | Accuracy (%) |
|-----------------------------|--------------|
| Random Forest               | 97.50        |
| Support Vector Machine (SVM)| 88.09        |
| Multi-Layer Perceptron (MLP)| 85.53        |

Random Forest yielded the best results in terms of classification accuracy, outperforming both SVM and MLP models.

---

## Results

- Successfully classified flood-prone regions with high confidence using spatial and temporal features.
- Random Forest model demonstrated strong generalization with 97.5% accuracy.
- The final susceptibility map enables visual interpretation and planning for flood mitigation.

---

## Visualizations and Resources

Complete results, maps, and datasets are accessible at the following location:

🔗 [Flood Mapping Resources (OneDrive)](https://iiitbac-my.sharepoint.com/:f:/g/personal/siddharth_maramreddy_iiitb_ac_in/EknJ2fb4i3FPnTzT_l-Cc_MBtPqr3xqY1pNMBrNdeNpT2Q?e=hj20o6)

---

## Team Members

- **Sai Venkata Sohith Gutta**
- **Maramreddy Siddharth Reddy**
- **Shreyas S**

---

## Tools Used

- QGIS 3.x
- Python (NumPy, Pandas, Scikit-learn)
- Remote Sensing & Raster Processing
- CSV, GeoTIFF, and Shapefile-based spatial analysis

---

## Acknowledgements

This project was developed as part of the GIS course at the International Institute of Information Technology, Bangalore. The team acknowledges the use of open government datasets and QGIS software in the successful execution of this work.
