# Biomechanical Features of Orthopedic Patients

## Project Overview

This project aims to classify patients into two categories (Normal and Abnormal) based on six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine. The categories Disk Hernia and Spondylolisthesis are merged into a single 'abnormal' category. Our goal is to utilize various machine learning algorithms to effectively classify these patients.

## Installation

To run this project, you will need Python and the following libraries:
- Pandas
- NumPy
- Matplotlib
- scikit-learn

You can install these packages using pip:

## Dataset

The dataset used (`Ml.csv`) includes six biomechanical features:
- Pelvic incidence
- Pelvic tilt
- Lumbar lordosis angle
- Sacral slope
- Pelvic radius
- Degree spondylolisthesis

## Features and Target Class

The target class is binary, representing 'Abnormal' (1) and 'Normal' (0) conditions. The dataset is preprocessed for null value check, duplicate removal, and feature correlation analysis.

## Methodology

We employ several machine learning algorithms, including:
- Linear Regression
- Decision Tree
- Support Vector Machine (SVM)
- K-Nearest Neighbours (KNN)

Each algorithm's performance is evaluated to determine the most effective classifier for this dataset.

## Results

The project concludes that the Support Vector Machine algorithm yields the best accuracy for this dataset. Detailed results and evaluations are available in the Jupyter Notebook (`Machine Learning Project.ipynb`).

## Usage

To run the analysis:
1. Clone this repository.
2. Run the Jupyter Notebook to see the analysis and results.

## References

- [NCBI Article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6030383/)
- [Dataset on Kaggle](https://www.kaggle.com/uciml/biomechanical-features-of-orthopedic-patients)



## Acknowledgments

Special thanks to the School of Emerging Science and Technology, Gujarat University for their support and guidance.
