# modelling-workshop-ongoing towards 02/02/25
# 🧠 Breast Cancer Diagnosis Using Statistical Neural Networks  

## 📌 Introduction  
Breast cancer is the **second leading cause of cancer-related deaths** among women. Early and accurate diagnosis is crucial for better treatment outcomes. This project implements **Statistical Neural Networks (SNNs)** to improve classification accuracy for breast cancer diagnosis.  

### 🏥 Methods Used:  
- **Radial Basis Function (RBF) Networks** – Uses nonlinear transformations for pattern recognition.  
- **Probabilistic Neural Networks (PNN)** – A Bayes-based classifier that estimates probability density functions.  
- **General Regression Neural Networks (GRNN)** – A function approximation model based on Nadaraya-Watson kernel regression.  

## 📊 Dataset  
- **Source:** University of Wisconsin Hospitals, Madison  
- **Samples:** 699 total (683 complete, 16 missing values)  
- **Attributes:** 9 cell features (e.g., cell shape, chromatin texture, mitotic count)  
- **Class Labels:**  
  - **Benign (Non-cancerous)**  
  - **Malignant (Cancerous)**  

## 🚀 Methodology  
Each model processes the dataset and performs **classification based on tumor characteristics**. The key steps include:  
1. **Data Preprocessing** – Handling missing values, normalization, and feature selection.  
2. **Model Training** – Training different SNN architectures on the dataset.  
3. **Evaluation Metrics** – Accuracy, precision, recall, and F1-score to assess performance.  
4. **Prediction** – Given a new tumor sample, the trained model predicts whether it is **benign or malignant**.  

## 🛠 Installation  
To set up and run this project, follow these steps:  
```bash
# Clone the repository
git clone https://github.com/yourusername/Breast-Cancer-Diagnosis.git

# Navigate to project directory
cd Breast-Cancer-Diagnosis

# Install dependencies (if required)
pip install -r requirements.txt
# Performance Evaluation
The models are evaluated using:
✅ Accuracy – Measures overall correctness of classification.
✅ Precision & Recall – Evaluates false positives and negatives.
✅ F1-Score – Balances precision and recall.

# Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

# License
This project is licensed under the MIT License.
