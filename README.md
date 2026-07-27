# Large-Scale Geographic Consumer Clustering & High-Dimensional Visualizations

## Project Overview

This project demonstrates the application of Machine Learning, Geographic Information Systems (GIS), and Data Visualization techniques to analyze large-scale real-estate data. The objective is to identify consumer housing market segments based on geographical locations and property characteristics. The generated clusters help organizations understand regional market trends and support strategic business expansion planning.

---

## Problem Statement

Real-estate organizations handle thousands of property records distributed across different geographical regions. Analyzing these records manually is time-consuming and inefficient.

This project automatically groups similar properties into meaningful clusters using machine learning algorithms and visualizes them through interactive maps and high-dimensional plots.

---

## Objectives

* Perform consumer segmentation using K-Means Clustering.
* Analyze housing markets based on multiple property attributes.
* Reduce high-dimensional data using Principal Component Analysis (PCA).
* Visualize clusters using interactive Plotly charts.
* Display clustered properties on an interactive geographical map.
* Generate business insights for regional expansion planning.

---

## Features

* Real-estate dataset preprocessing
* Data cleaning and normalization
* K-Means clustering
* Principal Component Analysis (PCA)
* Interactive Plotly visualization
* Interactive Folium map
* Heatmap visualization
* Marker clustering
* Cluster-wise statistical analysis
* Export clustered dataset

---

## Technologies Used

### Programming Language

* Python 3.x

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Plotly
* Folium
* UMAP (Optional)
* IPython

---

## Dataset

The project uses a Chennai Real Estate dataset containing property information.

### Dataset Columns

* PropertyID
* Locality
* Latitude
* Longitude
* Price
* Area
* Bedrooms
* Bathrooms
* PropertyAge
* Parking
* PropertyType

---

## Project Workflow

### Step 1 – Data Collection

Load the Chennai real-estate dataset.

### Step 2 – Data Preprocessing

* Remove missing values
* Convert numerical columns
* Standardize selected features

### Step 3 – Feature Selection

The following features are used for clustering:

* Price
* Area
* Bedrooms
* Bathrooms
* PropertyAge

### Step 4 – Consumer Clustering

Apply the K-Means algorithm to classify properties into multiple market segments.

### Step 5 – Dimensionality Reduction

Reduce multidimensional data into two principal components using PCA for visualization.

### Step 6 – Interactive Visualization

Create:

* PCA Scatter Plot
* Interactive Plotly Graph
* Folium Geographic Map
* Heat Map

### Step 7 – Cluster Analysis

Generate cluster-wise statistics including:

* Average Price
* Average Area
* Average Bedrooms
* Average Bathrooms
* Average Property Age

---

## Machine Learning Algorithm

### K-Means Clustering

K-Means partitions the dataset into groups where properties inside each cluster are more similar to one another than to properties in other clusters.

---

## High-Dimensional Visualization

Principal Component Analysis (PCA) transforms multiple property features into two principal components while preserving most of the important information, enabling easier visualization of clusters.

---

## Interactive Map Features

* Color-coded clusters
* Clickable property markers
* Property information popups
* Heatmap of property density
* Zoom and pan support
* Marker clustering

---

## Project Outputs

The project generates:

* `clustered_properties.csv`
* `housing_clusters_map.html`
* PCA Scatter Plot
* Interactive Plotly Visualization
* Cluster Summary Report

---

## Folder Structure

```
Project/
│
├── Large_Scale_Geographic_Consumer_Clustering.ipynb
├── Chennai_Real_Estate_Dataset.csv
├── clustered_properties.csv
├── housing_clusters_map.html
├── README.md
```

---

## Installation

Install the required packages:

```bash
pip install pandas numpy matplotlib scikit-learn plotly folium umap-learn
```

---

## How to Run

1. Download the project files.
2. Place `Chennai_Real_Estate_Dataset.csv` in the project folder.
3. Open the notebook (`.ipynb`) using Jupyter Notebook, JupyterLab, or VS Code.
4. Run all cells sequentially.
5. View:

   * PCA visualization
   * Plotly interactive graph
   * Interactive Folium map
   * Cluster summary

---

## Expected Results

* Automatic grouping of similar housing markets.
* Clear visualization of regional consumer segments.
* Interactive exploration of clustered properties.
* Business insights for expansion planning and investment decisions.

<img width="844" height="547" alt="image" src="https://github.com/user-attachments/assets/3bc7de8c-da01-4b88-8a70-5bc156615838" />

<img width="844" height="547" alt="image" src="https://github.com/user-attachments/assets/8ec1a079-c61f-48d8-89b3-b0e282417510" />

---

## Applications

* Real-estate analytics
* Consumer segmentation
* Smart city planning
* Property investment analysis
* Market trend analysis
* Geographic business expansion
* Urban development planning

---

## Future Enhancements

* DBSCAN and Hierarchical Clustering
* UMAP and t-SNE visualizations
* Live data integration
* Streamlit/Dash dashboard
* Real-time property recommendations
* Predictive price forecasting
* Deployment on cloud platforms

---

## Conclusion

This project demonstrates how machine learning and geographic visualization can transform large-scale real-estate data into meaningful consumer market segments. The combination of clustering, dimensionality reduction, and interactive mapping enables data-driven decision-making for organizations involved in real-estate investment, urban planning, and corporate expansion.

---

## Author

**Name:** Pradeepa

**Project Title:** Large-Scale Geographic Consumer Clustering & High-Dimensional Visualizations

**Technology Stack:** Python, Pandas, NumPy, Scikit-learn, PCA, Plotly, Folium, Matplotlib
