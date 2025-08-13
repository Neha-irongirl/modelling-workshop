# Breast Cancer Diagnosis using Statistical Neural Networks

This project implements three statistical neural network models:
**"Breast Cancer Diagnosis Using Statistical Neural Networks", using the provided
Wisconsin Breast Cancer Diagnostic (WBCD) dataset.


### 1. Radial Basis Function Network (RBF)
- Spread parameter: **4.4**
- Hidden layer applies Gaussian radial basis transformation.
- Output layer is a linear combination of hidden unit activations.

### 2. Probabilistic Neural Network (PNN)
- Sigma parameter: **1.0**
- Implements Bayes' decision rule with Parzen window probability density estimation.
- Classifies samples based on maximum posterior probability.

### 3. General Regression Neural Network (GRNN)
- Bandwidth parameter (h): **3.0**
- Implements Nadaraya–Watson kernel regression for classification.

## Dataset
The dataset used is the **Wisconsin Breast Cancer Diagnostic dataset** (`data.csv`).
- Target: `diagnosis` (M = malignant, B = benign)
- 30 numerical features extracted from digitized images of fine needle aspirates.

## Requirements
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn

Install requirements via:
```bash
pip install numpy pandas scikit-learn scipy matplotlib seaborn
```

## Usage
1. Place `data.csv` in the same directory as the notebook.
2. Open and run `Breast_Cancer_Statistical_NNs_Full_With_CM.ipynb` in Jupyter Notebook or JupyterLab.
3. The notebook will:
   - Preprocess the dataset
   - Train RBF, PNN, and GRNN using parameters from the paper
   - Output accuracy, classification report, and confusion matrix for each model

## Output
For each model, you will see:
- Accuracy score
- Classification report (Precision, Recall, F1-score)
- Confusion matrix heatmap

At the end, a summary table compares accuracies of all models.

## Paper Reference
Tüba KIYAN, Tülay YILDIRIM, *Breast Cancer Diagnosis Using Statistical Neural Networks*,
Istanbul University – Journal of Electrical & Electronics Engineering, 2004.


