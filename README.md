# Machine Learning - Clustering and Star Classification - Practice 2

![UC3M Logo](https://assets.onthehub.com/attachments/15/401d138e-5b75-de11-b7f9-0030487d8896/3d13020c-f96c-4a26-8c47-b617961e9c81.jpg)

## Table of Contents
- [About the Project](#about-the-project)
- [Objective](#objective)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Dataset Information](#dataset-information)
- [Author](#author)

## About the Project
This project implements unsupervised machine learning techniques for clustering stars based on their characteristics. It is part of the *Machine Learning* course at **Universidad Carlos III de Madrid (UC3M)**. The clustering process determines the types of stars using data such as temperature, luminosity, radius, and spectral class.

## Objective
The goal of this project is to:
- Preprocess and normalize data to prepare it for clustering algorithms.
- Apply various clustering techniques, including:
  - K-Means
  - DBSCAN
  - Hierarchical clustering
- Evaluate and visualize clustering results to infer star classifications.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** 
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Clustering: `sklearn`, `scipy`
  - Dimensionality Reduction: `PCA`, `TSNE`

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/rosareyes/AA24-100434072-P2.git
    cd AA24-100434072-P2
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook in Jupyter or Google Colab:
    ```bash
    jupyter notebook AA24_100434072_P2.ipynb
    ```

## Dataset Information
The dataset includes the following columns:
- **Temperature**: Surface temperature of the star.
- **L**: Luminosity relative to the Sun.
- **R**: Radius relative to the Sun.
- **A_M**: Absolute magnitude.
- **Color**: Star color (normalized during preprocessing).
- **Spectral_Class**: Spectral class of the star (e.g., O, B, A, F, G, K, M).

Preprocessing steps include:
- Normalizing inconsistent entries in the `Color` column.
- Converting categorical values into numerically encoded formats.

## Author
**Rosa Reyes**  
Course: Machine Learning
Institution: Universidad Carlos III de Madrid (UC3M)
