# Tsetse Wing Morphology Dynamics: Automated Landmark Detection and Time Series Analysis

This repository contains the project files for the study titled **Tsetse Wing Morphology Dynamics: Automated Landmark Detection and Time Series Analysis**. The primary focus of this study is to use machine learning and deep learning techniques to automate the identification of landmarks on tsetse fly wings, analyse morphological variations over time, and examine correlations with environmental factors.

## Repository Structure

## 1. Project Report

**19480105_Final_Report.pdf**: The research report of the project including methodology, results, and discussion.

## 2. Model Scripts

Contains Jupyter Notebook files used for implementing the machine learning models, data analysis and visualisation.

### Scripts:

- **1.vgg16_v22.ipynb**: Training the VGG16 model for classification of tsetse fly wing images.
- **2.classify_v22.ipynb**: Classification of tsetse fly wing images using the VGG16 model.
- **3.regress_v22.ipynb**: Regression model for wing landmark localisation.
- **4.regress_images_v22.ipynb**: Generates images with superimposed landmarks for visual inspection.
- **5.plots_v22.ipynb**: Generates individual page scatter plots for correlation analysis.
- **6.Time-series-analysis.ipynb**: Analyses time series data to correlate wing morphology changes with environmental data.

These scripts can be run using Jupyter Notebook on a local installation of Anaconda.

## 3. Data Spreadsheets

Contains csv data files with tsetse fly and environmental data needed for analysis.

### Files:

- **nuhrvol22.xlsx**: Contains specific biological data for Volume 22.
- **Logger daily means T RH SatDef NDVI rain.xlsx**: Contains environmental data used in time-series analysis.
- **Vols202122MorphBiolMetData27_Aug_2024.xlsx**: Provides descriptive biological and morphological data for Volumes 20, 21 and 22.

## 4. Image Data

The primary image dataset, Volume 22, containing tsetse fly wing images, is hosted on Dryad and can be accessed via [Dryad](https://doi.org/10.5061/dryad.wstqjq2wv) .

## Requirements

- **Python 3.11.7**
- **Jupyter Notebook** (available through Anaconda or directly on Jupyter)
- **Key Libraries**: Pytorch, torchvision, numpy, pandas, matplotlib, TensorFlow, Keras
  
## Running the Scripts

### Model Execution:

- Open each .ipynb notebook in Jupyter Notebook.
- Run the notebooks sequentially to follow the research workflow.
- Ensure that the data files in the **Data Spreadsheets** folder are accessible in the same directory as the notebooks.

### Data Access:

- The environmental and morphological data spreadsheets are included in this repository under the **Data Spreadsheets** folder.
- The main image dataset (Volume 22) must be downloaded from Dryad.
