# Data Processing & Visualization Practice

## Overview

This project is part of my preparation for a SWE internship interview at Precision Neuroscience. Here, I reproduce and analyze data processing and visualization techniques described in the **Handwriting Neuroprosthesis** paper by Willett et al. The goal is to demonstrate my ability to handle complex neural datasets and create insightful visualizations.

## Objectives

1. Learn and apply neural data preprocessing techniques:
   - Spike detection and thresholding.
   - Dimensionality reduction using PCA.
   - Time-warping for alignment.
2. Create clear and meaningful visualizations:
   - Neural trajectory clustering using PCA/t-SNE.
   - Reconstructed handwriting trajectories from neural data.
   - Heatmaps of neural activity patterns.

## Files

- **Notebooks**:

  - `01_load_and_explore.ipynb`: Loads and explores the neural dataset, including raw signal visualization.
  - `02_preprocessing.ipynb`: Implements spike detection, smoothing, dimensionality reduction, and time-warping.
  - `03_visualization.ipynb`: Creates visualizations such as neural trajectory plots and handwriting reconstructions.

- **README.md**: This file, providing context and an overview of the project.

## Key Highlights

- **Spike Detection**: Extracted multiunit activity from neural voltage traces.
- **Dimensionality Reduction**: Used PCA to identify dominant neural activity patterns.
- **Time-Warping**: Aligned neural signals across trials to remove timing variability.
- **Visualizations**:
  - Clustered neural activity for distinct characters.
  - Reconstructed pen-tip velocity to visualize handwriting.

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/allensu02/handwritingBCI.git
   cd handwritingBCI/data_processing_and_visualization_practice
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
