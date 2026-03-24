# Wine Anomaly Detection

## Project Overview
This project applies unsupervised anomaly detection methods to the Wine dataset using Python and scikit-learn.

The main objective is to identify unusual observations and compare how different anomaly detection algorithms behave on the same dataset.

## Methods Used
- Isolation Forest
- Local Outlier Factor (LOF)
- Principal Component Analysis (PCA) for visualization

## Workflow
- Load and preprocess the Wine dataset
- Standardize features
- Reduce dimensionality using PCA for visualization
- Detect anomalies using Isolation Forest
- Detect anomalies using Local Outlier Factor
- Compare the results from both methods

## Visualizations
- PCA projection of the dataset
- Isolation Forest anomaly detection plot
- LOF anomaly detection plot
- Comparison chart of detected anomalies

## Key Insights
- Both methods were able to detect unusual observations in the dataset
- Isolation Forest and LOF may flag different points as anomalies
- PCA is useful for visualizing high-dimensional anomaly detection results
- Comparing multiple methods helps build a better understanding of outlier behavior

## Tools and Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Learning Outcomes
Through this project, I improved my understanding of:
- anomaly detection techniques
- unsupervised learning workflows
- PCA-based visualization
- comparing machine learning models on the same dataset

## Repository Contents
- `wine_anomaly_detection.ipynb` — main notebook
- project visualizations for presentation and posting

## Conclusion
This project demonstrates how anomaly detection methods can be applied to structured data and highlights the importance of comparing algorithms when identifying unusual observations.

## Author
Muhammad Umair Bashir
