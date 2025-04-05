# 🌍 Congo Basin Mining Concessions Analysis

![image alt]()

This project explores mining concession data in the Congo Basin using geospatial and data analysis tools in Python. The goal is to visualize and understand the distribution, type, and scale of mining activity across Central Africa, with a focus on transparency and environmental awareness.

## 📁 Project Structure

- `Basin.ipynb` — Main analysis notebook containing geospatial data cleaning, visualization, and insights.
- `Congo_Basin_Mining_Concessions.gpkg` — GeoPackage file used as the primary data source (stored in Google Drive).

## 🔧 Technologies Used

- **Python 3.x**
- [GeoPandas](https://geopandas.org) — for handling geospatial vector data
- [Pandas](https://pandas.pydata.org) — for general data manipulation
- [Matplotlib](https://matplotlib.org) — for creating visualizations
- [Google Colab](https://colab.research.google.com) — for running and sharing the notebook

## 📌 Main Steps

### 1. Data Loading
- GeoPackage file containing mining concessions is loaded from Google Drive using GeoPandas.

### 2. Data Cleaning
- Columns of interest are selected: country name, operator, type, resource, area, etc.
- Missing values are replaced with `"UNKNOWN"` for consistency.

### 3. Visualization
- For Images I used QGIS

## 📊 Goals & Applications

- **Environmental Transparency**: Highlighting industrial expansion in a sensitive ecological region.
- **Policy & Advocacy**: Supporting data-driven discussions about the impact of mining on biodiversity and local communities.
- **Research**: Creating a clean, analyzable dataset for environmental economists, conservationists, and NGOs.

## 📌 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com).
2. Mount your Google Drive to access the dataset.
3. Step through each cell to load, clean, and visualize the data.

## 🤝 Acknowledgments

- Original dataset sourced from collaborative environmental monitoring efforts.
- Thanks to the [Earth Insight](https://www.earth-insight.org/) team for inspiration and background.

