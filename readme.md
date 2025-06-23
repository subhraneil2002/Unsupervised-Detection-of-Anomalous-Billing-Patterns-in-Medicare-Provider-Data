# 🩺 Unsupervised Healthcare Fraud Detection

Anomaly detection project using Isolation Forest and Autoencoder models on Medicare provider data (~9M records) to identify fraudulent billing patterns without labeled data.

## 📊 Dataset
- **Source**: [Medicare Provider Utilization and Payment Data](https://data.cms.gov/)
- ~9 million rows, 28 features including services, charges, and payment information.
- Due to data sensitivity, raw data is not uploaded. Please download it directly from the CMS website.

## 🛠️ Features
- Feature engineering: Created financial ratios like `charge-to-allowance`, `payment efficiency`, `charge per service`, etc.
- Dimensionality reduction using PCA (95% variance retained with 7 components).
- Trained Isolation Forest and Autoencoder to detect anomalies.
- Silhouette score (Autoencoder): **0.91**, flagged ~1% of records as anomalies.

## 📈 Models Used
- 📌 Isolation Forest
- 📌 Deep Autoencoder (Keras)
- 📌 PCA for visualization

## 🗂️ Project Structure
