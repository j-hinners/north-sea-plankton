
# North Sea Plankton Analysis

This project explores the relationship between plankton community composition and key environmental variables in the North Sea using exploratory time series analysis, principal component analysis (PCA), and correlation analysis.

---

## Project Overview

Plankton communities are essential indicators of marine ecosystem health. In this analysis, a dataset of **hypothetical** North Sea plankton samples collected during two research cruises (June and August) was used to:

- Visualize temporal shifts in plankton group abundance
- Identify environmental drivers using PCA
- Investigate pairwise correlations between environmental factors and plankton taxa

The analysis was conducted in a Jupyter Notebook and includes scientific interpretation and domain-relevant visualizations.

---

## Methods

The following techniques were applied:

- Data wrangling using `pandas`
- Time series visualization with `seaborn` and `matplotlib`
- Principal Component Analysis (PCA) with `scikit-learn`
- Correlation matrix using `scipy.stats` and `seaborn` heatmaps
- Z-score filtering to exclude outliers in PCA

---

## Repository Structure

 ```bash
north-sea-plankton/
├── North_Sea_Plankton_Analysis.ipynb # Jupyter Notebook with full analysis
├── North_Sea_Plankton_Analysis.html # Exported HTML version (preview)
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── NorthSeaPlanktonData.csv # Dummy dataset
 ```
---

## Key Findings (Summary)

- A clear seasonal shift in plankton composition is observed between June and August.
- PCA reveals distinct environmental signatures for both sampling periods.
- Certain plankton groups (e.g., Plankton B) show strong correlations with temperature and silicate levels, highlighting nutrient dependencies.

> *Note: This project uses a simulated dataset for demonstration purposes.*

---

## Getting Started

To reproduce the analysis:


1. Clone the repository:

   ```bash
   git clone https://github.com/j-hinners/north-sea-plankton.git
   cd north-sea-plankton
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter lab
   ```

Replace the dataset path if needed.

---

## Requirements

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy

(Also included in `requirements.txt`)

---

## Contact

For questions or collaboration requests, please contact me via [LinkedIn](https://www.linkedin.com/in/dr-jana-hinners-75bb6712a/).

