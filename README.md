Crop Discrimination Using Machine Learning and GEE

This project leverages multi-sensor remote sensing data and machine learning algorithms to classify major crops over Udham Singh Nagar, Uttarakhand, using Google Earth Engine (GEE). The system integrates Sentinel-1 (microwave) and Sentinel-2 (optical) imagery and applies multiple ML models to generate high-accuracy Land Use Land Cover (LULC) maps for agricultural monitoring.

📌 Overview

Location: Udham Singh Nagar, Uttarakhand, India

Timeframe: June – October 2023 (cropping season)

Goal: Accurately discriminate between rice, sugarcane, and other land covers using satellite imagery

🧠 Machine Learning Models Used

Random Forest (RF)

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Classification and Regression Tree (CART)

Gradient Boosted Machine (GBM)

Ensemble Model (Majority Voting)

🛰️ Datasets

Sentinel-2 (Optical): Bands B2, B3, B4, B11, B12

Sentinel-1 (Microwave): VH polarization

Ground Truth: Field survey and manual annotations

Indices Computed: NDVI, EVI, NDBI

⚙️ Methodology

Preprocessing: Filtering, mosaicking, and reducing noise in satellite imagery

Feature Engineering: Generating vegetation and urban indices

Training & Testing: 70/30 split for model training and validation

Evaluation: Confusion matrix, overall accuracy, user’s accuracy, and kappa coefficient

Ensembling: Majority voting across top-performing classifiers

📈 Key Results

Highest Accuracy: 90.25% (ensemble classifier)

Optical + Microwave Fusion improved accuracy by 2–5% over optical-only data

Rice occupied ~98% of the classified crop area; Sugarcane ~2%

Temporal indices like NDVI and EVI aligned with crop phenology, improving classification

📊 Visualizations

Classifier performance across months

Final LULC maps with crop-specific classifications

Ensemble outputs for robust mapping
