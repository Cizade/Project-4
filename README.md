# Interactive Global Prosperity Rankings Index Visualization

## Project Overview

This project aims to deliver a comprehensive, interactive visualization tool designed to evaluate and compare countries based on a diverse set of indicators such as GDP, life expectancy, military expenditures, and governance metrics. The primary goal is to provide intuitive insights into global performance trends and facilitate an accessible platform for understanding complex international data.

## Goals

* **Data Collection and Cleaning:** Gather relevant country-level economic, demographic, and governance data. Thoroughly clean and prepare the data for analysis.
* **Data Scaling and Feature Engineering:** Apply standardization techniques to ensure comparability across indicators.
* **Dimensionality Reduction and Clustering:** Implement Principal Component Analysis (PCA) to simplify the data structure, followed by clustering analysis to categorize countries into meaningful groups.
* **Interactive Visualization:** Create an engaging, web-based interactive map that visually represents clusters, rankings, and key indicators, supplemented with dynamic charts highlighting top-performing countries in each category.

## Processes and Methodology

### 1. Data Acquisition

* Sourced comprehensive datasets covering economic, demographic, and governance indicators from reputable public repositories.

### 2. Data Preparation

* Conducted rigorous data cleaning procedures including handling missing values, aligning data formats, and standardizing identifiers (ISO3 codes).

### 3. Data Scaling and PCA

* Applied standard scaling techniques to ensure equitable weighting across diverse indicators.
* Conducted PCA to reduce dimensionality, capturing the majority of variance with fewer composite indicators.

### 4. Clustering Analysis

* Explored multiple clustering methods, including K-Means and DBSCAN, ultimately selecting clusters that most clearly differentiated countries based on the PCA results.
* Generated descriptive labels and rankings for each cluster to facilitate interpretation.

### 5. Composite Scoring and Rankings

* Developed composite scores from PCA outcomes to provide country-level rankings, enabling direct comparison across global indicators.

### 6. Interactive Visualization

* Utilized Leaflet and Chart.js to build a responsive web application featuring:

  * Interactive choropleth maps dynamically colored based on user-selected indicators.

## Project Usage

1. Open `map.html` locally using a simple HTTP server (such as Python's built-in HTTP server).
2. Upload the final merged CSV data file (`country_data_merged.csv`) via the provided interface or configure direct loading for streamlined use.
3. Interact with the dropdown to explore various country indicators and rankings, with real-time visual updates and charts.

## Technologies Used

* **Python:** Pandas, NumPy, Scikit-learn (for data analysis, scaling, PCA, clustering)
* **JavaScript:** Leaflet, Chart.js (interactive visualization)
* **HTML/CSS:** Structure and style for web visualization interface

## Next Steps and Enhancements

* Integrate additional indicators as data availability expands.
* Further refine interactive elements, adding features such as detailed country profiles and trend analysis.
* Optimize performance for handling larger datasets.

## Contributing

Contributions, improvements, and feedback are welcomed! Please open issues or submit pull requests with clear explanations of your proposed enhancements.
