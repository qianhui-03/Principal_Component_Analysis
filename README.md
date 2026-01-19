# Principal Component Analysis (PCA) Visualization
## Overview
This project explores PCA using sklearn and focuses on visualizing data. Visualization ideas were inspired by the article “5 PCA Visualizations You Must Try in Your Next Data Science Project” (Towards Data Science).
The `Wine Quality Dataset` from Kaggle is used in this project.

## Objectives
1. Apply PCA to features.
2. Understand explained variance and principal components.
3. Visualize data in 2D and 3D PCA space.
4. Interpret feature loadings using biplots and loading bar charts.
5. Compare model training efficiency.

## Dataset
- Name: Wine Quality Dataset
- Source: Kaggle
- Features: Physicochemical properties
- Target: Wine quality score (integer)

## Methodology
1. Data Preprocessing
    - Feature-target separation
    - Standardize features 
2. Dimensionality Reduction
    - Fit PCA on standardized features
3. Visualization 
    - Explained variance plot
    - Cumulative explained variance plot
    - 2D and 3D PCA scatter plot
    - Attribute biplot
    - Loading score plot
4. Model Training 

## Insights
- The first few principal components capture the majority of variance in the dataset
- Alcohol and density-related features contribute strongly to early components
- PCA provides moderate class separation but is not fully discriminative for wine quality
- Visualization highlights correlated features and dominant variance directions

## Key Takeaways
- PCA maximizes variance, not class separability.
- Standardization is important before applying PCA.
- Loadings reveal the importance of original feature.

## Why PCA matters
PCA helps reduce feature redundancy, speeds up model training and improves interpretability in high-dimensional datasets. It is commonly used in data preprocessing and exploratory analysis.

## Tech Stack
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Project Structure
```
├── data/
│   └── WineQT.csv 
├── PCA_Visualization.ipynb
├── README.md
```

## Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/qianhui-03/Principal_Component_Analysis.git
cd Principal_Component_Analysis
pip install -r requirements.txt
```

## References
- **5 PCA Visualizations You Must Try On Your Next Data Science Project** 
<a href="https://towardsdatascience.com/5-pca-visualizations-you-must-try-on-your-next-data-science-project-148ec3d31e4d/" target="_blank">
PCA Visualizations You Must Try
</a>
- Kaggle Wine Quality Dataset