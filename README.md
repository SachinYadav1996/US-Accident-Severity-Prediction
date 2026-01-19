# US Road Accident Severity Analysis & Prediction
An end-to-end Machine Learning pipeline to analyze and predict accident severity using a massive dataset of 7.7 million records.

## 📌 Project Overview
This project focuses on identifying the key factors contributing to road accident severity across the United States. By leveraging a multi-gigabyte dataset, the model predicts the impact of an accident on traffic (Severity levels 1-4) based on environmental, temporal, and geospatial features.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Decision Tree, Logistic Regression, Naive Bayes)
* **Visualization:** Matplotlib, Seaborn
* **Geospatial Processing:** KMeans Clustering for coordinate analysis

## 🚀 Key Engineering Highlights
* **High-Volume Data Handling:** Processed and cleaned a dataset of **7.7 million records**, implementing strategic sampling of 1.2M rows for balanced training.
* **Advanced Feature Engineering:**
    * **Geospatial:** Converted Latitude/Longitude to 3D Cartesian coordinates and applied **KMeans Clustering** to identify high-risk accident zones.
    * **Temporal:** Implemented sine/cosine transformations for cyclical features (Hour, Month) to preserve seasonal patterns.
    * **High-Cardinality Encoding:** Managed thousands of unique cities and streets using frequency encoding.
* **Performance:** Achieved **~85% Test Accuracy** using a Decision Tree Classifier, significantly outperforming the linear baseline.

## 📊 Results & Insights
* **Infrastructural Impact:** Proximity to traffic signals and junctions showed a high correlation with severity levels.
* **Model Comparison:** While Logistic Regression provided a baseline of 77%, the Decision Tree model captured the non-linear complexities of accident data more effectively.

---
